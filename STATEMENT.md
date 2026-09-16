# Project Statement

**Problem Statement:** 
Traditional library operations face challenges with manual administration, stock management, and quota enforcement[cite: 1]. This project addresses these operational challenges by providing a standalone terminal application to streamline core library administration tasks, including automated quota enforcement, stock management, and concurrency control[cite: 1].

**Scope of the Project:** 
The system manages a catalog of physical and reference books, registers student and staff members, tracks book checkouts and returns, and computes overdue fines automatically[cite: 1]. It safely handles concurrent transaction processing using thread synchronization to prevent race conditions during simultaneous book checkouts[cite: 1]. All library records are persisted locally using an embedded SQLite database[cite: 1].

**Target Users:** 
Library staff and student members[cite: 1].

**High-Level Features:** 
1. **Catalog & Member Management:** Register users with automated borrowing limits and manage both borrowable physical inventory and non-borrowable reference books[cite: 1].
2. **Borrowing & Returns:** Safely issue books, process returns, and automatically calculate overdue fines at a rate of ₹2.50/day[cite: 1].
3. **Reporting & Data Export:** Generate formatted text summary reports, perform binary database backups, and export data to CSV files[cite: 1].
