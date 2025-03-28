# Fraud Investigation Forensic

## Overview
The **Fraud Investigation Forensic Management System** is a comprehensive platform designed to manage and maintain forensic lab data, officer records, and suspect details efficiently. This system ensures secure data handling and streamlines forensic case management with **voice-based access control**.

## Features
- **Forensic Data Management**: Store and update forensic reports and case files.
- **Officer Records Maintenance**: Maintain investigator and forensic officer details.
- **Suspect Tracking**: Log and update suspect data for ongoing investigations.
- **Voice Access Control**: Uses voice authentication for access authorization.
- **Database Integration**: Data is securely stored and managed using **MySQL (phpMyAdmin)**.
- **User Authentication**: Secure login system for authorized personnel.
- **XAMPP-Based Deployment**: The system runs on a local **XAMPP server** with **PHP and MySQL**.

## Technologies Used
- **PHP** – Backend for data management.
- **MySQL (phpMyAdmin)** – Database for storing case files and user records.
- **JavaScript, HTML, CSS** – Frontend for user interface.
- **AI Voice Authentication** – For secure access control.
- **XAMPP** – Local server environment for execution.

## Installation & Setup
1. **Install XAMPP** if not already installed:
   - Download and install from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)

2. **Start XAMPP & phpMyAdmin**:
   - Open XAMPP Control Panel and start `Apache` and `MySQL`.
   - Open `http://localhost/phpmyadmin/` and create a new database named **fraud_forensic**.

3. **Clone the Repository**:
   ```sh
   git clone https://github.com/Meghana230211/Fraud-investigation-forensic.git
   cd Fraud-Investigation-Forensic
   ```

4. **Import the Database**:
   - Go to `phpMyAdmin` and import the provided **fraud_forensic.sql** file.

5. **Run the Project**:
   - Place the project folder in `xampp/htdocs/`.
   - Open a web browser.

## Usage
- **Login as an admin** to manage forensic records.
- **Add, update, and delete suspect and case data** as required.
- **Use voice authentication** for secure access to sensitive records.
- **Generate reports and maintain investigation logs**.

## Future Enhancements
- **Cloud-based storage** for forensic data.
- **AI-powered case analysis and fraud detection.**
- **Integration with law enforcement databases.**

## Contributor
- **Meghana M**

For any inquiries or contributions, feel free to submit a pull request or open an issue.

