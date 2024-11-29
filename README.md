# Phishing Simulator

A powerful phishing simulation tool designed to create, test, and educate users about phishing attempts in a controlled environment. This project uses **GoPhish** to simulate real-world phishing campaigns while promoting awareness and teaching cybersecurity best practices.

---

## Features
- Create and manage phishing campaigns.
- Simulate phishing attacks with customizable landing pages and emails.
- Analyze results to identify potential security vulnerabilities.
- Educate users about identifying and avoiding phishing attempts.

---

## Requirements
- **Operating System:** Windows, macOS, or Linux
- **GoPhish Executable**
- **Browser:** Modern web browser (e.g., Chrome, Firefox)

---

## Installation
1. **Download GoPhish:**
   - Download the latest release from the [official GoPhish GitHub page](https://github.com/gophish/gophish/releases).
   - Extract the contents to a directory, e.g., `C:\Users\YourUsername\Desktop\GoPhish`.

2. **Run GoPhish:**
   - Open a terminal (PowerShell or Command Prompt).
   - Navigate to the directory where GoPhish is located:
     ```bash
     cd C:\Users\YourUsername\Desktop\GoPhish
     ```
   - Run the GoPhish executable:
     ```bash
     .\gophish.exe
     ```
   - Note the admin login credentials (username and password) provided in the terminal.

3. **Access the Dashboard:**
   - Open a browser and visit the GoPhish admin dashboard at [https://127.0.0.1:3333](https://127.0.0.1:3333).
   - Log in using the credentials from the terminal.

---

## Setting Up a Phishing Campaign
1. **Create Users and Groups:**
   - Add email recipients by creating user groups in the dashboard.

2. **Design a Landing Page:**
   - Use the included HTML landing page or create your own.
   - Customize the landing page with relevant phishing content.

3. **Configure a Campaign:**
   - Create a campaign in the dashboard.
   - Specify the user group, email template, and landing page.
   - Set a schedule to deploy the campaign.

4. **Test and Educate:**
   - Launch the campaign and monitor results.
   - Share simulated phishing emails and results with users to promote awareness.

---

## Files
- **gophish.exe**: The GoPhish executable to start the server.
- **landing_page.html**: Example phishing landing page (editable).
- **campaign_data.json**: Stores information about configured campaigns.
- **config.json**: Configuration file for server settings.

---

## Running in VS Code
1. Open the project folder in VS Code.
2. Use the built-in terminal to navigate to the GoPhish directory:
   ```bash
   cd C:\Users\YourUsername\Desktop\GoPhish
