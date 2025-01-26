# Email-Hacking
Disclaimer:"only for educational purposes and i am not responsible for any illegal uses"
**Project Description: Gmail Phishing using Setool (Educational Purposes)**

**Overview:**
This project demonstrates the process of phishing a Gmail account using SET (Social Engineering Toolkit) for educational purposes only. The purpose is to understand how phishing attacks work and how to mitigate them. It should never be used for malicious intent.

**Steps:**

1. **Install SET (Social Engineering Toolkit) or already available available on kali and parrot sec:**
   - Ensure Kali Linux or a similar Linux distribution is installed on your system.
   - Install SET by running the following command in terminal:
     ```bash
     sudo apt-get install setool
     ```

2. **Start SET:**
   - Launch SET using the command:
     ```bash
     sudo setool
     ```
   - It will present a menu with different attack options.

3. **Choose Phishing Attack:**
   - Select option `1` for "Social-Engineering Attacks."
   - Then, choose option `2` for "Website Attack Vectors."
   - Select option `3` for "Credential Harvester Attack Method."

4. **Configure the Phishing Page:**
   - SET will ask for the URL to clone. Provide the URL for Gmail (e.g., `https://mail.google.com`).
   - SET will generate a cloned phishing page that looks identical to Gmail's login page.
   
5. **Set Up Listener:**
   - SET will ask for the IP address to listen on. Enter your local machine's IP address or `0.0.0.0` for any available network interface.
   - It will generate a URL, which you can share with potential victims to lure them into entering their login credentials.

6. **Victim Interacts with Phishing Page:**
   - When the victim clicks on the phishing link, they will be directed to the cloned Gmail login page.
   - If they enter their credentials, the information will be captured and stored.

7. **Capture Credentials:**
   - The entered credentials will be logged and saved by SET. You can view the captured data in the console.

**Important Note:** This is strictly for educational purposes to demonstrate the risks of phishing attacks. Never engage in any malicious activities or attack others' accounts without permission. Always ensure ethical behavior and proper authorization in cybersecurity tasks.
