![alt tag](https://user-images.githubusercontent.com/24201238/29351849-9c3087b4-82b8-11e7-8fed-350e3b8b4945.png)

# Panopticon Project

add notes to each section
change how campaign works
working through https://oasis-open.github.io/cti-documentation/stix/examples
killchain might get added

## Examplus Hackerus
* Label - Advanced Persistent Threat (APT)

(Note that over time our APT has become more sophsticated, attribution has come more specific and their malware has evolved. Their general modus operandi has changed little over two years though.)

## Aliases
* APT 2000
* Those Bad People

## Overview
APT2000 is a single organization of operators that has conducted a cyber espionage campaign against a broad range of victims since at least 2018.

## Campaign or year
A grouping of adversarial behaviors that describes a set of malicious activities or attacks that occur over a period of time against a specific set of targets. Each Campaign should have a name or description and be associated with the below date range. Leave blank if there is no discernable campaign
* Campaign
* About - [Targetting infrastructure in South East Asia](URL to source)
* Active from - 01 March 2018
* Active to - 30 September 2018

### Attributes
* Resource level - Government
* Sophistication - Expert
* Primary activities - Attempting to compromise industrial control systems, intellectual property theft

### Attack Pattern
A type of Tactics, Techniques, and Procedures (TTP) that describes ways threat actors attempt to compromise targets.
* [Phishing](URL to source)
* [Credential harvesting](URL to source)
* [DDoS] (URL to source)
* [Social engineering] (URL to source)
* Malware - Extra Miffins

### Vulnerabilities
A mistake in software that can be directly used by a hacker to gain access to a system or network. Link to a writeup in the exploit repo where possible (example, CVEs).
* [CVE-2018-0158](URL to outline of how CVE is exploited) used by Extra Muffins

### Course of Action 
An action taken to either prevent an attack or respond to an attack.
* Apply patch 1234 to ICS systems to patch CVE-2018-0158

### Identity
Individuals, organizations, or groups, as well as classes of individuals, organizations, or groups.

#### Individuals 
* [Joanna Doe](URL to source)
* [Another Person](URL to source)

#### Affiliated organisations
* [The People's Republic of Lorem Ipsum](URL to source)
* [Any Other Groups](URL to source)

#### Affiliated groups
* [That Other APT](URL to source)
* [Yet Another APT](URL to source)

### Intrusion Set
A grouped set of adversarial behaviors and resources with common properties believed to be orchestrated by a single threat actor.
      
#### Malware
A type of TTP, also known as malicious code and malicious software, used to compromise the confidentiality, integrity, or availability of a victim’s data or system.
* Names - Extra Muffins, any other name the malware goes by
* Functionality - Backdoor, keylogger, anything else it can do
* MD5 - 001dd76872d80801692ff942308c64e6
* Notes - part of the Cake family of malware previously attributed to Lorem Ipsum

#### Website 
* About - Malicious site hosting downloader
* URL - hxxp://x4z9arb[.]cn/4712/
* IP - 562.115.0.0/80
* Valid from - 01 August 2018 
* Valid to - 01 September 2018

#### Command and Control Server
* About - used by Extra Muffins malware to receive commands from and exfiltrate data to
* URL - hxxp://sd35f456[.]cn/2134/
* IP - 223.166.0.0/15
* Valid from - 01 August 2018
* Valid to - 01 September 2018

#### Documents
* About - Word document attached to spearphishing emails, generates a popup that asks for credentials to connect to C&C server hxxp://sd35f456[.]cn/2134/
* SHA265 - d393349a4ad00902e3d415b622cf27987a0170a786ca3a1f991a521bff645318

#### Tools
* Name - pwdump7, any other name known by
* Functionality - Dumps password hashes from the Windows registry
* URL - http://www.tarasco.org/security/pwdump_7/

### Report 
Collections of threat intelligence focused on one or more topics, such as a description of a threat actor, malware, or attack technique, including contextual details.
* [Examinging Examplus Hackerus](URL to pdf/blog post etc)
* Description - Since 2018, RandomAV Firm has investigated computer security breaches at hundreds of organizations. The details we have analyzed during hundreds of investigations convince us that a specific group is based primarily in Lorem Ipsum and that the Lorem Ipsum Government is aware of them. We refer to this group as APT2000, a single organization of operators that has conducted a cyber espionage campaign against a broad range of victims since at least 2018. Our analysis has led us to conclude that APT2000 is able to wage such a long-running and extensive cyber espionage campaign in large part because it receives direct government support. 

## Campaign or year
A grouping of adversarial behaviors that describes a set of malicious activities or attacks that occur over a period of time against a specific set of targets. Each Campaign should have a name or description and be associated with the below date range. Leave blank if there is no discernable campaign
* Year - 2019

### Attributes
* Resource level - Government
* Sophistication - Advanced expert
* Primary activities - Attempting to compromise industrial control systems, intellectual property theft

### Attack Pattern
A type of Tactics, Techniques, and Procedures (TTP) that describes ways threat actors attempt to compromise targets.
* [Phishing](URL to source)
* [Credential harvesting](URL to source)
* [DDoS] (URL to source)
* [Social engineering] (URL to source)
* Malware - Even More Miffins

### Vulnerabilities
A mistake in software that can be directly used by a hacker to gain access to a system or network. Link to a writeup in the exploit repo where possible (example, CVEs).
* [CVE-2019-0254](URL to outline of how CVE is exploited) used by Even More Muffins

### Course of Action 
An action taken to either prevent an attack or respond to an attack.
* Apply patch 5678 to ICS systems to patch CVE-2019-0254

### Identity
Individuals, organizations, or groups, as well as classes of individuals, organizations, or groups.

#### Individuals 
* [Katniss Everdeen](URL to source)
* [Rue Noname](URL to source)

#### Affiliated organisations
* [The 23rd Military Intelligence Division](URL to source)

#### Affiliated groups
* [Tea and Cake APT](URL to source)
* [Butternut Cookies APT](URL to source)

### Intrusion Set
A grouped set of adversarial behaviors and resources with common properties believed to be orchestrated by a single threat actor.
      
#### Malware
A type of TTP, also known as malicious code and malicious software, used to compromise the confidentiality, integrity, or availability of a victim’s data or system.
* Names - Even More Muffins, any other name the malware goes by
* Functionality - Backdoor, keylogger, screen overlay, registry editing, anything else it can do
* MD5 - 002ae76872d80801692ff942308c64t6
* Notes - using a similar codebase to the Extra Muffins malware, Even More Muffins has further functionality to overlay fake login screens over a user's desktop and make edits to the system registry

#### Website 
* About - Malicious site hosting downloader
* URL - hxxp://fds32fd3[.]cn/4712/
* IP - 575.125.0.0/80
* Valid from - 01 August 2019 
* Valid to - 01 September 2019

#### Command and Control Server
* About - used by Even More Muffins malware to receive commands from and exfiltrate data to
* URL - hxxp://f1ds32f1sd[.]cn/2134/
* IP - 789.545.0.0/15
* Valid from - 01 August 2019
* Valid to - 01 September 2019

#### Documents
* About - Word document attached to spearphishing emails, generates a popup that asks for credentials to connect to C&C server hxxp://f1ds32f1sd[.]cn/2134/
* SHA265 - 5243349a4ad00902e3d415b622cf27987a0170a786ca3a1f991a521bff645789

#### Tools
* Name - pwdump7, any other name known by
* Functionality - Dumps password hashes from the Windows registry
* URL - http://www.tarasco.org/security/pwdump_7/

### Report 
Collections of threat intelligence focused on one or more topics, such as a description of a threat actor, malware, or attack technique, including contextual details.
* [Examinging Examplus Hackerus](URL to pdf/blog post etc)
* Description - Since 2018, RandomAV Firm has investigated computer security breaches at hundreds of organizations. The details we have analyzed during hundreds of investigations convince us that a specific group is based primarily in Lorem Ipsum and that the Lorem Ipsum Government is aware of them. We refer to this group as APT2000, a single organization of operators that has conducted a cyber espionage campaign against a broad range of victims since at least 2018. Our analysis has led us to conclude that APT2000 is able to wage such a long-running and extensive cyber espionage campaign in large part because it receives direct government support. 

## Raw Intelligence
Information pulled from articles. Should for formatted with the article link, date if possible, and the information

## Links
Articles that are yet to be read








### Resource level: government

### Primary Activities
* Attempting to compromise industrial control systems
* Intellectual property theft

### Attack Pattern
A type of Tactics, Techniques, and Procedures (TTP) that describes ways threat actors attempt to compromise targets.
* [Phishing](URL to source)
* [Credential harvesting](URL to source)

### Course of Action 
An action taken to either prevent an attack or respond to an attack.

### Identity
Individuals, organizations, or groups, as well as classes of individuals, organizations, or groups.

#### Individuals - use brackets and links
* [Joanna Doe](URL to source)
* [Another Person](URL to source)

#### Affiliated organisations
* [The People's Republic of Lorem Ipsum](URL to source)
* [The 23rd Military Intelligence Division](URL to source)

#### Affiliated groups
* [That Other APT](URL to source)
* [Yet Another APT](URL to source)

### Indicator
Contains a pattern that can be used to detect suspicious or malicious cyber activity.

### Intrusion Set
A grouped set of adversarial behaviors and resources with common properties believed to be orchestrated by a single threat actor.

### Malware
A type of TTP, also known as malicious code and malicious software, used to compromise the confidentiality, integrity, or availability of a victim’s data or system.

### Observed Data
Conveys information observed on a system or network (e.g., an IP address).

### Report 
Collections of threat intelligence focused on one or more topics, such as a description of a threat actor, malware, or attack technique, including contextual details.

### Threat Actor 
Individuals, groups, or organizations believed to be operating with malicious intent.

### Tools
Legitimate software that can be used by threat actors to perform attacks.

### Vulnerabilities
A mistake in software that can be directly used by a hacker to gain access to a system or network. Link to a writeup in the exploit repo where possible (example, CVEs).

## Raw Intelligence
Information pulled from articles. Should for formatted with the article link, date if possible, and the information

## Links
Articles that are yet to be read
