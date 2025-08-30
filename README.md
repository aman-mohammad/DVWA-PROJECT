# **DVWA Project**

## **Project Overview**

This project demonstrates web application security testing using **DVWA (Damn Vulnerable Web Application)**. It showcases vulnerabilities like **SQL Injection**, which are intentionally left for educational purposes.

---

## **Features**

* Vulnerable login page for testing.
* SQL Injection vulnerability demonstration.
* Configurable security levels: Low, Medium, High, Impossible.
* Documentation of setup, attack steps, and results.

---

## **Setup Instructions**

**Prerequisites:**

* Docker installed on your machine.
* Basic knowledge of web security testing.

**Steps to Run:**

1. Pull the DVWA Docker image:

   ```bash
   docker pull vulnerables/web-dvwa
   ```
2. Run the DVWA container:

   ```bash
   docker run --rm -it -p 8080:80 vulnerables/web-dvwa
   ```
3. Open your browser and go to: `http://localhost:8080`
4. Login with default credentials:

   * Username: `admin`
   * Password: `password`
5. Set **Security Level** to **Low** in DVWA Security page to perform tests.

---

## **Documentation**

* Screenshots of DVWA Login, SQL Injection (before and after attack), and Security page are included in the repository.
* Detailed steps and explanations are provided in the attached Word/PDF file.

---

## **Purpose**

This project helps interns understand web application vulnerabilities and the importance of securing web forms and databases.

---

## **Author**

* Name: Aman Ahmed Mohammad
* Internship: Codec Technologies 
* Email: amanabd2610@gmail.com
