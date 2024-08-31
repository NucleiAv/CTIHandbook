# Mobile Endpoint Protection

**1. Major Mobile Operating Systems:**

* **iOS:**
  * Developed by Apple, exclusively for Apple devices.
  * Launched in 2007, currently on version 13.
  * iOS devices make up \~13% of smartphones and 60% of tablets worldwide.
  * MDM capabilities available since iOS 6.
* **Android:**
  * Initially developed by Android Inc., acquired by Google in 2005.
  * Based on the Linux kernel, currently on version 10.
  * Accounts for \~86% of smartphones and 39% of tablets worldwide.
  * MDM capabilities available since Android 2.2.

**2. Differences Between Mobile and Traditional Endpoints:**

* Users do not interface directly with the OS; applications act as intermediaries.
* OS stability can be easily monitored; any breach in the security chain is noticeable.
* Antivirus software on mobile is limited in its scope compared to desktop counterparts.

**3. Primary Threats to Mobile Endpoints:**

<figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

* **System-Based Threats:**
  * **Jailbreaking (iOS):** Gaining unauthorized access to features, voiding warranties, and exposing the device to malware.
  * **Rooting (Android):** Modifying the OS for customization, potentially creating vulnerabilities.
* **App-Based Threats:**
  * **Phishing Scams:** Via SMS or email, leading to security breaches.
  * **Malicious Apps:** Even from official stores, apps may request irrelevant access to hardware or contain malicious code.
  * **Web Browsers:** Vulnerable to pop-ups and malicious links.
* **External Threats:**
  * **Network-Based Attacks:** Wi-Fi and Bluetooth vulnerabilities, social engineering.
  * **Tethering to External Media:** Exploiting physical access to the device.

**4. Mobile Endpoint Protection Strategies:**

* **Mobile Device Management (MDM):**
  * Control content, restrict access, and remediate infected devices.
  * Lock down devices if lost or stolen.
* **App Security:**
  * Use third-party app ratings, antivirus programs, and install only trusted apps.
* **User Training:**
  * Regularly educate users on mobile threats and safe practices.
* **Day-to-Day Operations:**
  * **Monitor OS Versions:** Ensure up-to-date OS versions as updates include vulnerability fixes.
  * **Monitor App Installs:** Keep track of app versions, especially on mobile OS where rolling back versions is difficult.
  * **Enforce Encryption:** Ensure devices are encrypted, with additional security layers like passcodes and biometrics.
  * **Distribute Secure Payloads:** Only distribute verified secure payloads.
  * **Automate Compliance Actions:** Block sensitive info access if a device is compromised.
  * **Enforce NAC Policies:** Control network access to approved devices only.
  * **Contingency Planning:** Have plans in place to quickly respond to widespread infections.
