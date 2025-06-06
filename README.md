# BUKIDNON NATIONAL HIGH SCHOOL INVENTORY SYSTEM

## Overview
The Bukidnon National High School (BNHS) Inventory System is a web-based application designed to manage and track school inventory assets. This system facilitates the monitoring of supplies, equipment, and materials for efficient resource management within the school.

## Features
- **User Authentication**: Separate login portals for administrators and staff
- **Inventory Management**: Track and manage all school assets
- **Document Generation**: Create and manage inventory-related documents including:
  - Inspection and Acceptance Reports (IAR)
  - Property Acknowledgment Receipts (PAR)
  - Requisition and Issue Slips (RIS)
  - Inventory Custodian Slips (ICS)
- **Supplier Management**: Maintain supplier information and relationship
- **Report Generation**: Generate inventory reports for administrative purposes

## Technology Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: XAMPP

## Installation Requirements
1. XAMPP (or alternative with Apache, MySQL, PHP)
2. Web Browser
3. Git (optional, for version control)

## Setup Instructions
1. Open your XAMPP Control Panel and start Apache and MySQL services
2. Extract the downloaded source code zip file
3. Copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory
4. Browse the PHPMyAdmin in a browser (http://localhost/phpmyadmin)
5. Create a new database naming `database_bnhs`
6. Import the provided SQL file. The file is known as `database_bnhs.sql` located inside the database folder
7. Browse the BNHS Inventory System in a browser:
   - Admin Portal: http://localhost/BNHS_INVENTORY_SYSTEM/admin/
   - Staff Portal: http://localhost/BNHS_INVENTORY_SYSTEM/staff/

## User Access
- **Admin Portal**: `/BNHS/admin/`
- **Staff Portal**: `/BNHS/staff/`

## Default Login Credentials
### Admin Access
- **Username**: admnstrator23@gmail.com
- **Password**: Admin@123

### Staff Access
- **Username**: u7382361@gmail.com
- **Password**: User@123

## Security
The system implements security measures including:
- Password hashing
- User-specific access levels
- Input validation and sanitization

## Developers
- Jino Taer
- Pjohn Colot 
- Steven Benedict Bernabe 

## License


## Support
For support or inquiries, please contact:

## Environment Configuration

1. **Database Configuration**
   1. DB_HOST=localhost           # Replace with your database host if different
   2. DB_NAME=database_bnhs       # Replace with your actual database name
   3. DB_USER=root                # Replace with your database username
   4. DB_PASS=your_password_here  # Replace with your actual database password

2. **Application Settings**
   1. APP_NAME=BUKIDNON_NATIONAL_HIGH_SCHOOL_INVENTORY_SYSTEM
   2. APP_URL=http://localhost/BNHS_INVENTORY_SYSTEM  # Update if your URL is different

3. **Admin Portal**
   1. ADMIN_URL=/BNHS/admin/

4. **Staff Portal**
   1. STAFF_URL=/BNHS/staff/

5. **Security Settings**
   1. APP_DEBUG=false             # Set to false in production
   2. APP_ENV=production          # Use 'development' for development environment

6. **Session Settings**
   1. SESSION_LIFETIME=120
   2. SESSION_SECURE=true         # Set to true when using HTTPS

