# Ticket-System-Home-lab
<img width="601" height="390" alt="Screenshot 2026-11-18 at 8 41 23 PM" src="https://github.com/user-attachments/assets/ab269716-d664-46c0-8088-4126d8d36fd5" />
<img width="1228" height="775" alt="Screenshot 2026-11-18 at 8 40 56 PM" src="https://github.com/user-attachments/assets/d6aea792-ddd3-47d3-93a3-0759c26f2131" />
<img width="1071" height="341" alt="Screenshot 2026-11-18 at 9 35 06 PM" src="https://github.com/user-attachments/assets/01d4506a-86b4-4954-9bce-acaa70e27e8e" />
  osTicket Installation & Setup
-[]Downloaded proper osTicket release files
-[]Configured web server and database environment
    -[]Verified PHP 8.2-8.4 installation
    -[]Verified MySQL 5.5+ database availability
-[]Completed initial web-based installation    
    -[]Connected to database using dedicated credentials
    -[]Created primary administrator account
-[]Security & Permissions Configuration
    -[]Locked down core configuration files
        -[]Removed write access from include/ost-config.php
        -[]Deleted the setup directory from the server
-[]User Management & Troubleshooting
    -[]Configured email validation settings
        -[]Used a standard placeholder domain (e.g., @example.com) to bypass local domain validation             errors
-[]Verified user roles and access
    -[]Confirmed Admin Panel access for management
    -[]Confirmed End-User Portal access for ticket creation
