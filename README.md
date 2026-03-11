# 📅 09 Mar 2026  

**🔹 UC17 – Update and Sync Database Contact (JDBC)** Branch: feature/UC17-update-contact-and-sync-with-db

# Objective

- Implement functionality to update contact information in the MySQL database
- Ensure the application's local memory remains synchronized with the database after an update

# Implementation

- Developed the `updateContactRecord()` method using SQL **PreparedStatement** for secure updates
- Implemented a synchronization logic that updates the local `ArrayList` only after a successful DB commit
- Used the `firstName` as a unique identifier to locate and modify specific contact attributes (e.g., Address, Phone)
- Verified data integrity by re-fetching or comparing the updated record from the database to ensure "Single Source of Truth"

[feature/UC17-update-contact-and-sync-with-db](https://github.com/abhishekkushwaha-2003/AddressBookApp/tree/feature/UC17-update-contact-and-sync-with-db)

---
