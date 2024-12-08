# Documentation on Splunk, Nessus Essentials, and Nmap

---

## **Splunk**
Splunk is a powerful platform for monitoring, searching, and analyzing machine-generated data in real-time. It is widely used for log monitoring, security analytics, and IT operations.

### Steps to Add and Analyze Data in Splunk:
- **Add Data**:
  1. Navigate to the **Monitor** section in Splunk.
  2. From the left panel, choose the type of logs you want to monitor.
  
- **Select Source**:
  1. Input event logs for review.
  2. Click **Submit** after verifying the inputs.

- **Start Searching**:
  1. Access the search interface by clicking on **Start Searching**.
  2. Check for **Event IDs**, such as:
     - **4624**: Successful login.
     - **4625**: Failed login.
     - Other IDs for specific actions like biometric logins or password attempts.
  3. Refer to the [Ultimate Windows Security Encyclopedia](https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/) for a comprehensive list of Event IDs.

- **Practical Example**:
  1. Lock your computer.
  2. Enter an incorrect password twice.
  3. Login successfully with the correct password.
  4. Return to Splunk and search for Event IDs **4624** (success) and **4625** (failure).

---

## **Nessus Essentials**
Nessus Essentials is a free vulnerability assessment tool designed for scanning systems to identify security vulnerabilities and configuration issues.

### Steps to Perform a Vulnerability Scan:
1. **Create a New Scan**:
   - Select **New Scan** and choose **Basic Network Scan**.

2. **Configure the Scan**:
   - Add relevant details like the name of the scan and target IP addresses.

3. **Run the Scan**:
   - Navigate to **My Scan**.
   - Launch the scan by clicking **Launch**.
   - Review the results for detected vulnerabilities.

---

## **Nmap**
Nmap (Network Mapper) is an open-source network scanning tool that identifies hosts and services on a network by analyzing ports and fingerprints.

### Steps to Use Nmap:
1. **Launch GUI**:
   - Open **ZenMap** (the GUI version of Nmap for Windows).

2. **Set Scan Parameters**:
   - Enter the target IP address.
   - Choose the type of scan (e.g., Quick, Ping, Regular, Intense).

3. **Run and Analyze**:
   - Click **Scan**.
   - Review the results to see open and closed ports, along with identified vulnerabilities.
