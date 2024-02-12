<div align="left" markdown="1">

[**گزارش  مشکلات و ارسال مطلب**](https://github.com/LaneZero/Blue-Team-Interview/issues)&nbsp;&nbsp;&nbsp;[**سوالات تست نفوذ وب**](https://github.com/soheilsec/WAP-Interview)&nbsp;&nbsp;&nbsp;[**سوالات تست نفوذ شبکه**](https://github.com/soheilsec/Network-pentest-Interview)&nbsp;&nbsp;&nbsp;[**سوالات تست نفوذ موبایل**](https://github.com/soheilsec/mobile-App-Pentest-Interview)&nbsp;&nbsp;&nbsp;[**سوالات تست رد تیم**](https://github.com/soheilsec/RedTeam-Interview)

</div>


<div align=center markdown="1">

**نقشه راه RedTeam**

</div>


<div dir="rtl" markdown="1">

***
### فهرست مطالب

- [مقدمه](#%D9%85%D9%82%D8%AF%D9%85%D9%87)
- [سوالات سطح متوسط](#%D8%B3%D9%88%D8%A7%D9%84%D8%A7%D8%AA-%D8%B3%D8%B7%D8%AD-%D9%85%D8%AA%D9%88%D8%B3%D8%B7)
- [سوالات سطح حرفه ای](#%D8%B3%D9%88%D8%A7%D9%84%D8%A7%D8%AA-%D8%B3%D8%B7%D8%AD-%D8%AD%D8%B1%D9%81%D9%87-%D8%A7%DB%8C)

***

</div>


<div dir="rtl" markdown="1">

# 1.ردتیم چه چیزی هست؟
از دید تاریخی ردتیم برگرفته از تمرین‌های ارتش امریکا در طی جنگ سرد بوده است که در واقع ارتش شوروی تیم قرمز و ارتش آمریکا تیم آبی بوده است.اما در دنیای امنیت سایبری ردتیم به معنای شبیه سازی حمله متخاصم یا دشمن می باشد.به صورت کلی اگر بخواهید به عنوان ردتیمر فعالیت کنید بنابر نوع موقعیت شغلی به شما کارهای مختلف محول می‌شود که برای انجام کارها نیازمند داشتن مهارت‌ها در طیف های مختلف هستید.  
مثلا:  
پیدا کردن و بهبود دادن زنجیره اجرایی فایل بدافزار در جهت ارزیابی blue team مثل زنجیره زیر  
url > zip > js > curl > .dll  
پیدا کردن روش‌های جدید و مختلف برای دور زدن مکانیسم‌های امنیتی  
مثل

- Application whitelisting  
- Uac bypass  
- AV evasion  
- EDR evasion  
- و ...

# 2.ردتیم چه چیزی نیست؟

تست نفوذ به خودی خود ردتیم نیست، بلکه یکی از تکنیک های نفوذ می تواند هک وب باشد.

# 3.ردتیم کجاها مورد استفاده قرار می‌گیرد

>     Offensive Security maturity model
![ReadTeam](https://github.com/soheilsec/Red-Team-Roadmap/assets/46918547/13ed8b06-6893-4f7d-bbca-9a4657d6db2d)

سازمان ها دارای بلوغ امنیت تهاجمی مختلفی می‌باشند.در تمام سازمان Vulnerability scanning و Vulnerability Assessment انجام می‌شود.با توجه به بزرگی سازمان‌ها بخش تست نفوذ را دارند یا این بخش را به بیرون out source می کنند یا حتی از برنامه‌های باگ بانتی استفاده می‌کنند.سازمان‌هایی که بلوتیم دارند برای ارزیابی عملکرد این تیم و کشف گپ‌های امنیتی از ردتیم داخلی یا خارجی استفاده می‌کنند.تمرین‌های پرپل تیم یکی از روش برقراری تعادل و کمک به افزایش بهره وری ردتیم و بلوتیم می‌باشد تا به هدف میزان شناسایی را افزایش و false positive را کاهش دست پیدا کنند.شبیه سازی گروه‌های APT در جهت ارزیابی عملکرد تیم های دفاعی بسیار کاربردی می‌باشد.

# 4.گام‌هایی که یک ردتیم داخلی در سازمان باید طی کند:
شناخت شبکه و تجهیزات امنیتی و همچنین محل‌هایی که سنسور وجود دارد یا ندارد!  
آماده‌سازی تست طبق شبکه و تجهیزات امنیتی و پیاده‌سازی آن ها  
کشف گپ های امنیتی و گزارش به بلوتیم  
بررسی مجدد و اجرای تست تا مطمئن شود که گپ‌ها رفع شدند  
بسته بلوغ بلوتیم شبیه سازی تکنیک یا APT گروه باید توسط ردتیم انجام شود  
اگر سازمانی به بلوغ رسیده باشد و حداقل 4 سال بلوتیم داشته باشد تست‌ها باید با سطح بالاتری پیاده‌سازی شوند و تمرکز بیشتر به دور زدن و نگاه به شناسایی و عدم شناسایی بلوتیم می‌باشد همچنین توسعه بدافزار جزو مهم ترین کارها می‌باشد.

# 5.انواع موقعیت‌های شغلی ردتیم و مهارتهای لازم برای هر سطح از موقعیت‌های شغلی

### اپراتور ردتیم Red Team operator:

اپراتورهای تیم قرمز مسئول انجام عملیات امنیتی تهاجمی، شبیه سازی حملات به سیستم های یک سازمان برای شناسایی نقاط ضعف و آسیب پذیری هستند. آنها اغلب آزمایش های نفوذ، توسعه بهره برداری و فعالیت های پس از بهره برداری را برای ارزیابی اثربخشی اقدامات دفاعی انجام می دهند.
</div>

>[!NOTE]
>**5.2.1 Junior Red Team Engineer**  
• Basic knowledge of network and system internals.  
• Familiarity with scripting and programming.  
• Understanding of virtualization, orchestration, and cloud technologies.  
• Knowledge of web and network penetration testing.  
**5.2.2 Mid-level Red Team Engineer**  
• Proficiency in programming and scripting.  
• Deep understanding of Windows, Linux, and macOS internals.  
• Knowledge of cloud security.  
• Skills in reverse engineering and malware analysis.  
**5.2.3 Senior Red Team Engineer**  
• Mastery in tools script development.  
• Expertise in reverse engineering and vulnerability research.  
• Advanced knowledge of cloud security.  
• Advanced skills in malware development and exploit development.

<div dir="rtl" markdown="1">

### رد تیم لید Red Team lead :

ردتیم لید بر برنامه ریزی، اجرا و هماهنگی عملیات تیم قرمز نظارت می کنند. آنها مسئول تعیین اهداف استراتژیک، مدیریت منابع و اطمینان از همسویی فعالیت های تیم قرمز با اهداف سازمانی هستند. رهبران تیم قرمز اغلب ترکیبی از تخصص فنی و مهارت های رهبری دارند.

</div>

>[!NOTE]
>**5.3.1. Mid-level Red Team lead**  
>• Proficiency in red team methodologies and tools.  
>• Strong understanding of cybersecurity principles and best practices.  
>• Expertise in planning and executing red team engagements.  
>• Knowledge of threat intelligence and threat actor emulation.  
>**5.3.2. Senior Red Team lead**  
>• Mastery in red team engagement.  
>• Skills in risk management.  
>• Expertise in threat intelligence and developing new techniques.

<div dir="rtl" markdown="1">

### مشاور ردتیم Red Team Consultant

مشاور تیم قرمز معمولاً ترکیبی از تخصص در عملیات، تجزیه و تحلیل، مهندسی و رهبری تیم قرمز را به ارمغان می‌آورد تا به سازمان‌ها در مورد ارتقای وضعیت امنیتی خود توصیه کند. در حالی که آنها ممکن است وظایف عملیاتی روزانه مانند اپراتور، مهندس یا تحلیلگر تیم قرمز را انجام ندهند، آنها راهنمایی های استراتژیک ارائه می دهند، ارزیابی ها را انجام می دهند و توصیه هایی را بر اساس تجربه و دانش گسترده خود ارائه می دهند.

</div>

>[!NOTE]
>**5.4.1 Junior Red Team consultant**  
>• Proficiency in network, OS, and cybersecurity.  
>• Familiarity with web and network penetration testing.  
>• Knowledge of scripting.  
>• Basic understanding of threat intelligence.  
>• Ability to analyze logs.  
>**5.4.2 Mid-level Red Team Consultant**  
>• Advanced skills in web and network penetration testing.  
>• Proficiency with red team tools and frameworks.  
>• Experience in scripting and automation.  
>• Experience with exploiting vulnerabilities.  
>• Developing mitigation strategies.  
>**5.4.3 Senior Red Team Consultant**  
>• Expertise in web and network penetration testing.  
>• Proficiency in reverse engineering, malware analysis, and exploit development.  
>• Experience in conducting red team engagements.  
>• Skills in threat modeling and risk assessment on both technical and business sides.  
>• Developing mitigation plans for new threats.

<div dir="rtl" markdown="1">

# 6.تفاوت ردتیم داخلی و خارجی

ردتیمر داخلی Internal Red Teamer دامنه کاری: داخل سازمان، چک کردن کنترل امنیتی داخلی، سیاست های امنیتی و فرآیندهای امنیتی، شبیه سازی حملات تهدید داخلی و گروه های APT میزان دسترسی: دانش روی زیرساخت، سیستم های امنیتی و در بعضی موارد خود SIEM اهداف: gap analysis، همکاری با بلوتیم، همکاری در incident response, threat hunting و mitigation

ردتیمر خارجی External Red Teamer دامنه کاری: سازمان و شرکت های وابسته، شبیه سازی حملات APT میزان دسترسی: هیچ دانشی از تجهیزات امنیتی و زیرساختی ندارد و همچنین هیچ ارتباطی با اعضای داخلی ندارد. اهداف: دسترسی اولیه و رسیدن به استخراج اطلاعات قوانین تست: انجام تمام تست ها بدون هیچ گونه عملیات تخریب در دارایی های سازمان، عدم استخراج اطلاعات مشتریان و اطلاعات حساس مثل دیتابیس ها

# 7.چگونه یک ردتیمر بشوم؟

امروزه تخصص ردتیم یکی از ترندهای امنیت سایبری تبدیل شده است به گونه‌ای که تاثیر آن را در موقعیت‌های شغلی در سرتاسر جهان می‌بینید و شاید علاقه مند شده باشید که واقعا این ردتیم چیست؟ چه بدردی می‌خورد آیا من می‌تونم ردتیمر بشوم چه دانشی نیاز دارد چه مهارت‌هایی نیاز دارد و آیا منابع رایگان وجود دارد تا من بتوانم به صورت خودخوان بخوانم یا حتما باید در کلاس خاصی شرکت کنم؟\

# 8.کلیه مهارت های فیلد ردتیم

به عنوان یک شخص تازه وارد در این حوزه شما باید دانش های زیر را کسب کنید تا وارد محل کار شوید:

1.  دانش ابتدایی روی امنیت سایبری : شبکه، سیستم عامل‌ها(ویندوز،لینوکس و مک).
2.  تست نفوذ دانش مفاهیم اصلی و کار با ابزارها و توانایی انجام تست نفوذ بر اساس فریمورک مطرح مثل owasp که به صورت کلی 7 مرحله دارد . information gathering, vul scanning, exploiting, maintain access , privilege escalation, post exploitation, reporting
3.  دانش اتومات سازی یا ساخت ابزار خاص منظوره برای بخشی از پروژه که حداقل نیاز دارید یک زبان برنامه نویسی یا اسکریپت نویسی بلد باشید ( python, powershell, bash,… )
4.  دانش بر کشف آسیب پذیری‌های شناخته شده روی برنامه ها و شبکه شما باید به مرور سعی کنید به مهارت بیشتری دست پیدا کنید به عنوان مثال یک ردتیمر سنیور مهارت‌های زیر را دارد:
5.  تسلط به Windows Internals, Linux Internals, Mac os Internals
6.  مسلط به تاکتیک‌های مایتراتک و توانایی شبیه سازی تکنیک‌های جدید APT گروه‌ها
7.  توانایی توسعه ابزارهایی در جهت پیاده‌سازی تکنیک‌های APT گروه‌ها مثل C2
8.  آشنایی با معماری شبکه‌های پیچیده نحوه کار کرد IDS/IPS, SIEM, EDR,XDR, honeypot, deception& decoy, AV, WAF, firewall
9.  تسلط بر روی مایتراتک و توانایی برنامه ریزی برای شبیه سازی تکنیکها
10.  توانایی شناخت بیزینس و ارایه تحلیل ریسک‌ها موجود در بیزینس
11.  توانایی توسعه فردی و یادگیری به صورت دائمی و آپدیت کردن خودش
12.  توانایی تحلیل اکسپلویت‌ها و بدافزارهایی که گروه‌های APT از آن‌ها استفاده کردند و قابلیت ارائه گزارش مبنی بر اینکه نحوه کارکرد بدافزار واکسپلویت چیز از چه آسیب پذیری استفاده می‌کند و هدف اصلی آن ها چیست
13.  توانایی در ارزیابی محصولات کنترلی مثل application whitelisting, AV, EDR در جهت FUD کردن تا لاگی از این تجهیزات نباشد و ارزیابی کند از حرکات بعدی یا artifact های موجود در سیستم یا شبکه تیم آبی توانایی شناسایی آن را دارند یا نه
14.  توانایی مدیریت و منتور بودن نیروهای تازه‌کار و کمک در پروژه‌های مختلف حل مشکلات
15.  توانایی ارائه دادن گزارش نوشتن برقراری جلسه و مدیریت جلسات

# 9.فریمورک‌های مطرح ردتیم

</div>

[TIBER-EU](https://www.ecb.europa.eu/paym/cyber-resilience/tiber-eu/html/index.en.html) (**Threat Intelligence-based Ethical Red Teaming for the European Union**):  
• Developed by the European Central Bank (ECB), TIBER-EU aims to enhance cyber resilience within the European Union's financial sector.  
• It focuses on conducting controlled red team exercises informed by threat intelligence to identify and address cybersecurity weaknesses.  
• TIBER-EU emphasizes collaboration, standardized methodologies, and scenario-based testing to improve cybersecurity posture.

[UK’s CBEST](https://www.crest-approved.org/membership/cbest/) (**UK's CBEST**)

---

[Hongkong’s iCAST](https://www.pwccn.com/en/risk-assurance/cyber-services/icast/icast-cyber-attack-simulation-hk.pdf) (**Intelligence-led Cyber Attack Simulation Testing**):

• iCAST (Intelligence-led Cyber Attack Simulation Testing) is a framework developed by the Hong Kong Monetary Authority (HKMA) for assessing and enhancing cybersecurity resilience in the financial sector of Hong Kong.  
• It employs an intelligence-led approach, incorporating threat intelligence to simulate realistic cyber attack scenarios.  
• iCAST emphasizes scenario-based testing, collaboration among stakeholders, and provides detailed reports for participating institutions to prioritize remediation efforts and improve their cybersecurity posture.

---

[Saudi Arabia’s FEER](http://www.sama.gov.sa/en-US/Laws/BankingRules/Financial%20Entities%20Ethical%20Red%20Teaming%20Framework.pdf) (**Financial Entities Ethical Red Teaming**): • Saudi Arabia's FEER (Financial Entities Ethical Red Teaming) framework is designed to enhance cybersecurity resilience specifically within the financial sector of Saudi Arabia.  
• It employs ethical red teaming methodologies to simulate cyber attacks and assess the effectiveness of cybersecurity defenses in financial institutions.  
• FEER promotes collaboration among financial entities, regulatory authorities, and stakeholders, and encourages continuous improvement of cybersecurity defenses based on insights gained from red team exercises.

---

[Singapore’s AASE](https://abs.org.sg/docs/library/abs-red-team-adversarial-attack-simulation-exercises-guidelines-v1-06766a69f299c69658b7dff00006ed795.pdf) (**Adversarial Attack Simulation Exercises**): • Singapore’s AASE (Adversarial Attack Simulation Exercises) framework employs simulation-based approaches to assess cybersecurity readiness by mimicking real-world cyber attacks.  
• AASE fosters cross-sector collaboration among government agencies, critical infrastructure operators, and private enterprises to ensure comprehensive coverage and sharing of insights.  
• The framework emphasizes continuous improvement by providing actionable recommendations based on exercise outcomes to enhance cybersecurity resilience over time.

---

**NATO’s framework** • NATO's red team framework is tailored for military and defense operations, focusing on enhancing operational planning, decision-making, and preparedness.  
• It conducts strategic assessments by analyzing military plans and exercises, employing diverse expertise to challenge assumptions and uncover vulnerabilities.  
• The framework aims to improve operational effectiveness by generating insights from simulated adversarial engagements, facilitating learning, adaptation, and refinement of military strategies and tactics.

---

[MITRE](https://attack.mitre.org/)(**Mitre’s ATT&CK framework**):  
• The MITRE ATT&CK framework categorizes adversary behaviors into tactics and techniques, aiding in understanding how attackers operate.  
• It maps adversary techniques to real-world scenarios, allowing organizations to assess their defensive capabilities and prioritize defensive measures.  
• Continuously updated and community-driven, the framework encourages collaboration among cybersecurity professionals to share knowledge and develop effective defensive strategies against evolving threats.


<div dir="rtl" markdown="1">

# 10.بر اساس مایتراتک برای شبیه سازی هر تاکتیک چه مهارت‌هایی لازم است

</div>

**1. Reconnaissance**  
• Skills: OSINT techniques, network scanning, footprinting.  
• Knowledge: Information gathering methodologies, threat intelligence.  
• Tools: [Maltego](https://www.maltego.com/), [theHarvester](https://github.com/laramies/theHarvester), [Shodan](https://www.shodan.io/), [Amass](https://github.com/owasp-amass/amass), [Sn1per](https://github.com/1N3/Sn1per), [Recon-ng](https://github.com/lanmaster53/recon-ng), [Nikto](https://github.com/sullo/nikto), [spiderfoot](https://github.com/smicallef/spiderfoot), [Gobuster](https://github.com/OJ/gobuster)  
• References:["Open Source Intelligence Techniques" by Michael Bazzell](https://www.amazon.com/Open-Source-Intelligence-Techniques-Information/dp/1530508908). 

---
 
**2. Resource Development**  
• Skills: Exploit development, scripting, programming.  
• Knowledge: Software vulnerabilities, programming languages (e.g., Python, C/C++).  
• Tools: [Immunity Debugger](https://www.immunityinc.com/products/debugger/), [IDA Pro](https://hex-rays.com/ida-pro/), [Msfvenom](https://docs.metasploit.com/docs/using-metasploit/basics/how-to-use-msfvenom.html), [GDB](https://www.sourceware.org/gdb/), [chimera](https://github.com/tokyoneon/Chimera), [shellter](https://www.shellterproject.com/), [offensive VBA](https://github.com/S3cur3Th1sSh1t/OffensiveVBA)  
• References: ["Hacking: The Art of Exploitation" by Jon Erickson](https://github.com/soheilsec/Red-Team-Roadmap/blob/main), ["Gray Hat Python" by Justin Seitz](https://github.com/soheilsec/Red-Team-Roadmap/blob/main)  

---

**3. Initial Access**  
• Skills: Understanding of common attack vectors (e.g., phishing, exploitation), reconnaissance techniques.  
• Knowledge: Network architecture, common vulnerabilities, and exposures (CVEs).  
• Tools: [Metasploit](https://www.metasploit.com), [Cobalt Strike](https://www.cobaltstrike.com/), [SET (Social Engineering Toolkit)](https://github.com/trustedsec/social-engineer-toolkit), [Aircrack-ng](https://github.com/aircrack-ng/aircrack-ng), [Luckystrike](https://github.com/curi0usJack/luckystrike), [Wifi-pumpkin](https://github.com/zackhaikal/WiFi-Pumpkin), [gophish](https://github.com/gophish/gophish), [sqlmap](https://github.com/sqlmapproject/sqlmap), [bash bunny](https://shop.hak5.org/products/bash-bunny), [evilginx2](https://github.com/kgretzky/evilginx2)  
• References: ["The Hacker Playbook 3" by Peter Kim](https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/dp/1980901759), ["Metasploit: The Penetration Tester's Guide" by David Kennedy et al.](https://www.amazon.com/Metasploit-Penetration-Testers-David-Kennedy/dp/159327288X)  

---

**4. Execution**  
• Skills: Ability to execute payloads, shell scripting, understanding of command execution techniques.  
• Knowledge: Operating system internals, scripting languages (e.g., PowerShell, Python).  
• Tools: [PowerShell Empire](https://github.com/EmpireProject/Empire), [Metasploit](https://www.metasploit.com), [Cobalt Strike](https://www.cobaltstrike.com/), [macro_pack](https://github.com/sevagas/macro_pack), [donut](https://github.com/TheWover/donut), [Unicorn](https://github.com/trustedsec/unicorn), [responder](https://github.com/SpiderLabs/Responder), [evil-winrm](https://github.com/Hackplayers/evil-winrm), [powersploit](https://github.com/PowerShellMafia/PowerSploit), [Rubeus](https://github.com/GhostPack/Rubeus), [sqlrecon](https://github.com/skahwah/SQLRecon)  
• References: ["PowerShell for Pentesters" by Nikhil Mittal](https://ine.com/learning/courses/powershell-for-pentesters), ["Violent Python" by TJ O'Connor.](https://www.amazon.com/Violent-Python-Cookbook-Penetration-Engineers/dp/1597499579)  

---

**5. Persistence**  
• Skills: Familiarity with persistence mechanisms (e.g., registry keys, scheduled tasks), privilege escalation techniques.  
• Knowledge: Windows Registry, Group Policy Objects (GPOs), file system permissions.  
• Tools: [Covenant](https://github.com/cobbr/Covenant), [Metasploit](https://www.metasploit.com), [Empire](https://github.com/BC-SECURITY/Empire), [impacket](https://github.com/fortra/impacket), [sharpersist](https://github.com/mandiant/SharPersist), [pwncat](https://github.com/calebstewart/pwncat)  
• References: ["Windows Internals" by Pavel Yosifovich et al.](https://www.amazon.com/Windows-Internals-Part-architecture-management/dp/0735684189)  

---

**6. Privilege Escalation:**  
• Skills: Understanding of privilege escalation techniques, kernel exploitation.  
• Knowledge: Windows and Linux internals, vulnerability analysis.  
• Tools: [PowerSploit](https://github.com/PowerShellMafia/PowerSploit), [Mimikatz](https://github.com/gentilkiwi/mimikatz), [Linux Exploit Suggester](https://github.com/The-Z-Labs/linux-exploit-suggester), [Rubeus](https://github.com/GhostPack/Rubeus), [UACme](https://github.com/hfiref0x/UACME), [sharpup](https://github.com/GhostPack/SharpUp), [certify](https://github.com/GhostPack/Certify), [PEASS-ng](https://github.com/carlospolop/PEASS-ng), [sherlock](https://github.com/rasta-mouse/Sherlock), [Watson](https://github.com/rasta-mouse/Watson), [ADFSDump](https://github.com/mandiant/ADFSDump), [Beroot](https://github.com/AlessandroZ/BeRoot), [sweetpotato](https://github.com/CCob/SweetPotato)  

---

**7. Defense Evasion:**  
• Skills: Anti-forensics techniques, obfuscation, bypassing security controls.  
• Knowledge: Security products (e.g., antivirus, EDR), encryption techniques.  
• Tools: [Veil](https://github.com/Veil-Framework/Veil), [Shellter](https://www.shellterproject.com/), [Meterpreter](https://github.com/rapid7/meterpreter), [Proxychains](https://github.com/haad/proxychains), [invoke-obfuscation](https://github.com/danielbohannon/Invoke-Obfuscation), [sharpblock](https://github.com/CCob/SharpBlock), [Alcatraz](https://github.com/weak1337/Alcatraz), [mangle](https://github.com/optiv/Mangle), [AMSI fail](https://github.com/Flangvik/AMSI.fail), [scarecrow](https://github.com/optiv/ScareCrow), [moonwalk](https://github.com/mufeedvh/moonwalk)  

---

**8. Credential Access:**  
• Skills: Password cracking, phishing, credential dumping techniques.  
• Knowledge: Cryptography, authentication protocols, password storage mechanisms.  
• Tools: [Mimikatz](https://github.com/gentilkiwi/mimikatz), [Hydra](https://github.com/vanhauser-thc/thc-hydra), [John the Ripper](https://github.com/openwall/john), [Hashcat](https://github.com/hashcat/hashcat), [responder](https://github.com/SpiderLabs/Responder), [Lazagne](https://github.com/AlessandroZ/LaZagne), [SCOMDecrypt](https://github.com/nccgroup/SCOMDecrypt), [nanodump](https://github.com/fortra/nanodump), [eviltree](https://github.com/t3l3machus/eviltree), [dploot](https://github.com/zblurx/dploot)  

---

**9. Discovery:**  
• Skills: Active directory, network penetration testing.  
• Knowledge: Network protocols, enumeration methods.  
• Tools: [Nmap](https://github.com/nmap/nmap), [Pingcastle](https://github.com/vletoux/pingcastle), [seatbelt](https://github.com/GhostPack/Seatbelt), [ADrecon](https://github.com/sense-of-security/ADRecon), [adidnsdump](https://github.com/dirkjanm/adidnsdump), [bloodhound](https://github.com/BloodHoundAD/BloodHound), [kismet](https://github.com/kismetwireless/kismet)  

---

**10.Lateral Movement:**  
• Skills: Exploiting misconfigurations, post-exploitation techniques.  
• Knowledge: Active Directory, Windows file sharing, SSH.  
• Tools: [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec), [PowerShell Empire](https://github.com/EmpireProject/Empire), [mimikatz](https://github.com/gentilkiwi/mimikatz), [psexec](https://learn.microsoft.com/en-us/sysinternals/downloads/psexec), [wmiops](https://github.com/RedSiege/WMIOps), [infection monkey](https://github.com/guardicore/monkey), [powerlessshell](https://github.com/Mr-Un1k0d3r/PowerLessShell), [liquidSnake](https://github.com/RiccardoAncarani/LiquidSnake), [ADFSpoof](https://github.com/mandiant/ADFSpoof), [kerbrute](https://github.com/ropnop/kerbrute), [coercer](https://github.com/p0dalirius/Coercer)  

---

**11.Collection:**  
• Skills: Data exfiltration methods, network packet analysis.  
• Knowledge: Data storage formats, network protocols.  
• Tools: [powersploit](https://github.com/PowerShellMafia/PowerSploit), [powerupsql](https://github.com/NetSPI/PowerUpSQL)  

---

**12.Command and Control:**  
• Skills: Setting up covert communication channels, using custom protocols.  
• Knowledge: Networking fundamentals, encryption techniques.  
• Tools: [Cobalt Strike](https://www.cobaltstrike.com/), [Metasploit](https://www.metasploit.com), [Covenant](https://github.com/cobbr/Covenant), [pupy](https://github.com/n1nj4sec/pupy), [merlin](https://github.com/Ne0nd0g/merlin), [poshc2](https://github.com/nettitude/PoshC2), [sliver](https://github.com/BishopFox/sliver), [havoc](https://github.com/HavocFramework/Havoc), [brute ratel](https://bruteratel.com/), [nimplant](https://github.com/chvancooten/NimPlant), [hoaxshell](https://github.com/t3l3machus/hoaxshell)  

---

**13.Exfiltration:**  
• Skills: Data compression, encryption, covert communication.  
• Knowledge: Steganography, network traffic analysis.  
• Tools: [Cryptcat](https://github.com/pprugger/Cryptcat-1.3.0-Win-10-Release), [OpenStego](https://github.com/syvaidya/openstego), [dnscat2](https://github.com/iagox86/dnscat2), [cloakifyfactory](https://github.com/TryCatchHCF/Cloakify), [powershell-rat](https://github.com/Viralmaniar/Powershell-RAT), [pyExfil](https://github.com/ytisf/PyExfil), [GD-Thief](https://github.com/antman1p/GD-Thief)  

---

**14.Impact:**  
• Skills: Understanding of destructive techniques (e.g., ransomware), data manipulation.  
• Knowledge: File system structures, database internals.  
• Tools: pseudo ransomware, [slowloris](https://github.com/gkbrk/slowloris), [LOIC](https://github.com/NewEraCracker/LOIC)


<div dir="rtl" markdown="1">

# 11.شبیه سازهای TTP مایتراتک

دو از ابزارهای متن باز که در شبیه سازی تاکتیک تکنیک و روشها به بسیار کاربردی هستند:

> Caldera, atomic red team

همچنین ابزارهای تجاری مثل

- Cobalt strike
- Cymulate
- Brute ratel
- و...

# [c2 Matrix](https://docs.google.com/spreadsheets/d/1b4mUxa6cDQuTV2BPC6aA-GR4zGZi0ooPYtBe4IgPsSc/edit?pli=1#gid=0)


# 12.آیا فریمورک مایتراتک پوشش کامل می‌دهد ؟

به صورت کلی مایتراتک یک فریمورک ما بین کامیونیتی امنیت است که بسیاری از شرکتهای امنیتی در طول سال وقتی به تکنیک‌های جدیدی دست پیدا کنند به مایتر گزارش می‌کنند و تیم مایتر پس از بررسی اضافه می‌کند لذا این فرآیند زمان بر است و مایتر در لحظه آپدیت نیست. منابع برای آپدیت گزارش‌های هوش تهدید، مقالات محققین امنیتی، گزارش‌های IR که پس هک سازمان‌ها منتشر می شود، بلاگ‌ها و تویتتر محقیقن امنیتی می تواند منابعی برای افزایش گستره پوشش TTP باشد.


# 13.گام های کلی که برای کار در فیلد ردتیم باید طی شود:

# [Mind V1](https://github.com/soheilsec/Red-Team-Roadmap/blob/main/Red%20Team%20Roadmap%20%5Bv1%5D.xmind)


</div>

# 14.بازار کار ردتیم متوسط حقوق پوزیشن ردتیم در خارج از ایران

با توجه به اینکه تو ایران هیچ آمار دقیقی از حقوق‌ها نیست. صرفا حقوق‌های ردتیم در آمریکا قرار داده شده است.

[**Red Team Operator**](https://www.linkedin.com/jobs/search/?currentJobId=3521239439&geoId=103644278&keywords=red%20team%20operator&location=United%20States&origin=JOBS_HOME_SEARCH_BUTTON&refresh=true)

(**Based on the job advertisement on LinkedIn**):

> Junior: $60,000 - $90,000  
> Mid-level: $90,000 - $120,000  
> Senior: $120,000 - $150,000+

[**Red Team Engineer**](https://www.linkedin.com/jobs/search/?currentJobId=3826859320&geoId=103644278&keywords=red%20team%20engineer&location=United%20States&origin=JOB_SEARCH_PAGE_SEARCH_BUTTON&refresh=true)

(**Based on the job advertisement on LinkedIn**):

> Junior: $70,000 - $100,000  
> Mid-level: $100,000 - $130,000  
> Senior: $130,000 - $160,000+

[**Red Team Lead**](https://www.linkedin.com/jobs/search/?currentJobId=3827197332&geoId=103644278&keywords=red%20team%20lead&location=United%20States&origin=JOB_SEARCH_PAGE_SEARCH_BUTTON&refresh=true)

> Mid-level: $120,000 - $150,000  
> Senior: $150,000 - $200,000+

[**Red Team Consultant**](https://www.linkedin.com/jobs/search/?currentJobId=3822230937&geoId=103644278&keywords=red%20team%20consultant&location=United%20States&origin=JOB_SEARCH_PAGE_SEARCH_BUTTON&refresh=true)

> Junior: $70,000 - $100,000  
> Mid-level: $100,000 - $130,000  
> Senior: $130,000 - $160,000+

# 15.نمونه سوالات ردتیم

[RedTeam Interview](https://github.com/soheilsec/RedTeam-Interview)