## Detection as Code - Email URL Interaction

<img align="left" alt="MITRE ATT&CK Logo" width="120px" src="https://attack.mitre.org/theme/images/mitre_attack_logo.png"/>
<br/>

- [T1566.002 - Phishing Spearphishing Link](https://attack.mitre.org/techniques/T1566/002)

### Instructions

- You can save this as function or you can have this as simple query by removing the function call in the end (line 13), then removing the semi-colon at the end of line 12, and removing the variable on line 7, you can do it by commenting what you don't want the system to consider. Then you have line 8 to line 12 (without the semi-colon).
- line 10
    - Add the recipient email (the email from user you are investigating and want to know if there was any click).
- Line 11
    - We can comment it out unless we want to investigate by sender. Then we can comment line 10.

<br/>
<img align="left" alt="Detections.ai logo" width="120px" src="https://detections.ai/detections-logo-navbar.svg"/>
<br/>

<p>This simple query helps detect whether a user interacted with the URL within the email message or not.</p>

- [Link to the KQL contribution](https://detections.ai/rules/019be674-caf7-744e-b252-5feadfb090f8)
- [Link to the Sigma contribution](https://detections.ai/rules/019c8e79-cd3f-776f-a54d-db4c20cac009)
