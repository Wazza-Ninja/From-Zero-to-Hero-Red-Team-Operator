# From-Zero-to-Hero-Red-Team-Cyber-Operator
This repo is suppose to be considered regular update sophisticated techniques.
 

| First Header  | Second Header | 
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | 


# Cyber Kill Chain
| Command | Description |
| --- | --- |
| reconnaissances |The first stage of the cyber kill chain is reconnaissance. In this stage, the attacker is assessing the target from outside of the organization from both a technical and non-technical perspective. In this stage, the attacker is working to determine which targets will return the most benefit for the resources expended in exploiting the target's information systems. The attacker will be looking for information systems with few protections or exploitable vulnerabilities.Active Information Gathering: With active information ***gathering and reconnaissance***, the attacker actively interacts with the target system. An example of active information gathering and reconnaissance is port scanning, where the attacker works to enumerate open ports. The goal of the attacker, in this case, is to uncover ports that are vulnerable to exploitation and therefore would provide a means for the attacker to access the target system. ***Passive Information Gathering***: Passive information gathering and reconnaissance attempt to obtain information related to the target information systems without engaging those information systems directly. |
| Weaponization |The second stage of the cyber kill chain is weaponization. During weaponization, the threat actor develops malware specifically crafted to the vulnerabilities discovered during the reconnaissance phase of the cyber kill chain. Based on the intelligence gathered in the reconnaissance phase, the attacker will tailor their toolset to meet the specific requirements of the target network.For example, if a specific vulnerable version of secure shell was discovered, the attacker would build an exploit kit that takes advantage of the vulnerability. The kit will not just focus on the exploitation of vulnerabilities. The kit's design will ensure that the attacker has administrative privileges on the exploited information system so that further actions can be taken on the computer as required. Additionally, if the internet is accessible, the attacker will build in a command-and-control capability allowing full remote access to the exploited information system. |
| Delivery | The third stage in the cyber kill chain, delivery, involves transmitting the APT code from the attacker to the target information system for exploitation. a network attack is most likely to originate from a spear-phishing attack targeting an internal employee of the organization. A carefully researched and crafted spear-phishing campaign against an organization based on information gathered during the reconnaissance phase would result in the organization's employees executing the APT malware code on their information systems. The spear phishing message will most likely contain an attachment such as a Microsoft Word or an Adobe PDF document. The attachment would contain code that, when executed, would result in the APT gaining a foothold on the organizational network.Another available opportunity for exploitation is examining the organizational public IP space for mismanaged servers. A lack of cyber hygiene practices within an organization's network could result in vulnerable production systems.  |
| Exploitation | During the exploitation phase, the APT malware code is executed on the target network through remote or local mechanisms, taking advantage of discovered vulnerabilities to gain superuser access to the targeted organizational information system |
| Installation |Once the exploitation of the system has been successful, the APT malware code will install itself onto the targeted information system. At this point, the APT malware will begin to download additional software if network access is available. This allows the delivery payload to remain small and undetectable.The small size of the malware in this example would have limited functionality. Therefore, the APT will download additional components to have better control of the exploited information systems and to penetrate further into the target organization's network. |
| Command And Control | Command and control is the sixth phase of the cyber kill chain. Command and control, also known as C2, is when the attacker has put in place their management and communication APT code onto to the target network. This software allows the attacker to fully manage the APT code in the environment and allows the attacker to move deeper into the network, exfiltrate data and conduct destruction or denial of service operations. |


# Tools Tactics and Procedures (TTP)

Red Teaming is a multi-layered, full-scope attack simulation program designed to measure how well people, networks, applications and physical security controls of an organization can withstand an attack from a real-life adversary. This type of assessment is designed for mature organizations that want to test the effectiveness of their defense and overall security level. 


| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |



# Learn Red Team From Scratch Section


| Command | Description |
| --- | --- |
| How To use Cobalt Strike | List all new or modified files |
| git diff | Show file differences that haven't been staged |


| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |


| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |



