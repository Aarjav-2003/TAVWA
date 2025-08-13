# TAVWA - TheAarjav Vulnerable Web Application

**TAVWA** (TheAarjav Vulnerable Web Application) is an intentionally insecure PHP/MySQL web application created by **Aarjav Sharma** for educational and penetration testing exercises in a safe, controlled environment.

This project is inspired by the concept of intentionally vulnerable applications (such as DVWA & XVWA) and contains multiple well-known web security flaws for students and researchers to practice secure coding and ethical hacking skills.

⚠ **Disclaimer**  
Do NOT host TAVWA on a live or production server. It is deliberately insecure and must only be used in an offline lab or isolated virtual machine. The author is not responsible for any misuse.

---

## Features

TAVWA includes labs and scenarios for the following vulnerabilities:

- **SQL Injection** (Error-based & Blind)
- **OS Command Injection**
- **XPATH Injection**
- **Formula Injection**
- **PHP Object Injection**
- **Unrestricted File Upload**
- **Cross-Site Scripting (XSS)** — Reflected, Stored, DOM-based
- **Server Side Request Forgery (SSRF) / Cross Site Port Attacks**
- **File Inclusion** (Local / Remote)
- **Session Management Flaws**
- **Insecure Direct Object Reference (IDOR)**
- **Missing Functional Access Control**
- **Cross-Site Request Forgery (CSRF)**
- **Weak Cryptography**
- **Unvalidated Redirects & Forwards**
- **Server-Side Template Injection (SSTI)**

---

## Requirements

- **Web Server:** Apache/Nginx
- **PHP:** 5.6+ (PHP 7.x or 8.x supported)
- **Database:** MySQL or MariaDB
- **Local Environment:** XAMPP, WAMP, MAMP, LAMP stack or Docker
- **Browser:** Any modern browser

---

## Installation

1. **Clone or Download:**
```
git clone https://github.com/YOUR-USERNAME/TAVWA.git
```

2. **Move to Web Directory:**
- For XAMPP (Windows):
  ```
  C:\xampp\htdocs\TAVWA
  ```
- For Linux LAMP:
  ```
  /var/www/html/TAVWA
  ```

3. **Create Database:**
- Access phpMyAdmin or MySQL
- Create a database, e.g., `tavwa`
- Import the SQL file from the `db/` folder

4. **Edit Configuration:**
- Open `config/config.inc.php`
- Set your MySQL username, password, and database name

5. **Run in Browser:**
```
http://localhost/TAVWA/
```

---

## Usage

- **Navigation:** Use the sidebar to choose a vulnerability lab to test
- **Testing Tools:** You may use Burp Suite, OWASP ZAP, or browser developer tools to simulate exploitation
- **Reset:** Use the "Setup / Reset" option to restore default database values

---

## Project Structure

<img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/23d196fc-50e4-4d81-a1b9-6abdbd7840a9" />

---

## Author

**Aarjav Sharma**  
Cybersecurity Enthusiast | Ethical Hacking & Forensics Student

---

## License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) file for details.

---

## Educational Purpose

TAVWA is meant for:
- Learning how vulnerabilities work
- Practicing ethical hacking in labs
- Demonstrating attacks and defenses to students or clients

---

**Happy Hacking (Ethically) 🔐**

