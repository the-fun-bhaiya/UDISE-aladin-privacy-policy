# Privacy Policy for UDISE+ Automator

**Last Updated: June 2026**

This Privacy Policy describes how the **UDISE+ Automator** browser extension (available for Firefox and Microsoft Edge) handles data. We believe in absolute transparency and absolute user privacy.

### 1. No Data Collection (Zero-Server Architecture)
UDISE+ Automator operates entirely on your local machine. 
* **No External Servers:** The extension does not communicate with any external servers, third-party databases, or analytics engines. 
* **No APIs Used:** We do not use any tracking APIs or data collection tools. 
* **No Transmission:** None of the data from the Excel files you upload or the government portal you interact with is ever transmitted, leaked, or saved outside your local browser environment.

### 2. How Data is Processed Locally
* **Excel Files:** When you generate or upload an Excel template, the parsing and reading of that data happen strictly within your browser's local sandbox memory using pure client-side JavaScript.
* **Automation Workflow:** The data read from your Excel sheet is directly injected into the official UDISE+ portal inputs while you watch it happen live on your screen. 
* **Transient Memory:** Once the browser tab is closed or the extension finishes execution, all parsed student data is completely wiped out from the extension’s active memory.

### 3. Permissions Requested & Why
To function correctly, the extension requires the following permissions:
* `activeTab` or Host Permissions for the official UDISE+ domain: Required strictly to read the input fields of the form and automate the clicks/typing on your behalf.
* `storage`: Used solely to store your operational preferences (such as the automation state or pausing preferences) locally within your own browser.
* **Host Permissions (`https://*.udiseplus.gov.in/*`):** Required strictly to allow the extension to run its automation features on the official government UDISE+ domains where the forms are located.
* **`scripting`:** Used solely to inject the core automation engine and helper scripts safely into the active UDISE+ web pages to simulate form-filling actions.
* **`tabs`:** Required to interact with the current active tab, ensuring the automation stays synchronized with the exact page the user is currently looking at and to prevent execution on wrong domains.

### 4. Third-Party Websites
This extension interacts only with the user-provided Excel documents and the official government UDISE+ portal. We have no control over, and assume no responsibility for, the privacy policies or practices of the official government portals.

### 5. Contact
If you have any questions or feedback regarding this absolute privacy commitment, you can open an issue directly on our official GitHub repository.
