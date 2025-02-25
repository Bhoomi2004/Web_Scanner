# Website Security Scanner

## 📌 Overview
The **Website Security Scanner** is a tool designed to analyze website URLs for security vulnerabilities, trust scores, SSL certificate validity, and backlink analysis. It helps users assess the reliability of a website by displaying key security metrics in an intuitive visual format.

## 🚀 Features
- 🔍 **Trust Score Analysis**: Evaluate a website's credibility based on various security parameters.
- 🛡 **Vulnerability Detection**: Identify potential security risks using OWASP ZAP API.
- 🔗 **Backlink Analysis**: Check inbound links to determine a website’s authenticity.
- 🔒 **SSL Certificate Validation**: Verify if a website has a valid SSL certificate.
- 📊 **Graphical Representation**: Display security metrics using interactive charts.

## 🛠 Tech Stack
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Python 
- **APIs Used**:
  - [VirusTotal API](https://www.virustotal.com/)
  - [OWASP ZAP API](https://www.zaproxy.org/)


## 🔧 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/website-scanner.git
   cd website-scanner
   ```
2. Install dependencies:
   ```bash
   pip install -r backend/requirements.txt
   ```
3. Install owasp Zap in your system and change the api key in the backend
   ```
5. Run the backend:
   ```bash
   python backend/back.py
   ```   
6. Open `frontend/front.html` in a browser.

## 📌 Usage
1. Enter a website URL in the input field.
2. Click the "Scan" button to analyze the site.
3. View trust score, vulnerabilities, and SSL status in the visual dashboard.
4. Click on charts for detailed analysis.

## 📬 Contact
For any inquiries or suggestions, feel free to reach out:
- 📧 Email: bhoomimehta2004@gmail.com
