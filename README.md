
# Web-based Secure Login and Registration System

This is a university assignment-based project called UOS2024.

- Install and run at `localhost:8080` using **Apache Server**
- Used **PHPMailer** Libary to send OTPs via Gmail
- Used **Google Authenticator** Libary for TOTP authentication

## Installation

#### Local Host Server Installation

- Download [XAMPP](https://www.apachefriends.org/index.html)

#### Project Folder Configuration

- Download and extract my project folder called `UOS2024`

- Copy `uos2024` folder to `C:\xampp\htdocs`

#### Apache Configuration

- Replace `C:\xampp\apache\conf\httpd.config` with `UOS2024\httpd.config`

#### SQL Server Configuration

- Replace `C:\xampp\mysql\data` with `UOS2024\data` to create database and table.

#### PHP Configuration

- Replace `C:\xampp\php.ini` with `UOS2024\php.ini`
    
## Tech Stack

**Client:** HTML, CSS, JavaScript

**Server:** PHP, MySQL

## Security Features

- Google reCAPTCHA and Honeypot
- Text-based Password Strength Meter
- Email Two-Factor Authentication
- Support Authenticator Apps
- Password Hashing and AES Data Encryption

## Running Tests

- Use `CURL` or `Postman` to test captcha and honeypot

## Troubleshooting

#### MySQL Module crash

If MySQL shutdown automatically and cannot start properly in XAMPP, 

- Stop all module services from XAMPP control panel

- go to `C:\xampp\mysql`

- rename `C:\xampp\mysql\data` as `C:\xampp\mysql\data_old`.

- copy `C:\xampp\mysql\backup` and rename it to `C:\xampp\mysql\data`

- go to `C:\xampp\mysql\data_old`

- copy `performance_schema` folder, `uos2024` folder, `aria_log.00000001`, `aria_log_control`, `ib_buffer_pool`, `ib_logfile0`, `ib_logfile1`, `ibdata1`, and `ibtmp1`.

- replace them in `C:\xampp\mysql\data`

- restart MySQL Module service.

## Help

If you have any technical error during running or testing, please reach out to us at kohtutoo19@gmail.com
