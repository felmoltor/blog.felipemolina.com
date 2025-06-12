---
layout: page
title: Public Talks
icon: fa-solid fa-microphone
order: 10
---

* **Man in the Middle, but for Mails (MaitM)** - 20th Sep 2024
  * **Where**: [Brucon 0x10](https://www.brucon.org/2024/)
  * **Related Blog Post**: [https://sensepost.com/blog/2024/mail-in-the-middle-a-tool-to-automate-spear-phishing-campaigns/](https://sensepost.com/blog/2024/mail-in-the-middle-a-tool-to-automate-spear-phishing-campaigns/)
  * **Tool**: [https://github.com/sensepost/mail-in-the-middle](https://github.com/sensepost/mail-in-the-middle)
  * **Slides**: [Mail_in_the_Middle-BruCON.pdf]( /assets/presentations/2024/brucon/Mail_in_the_Middle-BruCON.pdf )
  * **Summary**: Mistyped domains often take some convincing to be effective in phishing attacks. After finding the perfect typo, the real work starts setting up the perfect lure. Instead of this, an often-forgotten attack vector exists where potential victims already make these typo's when sending email and or configuring systems, letting go of plenty useful information while at it.
  In this talk we will explore this attack vector, ultimately setting ourselves up for a Mail-in-the-middle (MaiTM) attack to steal confidential information, login using password resets, embed tracking pixels and even deliver malware. Configuring this can still take some work and requires quick timing, so to help with that we have developed a toolkit that we will demonstrate during this talk. Finally, considering the impact of these attacks we will dive into some detection and prevention strategies for this attack while also releasing some new proof of concept tooling to aid organizations in defending against it
  * **Recording**: (https://www.youtube.com/watch?v=D37EQuX297g&ab_channel=BruCONSecurityConference)
{%  include embed/youtube.html id='D37EQuX297g' %}
* **Dress Code - Analysis of the Current Status of CSP** - 25th Oct 2023
  * **Where**: [Sector 2023](https://www.blackhat.com/sector/2023/)
  * **Tool**: [https://github.com/sensepost/dresscode](https://github.com/sensepost/dresscode)
  * **Link**: [https://www.blackhat.com/sector/2023/briefings/schedule/index.html#dress-code---analysis-of-the-current-status-of-the-content-security-policy-34050](https://www.blackhat.com/sector/2023/briefings/schedule/index.html#dress-code---analysis-of-the-current-status-of-the-content-security-policy-34050)
  * **Slides**: [Sector-23-Molina-Dress-Code.pdf]( /assets/presentations/2023/sector/Sector-23-Molina-Dress-Code.pdf )
  * **Summary**: The top one million most popular sites were scanned and their CSP related headers were stored. The values of the CSP headers were analysed to answer several questions. How popular is this security measure nowadays? What are common pitfalls and misconfigurations within CSP headers. How often do sites enable reporting of violations to take a more proactive approach? Do sites blindly trust third parties such as content delivery networks and how can this trust be abused.
  This talk will cover the results of the analysis against real world data and answer the previous questions. Additionally, it will present practical eighth novel exploitation examples and provide with effective hardening and mitigation to the detected weaknesses.
* **Dress Code - Analysis of the Current Status of CSP** - 20th Aug 2023
  * **Where**: [Defcon 31 - AppsSec Village](https://www.appsecvillage.com/events/dc-2023)
  * **Tool**: [https://github.com/sensepost/dresscode](https://github.com/sensepost/dresscode)
  * **Slides**: [Sector-23-Molina-Dress-Code.pdf]( /assets/presentations/2023/sector/Sector-23-Molina-Dress-Code.pdf )
  * **Recording**: (https://www.youtube.com/watch?v=9xTw_SKed-Q&ab_channel=AppSecVillage)
{%  include embed/youtube.html id='9xTw_SKed-Q' %}
* **Breaking the Security of Location-enabled Apps** - 17th Sep 2021
  * **Where**: [BSides Copenhagen 2021](https://video.bsideskbh.dk/2021/)
  * **Slides**: [Breaking-the-Security-of-Location-enabled-Apps.pdf]( /assets/presentations/2021/bsides/Breaking-the-Security-of-Location-enabled-Apps.pdf )
  * **Summary**: Using various mobile applications' Location Based Services (LBS), we were able to precisely geolocate users of many of these platforms. In performing a broad-based study on nearly twenty applications, a vulnerability class that is nearing a 10-year anniversary more recently surfaced in Telegram, for which we were also able to develop a partial bypass to still locate users with good enough accuracy. In this talk, we will discuss how to exploit these LBS vulnerabilities while automating parts of them, as well as how to effectively defend against them.
  As penetration testers, we have analyzed many LBS-enabled mobile applications, ranging from social networks, mobile games &payments as well as banking applications. These services, while seemingly harmless, are often used without considering their privacy impact. Since 2013, well-known applications such as Tinder, Grindr, Strava and others, have suffered from LBS-related vulnerabilities and privacy concerns.
  * **Recording**: 
{%  include embed/vimeo.html id='621385238' %}
