## 1. What is Red Teaming?
<div align="justify">From a historical perspective, red teaming originated from exercises conducted by the US military during the Cold War, with the Soviet Army representing the Red Team and the US Army representing the Blue Team. However, in the realm of cybersecurity, red teaming refers to simulating hostile or adversarial attacks. Generally, if you aim to work as a red teamer, you'll be assigned various tasks depending on the job role, requiring skills across different domains. For example: Finding and enhancing the execution chain of malware for Blue Team evaluation,
such as the following chain: URL > ZIP > JS > cURL > .dll Discovering new and diverse methods to bypass security mechanisms nlike application whitelisting, UAC bypass, AV evasion, EDR evasion, etc.</div> 

## 2. What Red Teaming is Not?

Penetration testing itself is not red teaming; rather, it's one of the penetration techniques, such as web hacking.

## 3. Where is Red Teaming Used?

Offensive Security Maturity Model

![readteam00013](https://github.com/soheilsec/Red-Team-Roadmap/assets/46918547/f2050f1d-40f7-4724-9c15-30fc823bef83 "Cymulate offensive security matuirty model")

<div align="justify">Organizations have various levels of offensive security maturity. Vulnerability scanning and vulnerability assessment are performed across all organizations. Depending on the size of the organizations, they either have an in-house penetration testing department, outsource this function, or even utilize bug bounty programs. Organizations with blue teams use internal or external red teaming to assess team performance and discover security gaps. Purple team exercises serve as a method to establish balance and aid in increasing the efficiency of red and blue teams to achieve higher detection rates and reduce false positives. Simulating APT groups to assess the performance of defensive teams is highly practical.</div> 

## 4. Steps for an Internal Red Team in an Organization:

• Understanding the network, security equipment, and the presence or absence of sensors. \
• Preparing tests according to the network and security equipment and implementing them. \
• Discovering security gaps and reporting them to the blue team. \
• Reviewing and re-executing tests to ensure that the gaps have been addressed. \
• At an advanced level of blue team maturity, simulation of techniques or APT group activities should be conducted by the red team. If an organization has reached maturity and has had at least 4 years of blue teaming, tests should be implemented at a higher level, focusing more on bypassing and observing detection and non-detection by the blue team. Additionally, malware development is one of the most important tasks.

## 5. Types of Red Team Job Positions and Required Skills for Each Level of Job Positions:

**5.1 Red Team Operator:** Red team operators are responsible for conducting offensive security operations, simulating attacks on an organization's systems to identify weaknesses and vulnerabilities. They often perform penetration tests, exploit development, and post-exploitation activities to assess the effectiveness of defensive measures. \
**5.1.1	Junior Red Team operator:** \
•	Familiarity with cybersecurity concepts. \
•	Knowledge of web and network penetration testing. \
•	Familiarity with scripting. \
**5.1.2  Mid-level Red team operator** \
•	Proficiency in web and network penetration testing. \
•	Expertise in automation and tools customization. \
•	Active directory assessment. \
•	Post-exploitation techniques. \
**5.1.3 Senior Red Team operator** \
•	Mastery in web and network penetration testing. \
•	Advanced skills in tools and exploit development. \
•	Knowledge of evasion techniques. \
•	Conducting APT emulation and simulation. \
**5.2 Red Team Engineer:** Red team engineers focus on the development and maintenance of tools, techniques, and infrastructures used by the red team. They may be involved in developing custom attack tools, automating attack processes, and enhancing the capabilities of the red team to mimic complex adversaries. \
**5.2.1 Junior Red Team Engineer**  \
•	Basic knowledge of network and system internals. \
•	Familiarity with scripting and programming. \
•	Understanding of virtualization, orchestration, and cloud technologies. \
•	Knowledge of web and network penetration testing. \
**5.2.2 Mid-level Red Team Engineer** \
•	Proficiency in programming and scripting. \
•	Deep understanding of Windows, Linux, and macOS internals. \
•	Knowledge of cloud security. \
•	Skills in reverse engineering and malware analysis. \
**5.2.3 Senior Red Team Engineer** \
•	Mastery in tools script development. \
•	Expertise in reverse engineering and vulnerability research. \
•	Advanced knowledge of cloud security. \
•	Advanced skills in malware development and exploit development. \
**5.3 Red Team Lead:** Red team leads oversee the planning, execution, and coordination of red team operations. They are responsible for setting strategic objectives, managing resources, and ensuring alignment of red team activities with organizational goals. Red team leaders often possess a combination of technical expertise and leadership skills. \
**5.3.1. Mid-level Red Team lead** \
•	Proficiency in red team methodologies and tools. \
•	Strong understanding of cybersecurity principles and best practices. \
•	Expertise in planning and executing red team engagements. \
•	Knowledge of threat intelligence and threat actor emulation. \
**5.3.2. Senior Red Team lead** \
•	Mastery in red team engagement. \
•	Skills in risk management. \
•	Expertise in threat intelligence and developing new techniques. \
**5.4 Red Team Consultant:** Red team consultants typically bring a blend of expertise in operations, analysis, engineering, and leadership of red teams to advise organizations on enhancing their security posture. While they may not perform daily operational tasks like operators, engineers, or analysts on the red team, they provide strategic guidance, conduct assessments, and offer recommendations based on their extensive experience and knowledge. \
**5.4.1	Junior Red Team consultant** \
•	Proficiency in network, OS, and cybersecurity. \
•	Familiarity with web and network penetration testing. \
•	Knowledge of scripting. \
•	Basic understanding of threat intelligence. \
•	Ability to analyze logs. \
**5.4.2 Mid-level Red Team Consultant** \
•	Advanced skills in web and network penetration testing. \
•	Proficiency with red team tools and frameworks. \
•	Experience in scripting and automation. \
•	Experience with exploiting vulnerabilities. \
•	Developing mitigation strategies. \
**5.4.3 Senior Red Team Consultant** \
•	Expertise in web and network penetration testing. \
•	Proficiency in reverse engineering, malware analysis, and exploit development. \
•	Experience in conducting red team engagements. \
•	Skills in threat modeling and risk assessment on both technical and business sides. \
•	Developing mitigation plans for new threats.

## 6.Differences between Internal and External Red Teams:

**Internal Red Teamer:** \
•	Scope: Within the organization, checking internal security controls, security policies, and processes, simulating insider threat attacks and APT groups. \
•	Access Level: Knowledge of infrastructure, security systems, and sometimes self-SIEM. \
•	Objectives: Gap analysis, collaboration with blue teams, participation in incident response, threat hunting, and mitigation. \
**External Red Teamer:** \
•	Scope: Organizations and affiliated companies, simulating APT attacks. \
•	Access Level: No knowledge of security equipment and infrastructure, no interaction with internal members. \
•	Objectives: Initial access and information extraction. \
•	Testing Rules: Conducting all tests without any destructive operations on organizational assets, no extraction of customer information and sensitive data like databases.

## 7. How to Become a Red Teamer:

Today, specialization in red teaming has become one of the trends in cybersecurity, and you may be interested in what exactly red teaming is, what it's for, whether you can become a red teamer, what knowledge is required, what skills are needed, and whether there are free resources for self-study or if you must attend specific classes.

## 8.Essential Skills in the Field of Red Teaming:

As a newcomer to this field, you need to acquire the following knowledge to enter the workplace: \
•	Basic knowledge of cybersecurity: Networks, operating systems (Windows, Linux, and Mac). \
•	Penetration testing: Understanding the core concepts and working with tools, ability to conduct penetration testing based on established frameworks like OWASP, which generally has seven stages: information gathering, vulnerability scanning, exploitation, maintaining access, privilege escalation, post-exploitation, reporting. \
•	Automation knowledge: Ability to develop specialized purpose-built tools for a part of the project, requiring at least proficiency in a programming or scripting language (Python, PowerShell, Bash, etc.). \
•	Vulnerability discovery knowledge on known vulnerabilities in applications and networks. \
•	Over time, you should strive to gain more skills. For example, a senior red teamer has the following skills: \
•	Proficiency in Windows Internals, Linux Internals, and Mac OS Internals. \
•	Mastery of MITRE ATT&CK and the ability to plan for simulating techniques. \
•	Ability to develop tools to implement APT group techniques like C2. \
•	Familiarity with the architecture of complex networks, understanding how IDS/IPS, SIEM, EDR, XDR, honeypots, deceptions & decoys, AV, WAF, and firewalls work. \
•	Mastery of MITRE ATT&CK and the ability to plan for simulating techniques. \
•	Ability to understand business needs and provide risk analysis on business. \
•	Personal development and continuous learning ability, keeping oneself updated. \
•	Ability to analyze exploits and malware used by APT groups and the ability to provide reports on how malware and exploits work, what vulnerabilities they exploit, and their primary objectives. \
•	Ability to evaluate control products such as application whitelisting, AV, EDR, to make them fully undetectable and assess whether blue teams can identify them or not. \
•	Management and mentoring skills for newcomers and assisting in problem-solving in various projects. \
•	Ability to present, write reports, hold meetings, and manage sessions. \

## 9. Red team frameworks
[TIBER-EU](https://www.ecb.europa.eu/paym/cyber-resilience/tiber-eu/html/index.en.html) (**Threat Intelligence-based Ethical Red Teaming for the European Union**):
•	Developed by the European Central Bank (ECB), TIBER-EU aims to enhance cyber resilience within the European Union's financial sector. \
•	It focuses on conducting controlled red team exercises informed by threat intelligence to identify and address cybersecurity weaknesses. \
•	TIBER-EU emphasizes collaboration, standardized methodologies, and scenario-based testing to improve cybersecurity posture.

[UK’s CBEST](https://www.crest-approved.org/membership/cbest/) (**UK's CBEST**)

[Hongkong’s iCAST](https://www.pwccn.com/en/risk-assurance/cyber-services/icast/icast-cyber-attack-simulation-hk.pdf) (**Intelligence-led Cyber Attack Simulation Testing**):

•	iCAST (Intelligence-led Cyber Attack Simulation Testing) is a framework developed by the Hong Kong Monetary Authority (HKMA) for assessing and enhancing cybersecurity resilience in the financial sector of Hong Kong. \
•	It employs an intelligence-led approach, incorporating threat intelligence to simulate realistic cyber attack scenarios. \
•	iCAST emphasizes scenario-based testing, collaboration among stakeholders, and provides detailed reports for participating institutions to prioritize remediation efforts and improve their cybersecurity posture.

[Saudi Arabia’s FEER](http://www.sama.gov.sa/en-US/Laws/BankingRules/Financial%20Entities%20Ethical%20Red%20Teaming%20Framework.pdf) (**Financial Entities Ethical Red Teaming**):
•	Saudi Arabia's FEER (Financial Entities Ethical Red Teaming) framework is designed to enhance cybersecurity resilience specifically within the financial sector of Saudi Arabia. \
•	It employs ethical red teaming methodologies to simulate cyber attacks and assess the effectiveness of cybersecurity defenses in financial institutions. \
•	FEER promotes collaboration among financial entities, regulatory authorities, and stakeholders, and encourages continuous improvement of cybersecurity defenses based on insights gained from red team exercises.

[Singapore’s AASE](https://abs.org.sg/docs/library/abs-red-team-adversarial-attack-simulation-exercises-guidelines-v1-06766a69f299c69658b7dff00006ed795.pdf) (**Adversarial Attack Simulation Exercises**):
•	Singapore’s AASE (Adversarial Attack Simulation Exercises) framework employs simulation-based approaches to assess cybersecurity readiness by mimicking real-world cyber attacks. \
•	AASE fosters cross-sector collaboration among government agencies, critical infrastructure operators, and private enterprises to ensure comprehensive coverage and sharing of insights. \
•	The framework emphasizes continuous improvement by providing actionable recommendations based on exercise outcomes to enhance cybersecurity resilience over time.

**NATO’s framework**
•	NATO's red team framework is tailored for military and defense operations, focusing on enhancing operational planning, decision-making, and preparedness. \
•	It conducts strategic assessments by analyzing military plans and exercises, employing diverse expertise to challenge assumptions and uncover vulnerabilities. \
•	The framework aims to improve operational effectiveness by generating insights from simulated adversarial engagements, facilitating learning, adaptation, and refinement of military strategies and tactics.

[MITRE](https://attack.mitre.org/)(**Mitre’s ATT&CK framework**): \
•	The MITRE ATT&CK framework categorizes adversary behaviors into tactics and techniques, aiding in understanding how attackers operate. \
•	It maps adversary techniques to real-world scenarios, allowing organizations to assess their defensive capabilities and prioritize defensive measures. \
•	Continuously updated and community-driven, the framework encourages collaboration among cybersecurity professionals to share knowledge and develop effective defensive strategies against evolving threats.

## 10.MITRE ATT&CK Tactics (SKILLS and TOOLS)
**1.	Reconnaissance** \
•	Skills: OSINT techniques, network scanning, footprinting. \
•	Knowledge: Information gathering methodologies, threat intelligence. \
•	Tools: [Maltego](https://www.maltego.com/), [theHarvester](https://github.com/laramies/theHarvester), [Shodan](https://www.shodan.io/), [Amass](https://github.com/owasp-amass/amass), [Sn1per](https://github.com/1N3/Sn1per), [Recon-ng](https://github.com/lanmaster53/recon-ng), [Nikto](https://github.com/sullo/nikto), [spiderfoot](https://github.com/smicallef/spiderfoot), [Gobuster](https://github.com/OJ/gobuster) \
•	References:["Open Source Intelligence Techniques" by Michael Bazzell](https://www.amazon.com/Open-Source-Intelligence-Techniques-Information/dp/1530508908). \
**2.	Resource Development** \
•	Skills: Exploit development, scripting, programming. \
•	Knowledge: Software vulnerabilities, programming languages (e.g., Python, C/C++). \
•	Tools: [Immunity Debugger](https://www.immunityinc.com/products/debugger/), [IDA Pro](https://hex-rays.com/ida-pro/), [Msfvenom](https://docs.metasploit.com/docs/using-metasploit/basics/how-to-use-msfvenom.html), [GDB](https://www.sourceware.org/gdb/), [chimera](https://github.com/tokyoneon/Chimera), [shellter](https://www.shellterproject.com/), [offensive VBA](https://github.com/S3cur3Th1sSh1t/OffensiveVBA) \
•	References: ["Hacking: The Art of Exploitation" by Jon Erickson](), ["Gray Hat Python" by Justin Seitz]() \
**3.	Initial Access** \
•	Skills: Understanding of common attack vectors (e.g., phishing, exploitation), reconnaissance techniques. \
•	Knowledge: Network architecture, common vulnerabilities, and exposures (CVEs). \
•	Tools: [Metasploit](https://www.metasploit.com), [Cobalt Strike](https://www.cobaltstrike.com/), [SET (Social Engineering Toolkit)](https://github.com/trustedsec/social-engineer-toolkit), [Aircrack-ng](https://github.com/aircrack-ng/aircrack-ng), [Luckystrike](https://github.com/curi0usJack/luckystrike), [Wifi-pumpkin](https://github.com/zackhaikal/WiFi-Pumpkin), [gophish](https://github.com/gophish/gophish), [sqlmap](https://github.com/sqlmapproject/sqlmap), [bash bunny](https://shop.hak5.org/products/bash-bunny), [evilginx2](https://github.com/kgretzky/evilginx2) \
•	References: ["The Hacker Playbook 3" by Peter Kim](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/dp/1980901759), ["Metasploit: The Penetration Tester's Guide" by David Kennedy et al.](https://www.amazon.com/Metasploit-Penetration-Testers-David-Kennedy/dp/159327288X) \
**4.	Execution** \
•	Skills: Ability to execute payloads, shell scripting, understanding of command execution techniques. \
•	Knowledge: Operating system internals, scripting languages (e.g., PowerShell, Python). \
•	Tools: [PowerShell Empire](https://github.com/EmpireProject/Empire), [Metasploit](https://www.metasploit.com), [Cobalt Strike](https://www.cobaltstrike.com/), [macro_pack](https://github.com/sevagas/macro_pack), [donut](https://github.com/TheWover/donut), [Unicorn](https://github.com/trustedsec/unicorn), [responder](https://github.com/SpiderLabs/Responder), [evil-winrm](https://github.com/Hackplayers/evil-winrm), [powersploit](https://github.com/PowerShellMafia/PowerSploit), [Rubeus](https://github.com/GhostPack/Rubeus), [sqlrecon](https://github.com/skahwah/SQLRecon) \
•	References: ["PowerShell for Pentesters" by Nikhil Mittal](https://ine.com/learning/courses/powershell-for-pentesters), ["Violent Python" by TJ O'Connor.](https://www.amazon.com/Violent-Python-Cookbook-Penetration-Engineers/dp/1597499579) \
**5.	Persistence** \
•	Skills: Familiarity with persistence mechanisms (e.g., registry keys, scheduled tasks), privilege escalation techniques. \
•	Knowledge: Windows Registry, Group Policy Objects (GPOs), file system permissions. \
•	Tools: [Covenant](https://github.com/cobbr/Covenant), [Metasploit](https://www.metasploit.com), [Empire](https://github.com/BC-SECURITY/Empire), [impacket](https://github.com/fortra/impacket), [sharpersist](https://github.com/mandiant/SharPersist), [pwncat](https://github.com/calebstewart/pwncat) \
•	References: ["Windows Internals" by Pavel Yosifovich et al.](https://www.amazon.com/Windows-Internals-Part-architecture-management/dp/0735684189) \
**6.	Privilege Escalation:** \
•	Skills: Understanding of privilege escalation techniques, kernel exploitation. \
•	Knowledge: Windows and Linux internals, vulnerability analysis. \
•	Tools: [PowerSploit](https://github.com/PowerShellMafia/PowerSploit), [Mimikatz](https://github.com/gentilkiwi/mimikatz), [Linux Exploit Suggester](https://github.com/The-Z-Labs/linux-exploit-suggester), [Rubeus](https://github.com/GhostPack/Rubeus), [UACme](https://github.com/hfiref0x/UACME), [sharpup](https://github.com/GhostPack/SharpUp), [certify](https://github.com/GhostPack/Certify), [PEASS-ng](https://github.com/carlospolop/PEASS-ng), [sherlock](https://github.com/rasta-mouse/Sherlock), [Watson](https://github.com/rasta-mouse/Watson), [ADFSDump](https://github.com/mandiant/ADFSDump), [Beroot](https://github.com/AlessandroZ/BeRoot), [sweetpotato](https://github.com/CCob/SweetPotato) \
**7.	Defense Evasion:** \
•	Skills: Anti-forensics techniques, obfuscation, bypassing security controls. \
•	Knowledge: Security products (e.g., antivirus, EDR), encryption techniques. \
•	Tools: [Veil](https://github.com/Veil-Framework/Veil), [Shellter](https://www.shellterproject.com/), [Meterpreter](https://github.com/rapid7/meterpreter), [Proxychains](https://github.com/haad/proxychains), [invoke-obfuscation](https://github.com/danielbohannon/Invoke-Obfuscation), [sharpblock](https://github.com/CCob/SharpBlock), [Alcatraz](https://github.com/weak1337/Alcatraz), [mangle](https://github.com/optiv/Mangle), [AMSI fail](https://github.com/Flangvik/AMSI.fail), [scarecrow](https://github.com/optiv/ScareCrow), [moonwalk](https://github.com/mufeedvh/moonwalk) \
**8.	Credential Access:** \
•	Skills: Password cracking, phishing, credential dumping techniques. \
•	Knowledge: Cryptography, authentication protocols, password storage mechanisms. \
•	Tools: [Mimikatz](https://github.com/gentilkiwi/mimikatz), [Hydra](https://github.com/vanhauser-thc/thc-hydra), [John the Ripper](https://github.com/openwall/john), [Hashcat](https://github.com/hashcat/hashcat), [responder](https://github.com/SpiderLabs/Responder), [Lazagne](https://github.com/AlessandroZ/LaZagne), [SCOMDecrypt](https://github.com/nccgroup/SCOMDecrypt), [nanodump](https://github.com/fortra/nanodump), [eviltree](https://github.com/t3l3machus/eviltree), [dploot](https://github.com/zblurx/dploot) \
**9.	Discovery:** \
•	Skills: Active directory, network penetration testing. \
•	Knowledge: Network protocols, enumeration methods. \
•	Tools: [Nmap](https://github.com/nmap/nmap), [Pingcastle](https://github.com/vletoux/pingcastle), [seatbelt](https://github.com/GhostPack/Seatbelt), [ADrecon](https://github.com/sense-of-security/ADRecon), [adidnsdump](https://github.com/dirkjanm/adidnsdump), [bloodhound](https://github.com/BloodHoundAD/BloodHound), [kismet](https://github.com/kismetwireless/kismet) \
**10.Lateral Movement:** \
•	Skills: Exploiting misconfigurations, post-exploitation techniques. \
•	Knowledge: Active Directory, Windows file sharing, SSH. \
•	Tools: [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec), [PowerShell Empire](https://github.com/EmpireProject/Empire), [mimikatz](https://github.com/gentilkiwi/mimikatz), [psexec](https://learn.microsoft.com/en-us/sysinternals/downloads/psexec), [wmiops](https://github.com/RedSiege/WMIOps), [infection monkey](https://github.com/guardicore/monkey), [powerlessshell](https://github.com/Mr-Un1k0d3r/PowerLessShell), [liquidSnake](https://github.com/RiccardoAncarani/LiquidSnake), [ADFSpoof](https://github.com/mandiant/ADFSpoof), [kerbrute](https://github.com/ropnop/kerbrute), [coercer](https://github.com/p0dalirius/Coercer) \
**11.Collection:** \
•	Skills: Data exfiltration methods, network packet analysis. \
•	Knowledge: Data storage formats, network protocols. \
•	Tools: [powersploit](https://github.com/PowerShellMafia/PowerSploit), [powerupsql](https://github.com/NetSPI/PowerUpSQL) \
**12.Command and Control:** \
•	Skills: Setting up covert communication channels, using custom protocols. \
•	Knowledge: Networking fundamentals, encryption techniques. \
•	Tools: [Cobalt Strike](https://www.cobaltstrike.com/), [Metasploit](https://www.metasploit.com), [Covenant](https://github.com/cobbr/Covenant), [pupy](https://github.com/n1nj4sec/pupy), [merlin](https://github.com/Ne0nd0g/merlin), [poshc2](https://github.com/nettitude/PoshC2), [sliver](https://github.com/BishopFox/sliver), [havoc](https://github.com/HavocFramework/Havoc), [brute ratel](https://bruteratel.com/), [nimplant](https://github.com/chvancooten/NimPlant), [hoaxshell](https://github.com/t3l3machus/hoaxshell) \
**13.Exfiltration:** \
•	Skills: Data compression, encryption, covert communication. \
•	Knowledge: Steganography, network traffic analysis. \
•	Tools: [Cryptcat](https://github.com/pprugger/Cryptcat-1.3.0-Win-10-Release), [OpenStego](https://github.com/syvaidya/openstego), [dnscat2](https://github.com/iagox86/dnscat2), [cloakifyfactory](https://github.com/TryCatchHCF/Cloakify), [powershell-rat](https://github.com/Viralmaniar/Powershell-RAT), [pyExfil](https://github.com/ytisf/PyExfil), [GD-Thief](https://github.com/antman1p/GD-Thief) \
**14.Impact:** \
•	Skills: Understanding of destructive techniques (e.g., ransomware), data manipulation. \
•	Knowledge: File system structures, database internals. \
•	Tools: pseudo ransomware, [slowloris](https://github.com/gkbrk/slowloris), [LOIC](https://github.com/NewEraCracker/LOIC) 

## 11. Two open-source tools that are very useful for simulating tactics, techniques, and procedures (TTPs) in the context of MITRE ATT&CK are:
Atomic Red Team: A library of simple, automatable tests that exercise the ATT&CK matrix. These tests are designed to validate detection capabilities of security solutions. Atomic Red Team tests can be executed with minimal dependencies and are compatible with most platforms. \
Caldera: An automated adversary emulation system that performs post-compromise adversarial behavior within a Windows enterprise network. It generates an intrusion kill chain and produces artifacts that allow defenders to evaluate their security operations' capabilities to detect, respond to, and remediate the actions of an adversary. پ
# Commercial tools:

  Cobalt strike \
  Cymulate \
  Brute ratel \
  [C2 Matrix](https://docs.google.com/spreadsheets/d/1b4mUxa6cDQuTV2BPC6aA-GR4zGZi0ooPYtBe4IgPsSc/edit?pli=1#gid=0)

## 12.Does the MITRE ATT&CK framework provide complete coverage?

Generally, the MITRE ATT&CK framework is a community-driven security framework where many security companies report new techniques over time, and the MITRE team adds them after review. However, this process is time-consuming, and MITRE is not updated in real-time. Sources for updates include threat intelligence reports, security researcher articles, post-incident reports released after organizational hacks, blogs, and security researcher tweets, which can serve as sources to expand the coverage breadth of TTPs.

## 13.Red Team Steps

# [Mind V1](https://github.com/soheilsec/Red-Team-Roadmap/blob/main/Red%20Team%20Roadmap%20%5Bv1%5D.xmind)

<div dir="center" markdown="1">
<details markdown="1"> <summary><h3>Red Team Steps Image</h3></summary>

![redteamsteps](https://github.com/soheilsec/Red-Team-Roadmap/assets/46918547/dd5e2900-e2a4-447b-95da-bc028e887ef6)

</details>
</div>

## 14.Red Team salaries

[**Red Team Operator**](https://www.linkedin.com/jobs/search/?currentJobId=3521239439&geoId=103644278&keywords=red%20team%20operator&location=United%20States&origin=JOBS_HOME_SEARCH_BUTTON&refresh=true)

(**Based on the job advertisement on LinkedIn**):

>    Junior: $60,000 - $90,000 \
>    Mid-level: $90,000 - $120,000 \
>    Senior: $120,000 - $150,000+


[**Red Team Engineer**](https://www.linkedin.com/jobs/search/?currentJobId=3826859320&geoId=103644278&keywords=red%20team%20engineer&location=United%20States&origin=JOB_SEARCH_PAGE_SEARCH_BUTTON&refresh=true)

(**Based on the job advertisement on LinkedIn**):

>    Junior: $70,000 - $100,000 \
>    Mid-level: $100,000 - $130,000 \
>    Senior: $130,000 - $160,000+


[**Red Team Lead**](https://www.linkedin.com/jobs/search/?currentJobId=3827197332&geoId=103644278&keywords=red%20team%20lead&location=United%20States&origin=JOB_SEARCH_PAGE_SEARCH_BUTTON&refresh=true) 

>    Mid-level: $120,000 - $150,000 \
>    Senior: $150,000 - $200,000+


[**Red Team Consultant**](https://www.linkedin.com/jobs/search/?currentJobId=3822230937&geoId=103644278&keywords=red%20team%20consultant&location=United%20States&origin=JOB_SEARCH_PAGE_SEARCH_BUTTON&refresh=true)

>    Junior: $70,000 - $100,000 \
>    Mid-level: $100,000 - $130,000 \
>    Senior: $130,000 - $160,000+

## Red Team Interview questions ( Persian )

[RedTeam Interview](https://github.com/soheilsec/RedTeam-Interview)
