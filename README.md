# Password-Security-Anaysis
 This project is a web application that helps users determine if their passwords have been compromised in known data breaches. It integrates with the Have I Been Pwned (HIBP) API to securely check password security while maintaining user privacy.
Features
Secure Password Check: Uses SHA-1 hashing to check passwords against a database of compromised credentials.
User-Friendly Interface: A simple and responsive web UI built with HTML, CSS, and JavaScript.
Real-Time Feedback: Notifies users if their password has been found in previous breaches.
Project Structure
server.py - Backend server using Flask to handle API requests and password checks.
index.html - Frontend UI for password input and result display.
style.css - (Optional) Stylesheet for better UI experience.
Execution Instructions
Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/password-security-analysis.git
cd password-security-analysis
Install dependencies:
bash
Copy
Edit
pip install flask requests
Run the server:
bash
Copy
Edit
python server.py
Access the application: Open your browser and go to http://127.0.0.1:5000/.
