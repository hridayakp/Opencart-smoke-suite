# Opencart-smoke-suite
OpenCart Manual QA Smoke Suite (UI + Database)
A targeted Smoke Testing Suite for an OpenCart e-commerce platform, demonstrating technical proficiency in functional testing and backend SQL verification.

##Testing Highlights
Focused Scope: 10 high-priority smoke test cases covering the critical "Happy Path" of the application.

Database Integrity: Every UI action—from Registration to Order Placement—is validated using MySQL Workbench to ensure accurate data storage.

Security Validation: Verified brute-force protection by monitoring and querying the oc_customer_login table after failed attempts.

Data Flow Analysis: Tracked user and order information across multiple relational tables to confirm system consistency.

##Key Documents
Test Suite: Opencart_smoke_suite_Hridaya.xlsx.

Includes Pre-conditions, Step-by-Step execution, and specific SQL verification queries for every test case.

Evidence: Screenshots documenting the "Pass" status for both the web interface and the corresponding database records.

##Tech Stack
E-commerce: OpenCart (Localhost/XAMPP)

Database: MySQL / MySQL Workbench

Documentation: Microsoft Excel
