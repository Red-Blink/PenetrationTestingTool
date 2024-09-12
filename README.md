# Penetration Testing Tool

This is a simple cybersecurity tool I developed for penetration testing. It scans a specified host for active services and their versions, then cross-references these with the Metasploit database to identify potential vulnerabilities. It's designed for ease of use and provides essential insights for security assessments.

**Requirements:**
- Python3
- Python3-Nmap
- Nmap
- Metasploit
- Flask

**Getting Started:**
- Clone the repository to your server with: `git clone https://github.com/Red-Blink/PenetrationTestingTool.git`
- Navigate to the directory with: `cd PenetrationTestingTool`
- Start the app by running: `sudo python3 -m app`
- Open a web browser and go to `http://PUBLIC_IP:5000`

**Notes:**
- The app allows external access via your public IP address.
- It operates on port 5000. Ensure this port is open in your firewall settings if applicable.
- The tool scans ports up to 9999 by default. To increase this limit, edit the `app.py` file.
