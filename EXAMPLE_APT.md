![alt tag](https://user-images.githubusercontent.com/24201238/29351849-9c3087b4-82b8-11e7-8fed-350e3b8b4945.png)

# Panopticon Project

add notes to each section
change how campaign works
working through https://oasis-open.github.io/cti-documentation/stix/examples

## Examplus Hackerus
* Label - Advanced Persistent Threat (APT)

## Aliases
* APT 2000
* Those Bad People

## Overview
APT2000 is a single organization of operators that has conducted a cyber espionage campaign against a broad range of victims since at least 2018.

## Campaign or year
A grouping of adversarial behaviors that describes a set of malicious activities or attacks that occur over a period of time against a specific set of targets. Each Campaign should have a name or description and be associated with the below date range. Leave blank if there is no discernable campaign
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

### Course of Action 
An action taken to either prevent an attack or respond to an attack.
* Apply patch 1234 to ICS systems

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

### Intrusion Set
A grouped set of adversarial behaviors and resources with common properties believed to be orchestrated by a single threat actor.
      
#### Malware
A type of TTP, also known as malicious code and malicious software, used to compromise the confidentiality, integrity, or availability of a victim’s data or system.
* Names - Extra Muffins, any other name the malware goes by
* Functionality - Backdoor, keylogger, anything else it can do
* MD5 - 001dd76872d80801692ff942308c64e6

##### Website 
* About - Malicious site hosting downloader
* URL - hxxp://x4z9arb[.]cn/4712/
* IP - 562.115.0.0/80
* Valid from - 01 August 2018 
* Valid to - 01 September 2013

##### Command and Control Server
* About - used by Extra Muffins malware to receive commands from and exfiltrate data to
* URL - hxxp://sd35f456[.]cn/2134/
* IP - 223.166.0.0/15
* Valid from - 01 August 2018
* Valid to - 01 September 2013

##### Documents
* About - Word document attached to spearphishing emails, generates a popup that asks for credentials to connect to C&C server hxxp://sd35f456[.]cn/2134/
* SHA265 - d393349a4ad00902e3d415b622cf27987a0170a786ca3a1f991a521bff645318

##### Tools
* Name - pwdump7, any other name known by
* Functionality - Dumps password hashes from the Windows registry
* URL - http://www.tarasco.org/security/pwdump_7/
      
#### Vulnerabilities
A mistake in software that can be directly used by a hacker to gain access to a system or network. Link to a writeup in the exploit repo where possible (example, CVEs).
* [CVE-2018-0158](URL to outline of how CVE is exploited) used by Extra Muffins

### Report 
Collections of threat intelligence focused on one or more topics, such as a description of a threat actor, malware, or attack technique, including contextual details.
* [Examinging Examplus Hackerus](URL to pdf/blog post etc)
* Description - Since 2018, RandomAV Firm has investigated computer security breaches at hundreds of organizations. The details we have analyzed during hundreds of investigations convince us that a specific group is based primarily in Lorem Ipsum and that the Lorem Ipsum Government is aware of them. We refer to this group as APT2000, a single organization of operators that has conducted a cyber espionage campaign against a broad range of victims since at least 2018. Our analysis has led us to conclude that APT2000 is able to wage such a long-running and extensive cyber espionage campaign in large part because it receives direct government support. 

## Campaign 
A grouping of adversarial behaviors that describes a set of malicious activities or attacks that occur over a period of time against a specific set of targets. Each Campaign should have a name or description and be associated with the below date range. Leave blank if there is no discernable campaign
* None

### Date range
Can be of a campaign. If there is no discernable campaign and campaign is blank, use beginning to end of a year.
* 01 January 2019 - 31 December 2019

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

"type": "attack-pattern",
      "id": "attack-pattern--3098c57b-d623-4c11-92f4-5905da66658b",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "Initial Compromise",
      "description": "As with most other APT groups, spear phishing is APT1’s most commonly used technique. The spear phishing emails contain either a malicious attachment or a hyperlink to a malicious file. The subject line and the text in the email body are usually relevant to the recipient. APT1 also creates webmail accounts using real peoples’ names — names that are familiar to the recipient, such as a colleague, a company executive, an IT department employee, or company counsel. The files they use contain malicious executables that install a custom APT1 backdoor that we call WEBC2-TABLE.",
      "external_references": [
        {
          "source_name": "capec",
          "description": "spear phishing",
          "external_id": "CAPEC-163"
        }
      ],
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "initial-compromise"
        }
      ]
    },
    {
      "type": "attack-pattern",
      "id": "attack-pattern--1e2c4237-d469-4144-9c0b-9e5c0c513c49",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "Establishing a Foothold",
      "description": "APT1 establishes a foothold once email recipients open a malicious file and a backdoor is subsequently installed.  In almost every case, APT backdoors initiate outbound connections to the intruder’s 'command and control' (C2) server. While APT1 intruders occasionally use publicly available backdoors such as Poison Ivy and Gh0st RAT, the vast majority of the time they use what appear to be their own custom backdoors. APT1’s backdoors are in two categories: 'Beachhead Backdoors' and 'Standard Backdoors.' Beachhead Backdoors offer the attacker a toe-hold to perform simple tasks like retrieve files, gather basic system information and trigger the execution of other more significant capabilities such as a standard backdoor. APT1’s beachhead backdoors are usually what we call WEBC2 backdoors. WEBC2 backdoors are probably the most well-known kind of APT1 backdoor, and are the reason why some security companies refer to APT1 as the Comment Crew. A WEBC2 backdoor is designed to retrieve a webpage from a C2 server. It expects the webpage to contain special HTML tags; the backdoor will attempt to interpret the data between the tags as commands. WEBC2 backdoors are often packaged with spear phishing emails. Once installed, APT1 intruders have the option to tell victim systems to download and execute additional malicious software of their choice. The standard, non-WEBC2 APT1 backdoor typically communicates using the HTTP protocol (to blend in with legitimate web traffic) or a custom protocol that the malware authors designed themselves. The BISCUIT backdoor (so named for the command “bdkzt”) is an illustrative example of the range of commands that APT1 has built into its “standard” backdoors. APT1 has used and steadily modified BISCUIT since as early as 2007 and continues to use it presently. Some APT backdoors attempt to mimic legitimate Internet traffic other than the HTTP protocol. When network defenders see the communications between these backdoors and their C2 servers, they might easily dismiss them as legitimate network traffic. Additionally, many of APT1’s backdoors use SSL encryption so that communications are hidden in an encrypted SSL tunnel.",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "establish-foothold"
        }
      ]
    },
    {
      "type": "attack-pattern",
      "id": "attack-pattern--e13f3e6d-4f9c-4265-b1cf-f997a1bf7827",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "Privilege Escalation",
      "description": "Escalating privileges involves acquiring items (most often usernames and passwords) that will allow access to more resources within the network. APT1 predominantly uses publicly available tools to dump password hashes from victim systems in order to obtain legitimate user credentials.",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "escalate-privileges"
        }
      ]
    },
    {
      "type": "attack-pattern",
      "id": "attack-pattern--5728f45b-2eca-4942-a7f6-bc4267c1ab8d",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "Internal Reconnaisance",
      "description": "In the Internal Reconnaissance stage, the intruder collects information about the victim environment. Like most APT (and non-APT) intruders, APT1 primarily uses built-in operating system commands to explore a compromised system and its networked environment. Although they usually simply type these commands into a command shell, sometimes intruders may use batch scripts to speed up the process.",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "internal-recon"
        }
      ]
    },
    {
      "type": "attack-pattern",
      "id": "attack-pattern--0bea2358-c244-4905-a664-a5cdce7bb767",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "Lateral Movement",
      "description": "Once an APT intruder has a foothold inside the network and a set of legitimate credentials, it is simple for the intruder to move around the network undetected. They can connect to shared resources on other systems. They can execute commands on other systems using the publicly available 'psexec' tool from Microsoft Sysinternals or the built-in Windows Task Scheduler ('at.exe').",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "move-laterally"
        }
      ]
    },
    {
      "type": "attack-pattern",
      "id": "attack-pattern--7151c6d0-7e97-47ce-9290-087315ea3db7",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "Maintain Presence",
      "description": "In this stage, the intruder takes actions to ensure continued, long-term control over key systems in the network environment from outside of the network. APT1 does this in three ways: Install new backdoors on multiple systems, use legitimate VPN credentials, and log in to web portals.",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "maintain-presence"
        }
      ]
    },
    {
      "type": "attack-pattern",
      "id": "attack-pattern--0781fe70-4c94-4300-8865-4b08b98611b4",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "Completing the Mission",
      "description": "Similar to other APT groups we track, once APT1 finds files of interest they pack them into archive files before stealing them. APT intruders most commonly use the RAR archiving utility for this task and ensure that the archives are password protected. Sometimes APT1 intruders use batch scripts to assist them in the process. After creating files compressed via RAR, the APT1 attackers will transfer files out of the network in ways that are consistent with other APT groups, including using the File Transfer Protocol (FTP) or their existing backdoors. Many times their RAR files are so large that the attacker splits them into chunks before transferring them. Unlike most other APT groups we track, APT1 uses two email-stealing utilities that we believe are unique to APT1. The first, GETMAIL, was designed specifically to extract email messages, attachments, and folders from within Microsoft Outlook archive ('PST') files. The GETMAIL utility allows APT1 intruders the flexibility to take only the emails between dates of their choice. In one case, we observed an APT1 intruder return to a compromised system once a week for four weeks in a row to steal only the past week’s emails. Whereas GETMAIL steals email in Outlook archive files, the second utility, MAPIGET, was designed specifically to steal email that has not yet been archived and still resides on a Microsoft Exchange Server. In order to operate successfully, MAPIGET requires username/password combinations that the Exchange server will accept. MAPIGET extracts email from specified accounts into text files (for the email body) and separate attachments, if there are any.",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "complete-mission"
        }
      ]
    },
    {


*** look over the report and see what the hash is of
"type": "indicator",
      "id": "indicator--031778a4-057f-48e6-9db9-c8d72b81ccd5",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "HTRAN Hop Point Accessor",
      "pattern": "[ipv4-addr:value = '223.166.0.0/15']",
      "labels": [
        "malicious-activity"
      ],
      "valid_from": "2015-05-15T09:00:00.000Z",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "establish-foothold"
        }
      ]
    },
    {
      "type": "indicator",
      "id": "indicator--da1d061b-2bc9-467a-b16f-8d14f468e1f0",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "HTRAN Hop Point Accessor",
      "pattern": "[ipv4-addr:value = '58.246.0.0/15']",
      "labels": [
        "malicious-activity"
      ],
      "valid_from": "2015-05-15T09:00:00.000Z",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "establish-foothold"
        }
      ]
    },
    {
      "type": "indicator",
      "id": "indicator--2173d108-5714-42fd-8213-4f3790259fda",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "HTRAN Hop Point Accessor",
      "pattern": "[ipv4-addr:value = '112.64.0.0/15']",
      "labels": [
        "malicious-activity"
      ],
      "valid_from": "2015-05-15T09:00:00.000Z",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "establish-foothold"
        }
      ]
    },
    {
      "type": "indicator",
      "id": "indicator--8ce03314-dfea-4498-ac9b-136e41ab00e4",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "HTRAN Hop Point Accessor",
      "pattern": "[ipv4-addr:value = '139.226.0.0/15']",
      "labels": [
        "malicious-activity"
      ],
      "valid_from": "2015-05-15T09:00:00.000Z",
      "kill_chain_phases": [
        {
          "kill_chain_name": "mandiant-attack-lifecycle-model",
          "phase_name": "establish-foothold"
        }
      ]
    },
    {
      "type": "indicator",
      "id": "indicator--3f3ff9f1-bb4e-4392-89e5-1991179042ba",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "FQDN hugesoft.org",
      "pattern": "[domain-name:value = 'hugesoft.org']",
      "labels": [
        "malicious-activity"
      ],
      "valid_from": "2015-05-15T09:00:00.000Z"
    },
    {
      "type": "indicator",
      "id": "indicator--8390fd29-24ed-45d4-84d7-c5e5feaf195d",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "FQDN arrowservice.net",
      "pattern": "[domain-name:value = 'arrowservice.net']",
      "labels": [
        "malicious-activity"
      ],
      "valid_from": "2015-05-15T09:00:00.000Z"
    },
    {
      "type": "indicator",
      "id": "indicator--1002c58e-cbde-4930-b5ee-490037fd4f7e",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "FQDN msnhome.org",
      "pattern": "[domain-name:value = 'msnhome.org']",
      "labels": [
        "malicious-activity"
      ],
      "valid_from": "2015-05-15T09:00:00.000Z"
    },
    {
      "type": "indicator",
      "id": "indicator--8d12f44f-8ac0-4b12-8b4a-3699ca8c9691",
      "created": "2015-05-15T09:00:00.000Z",
      "modified": "2015-05-15T09:00:00.000Z",
      "object_marking_refs": [
        "marking-definition--3444e29e-2aa6-46f7-a01c-1c174820fa67"
      ],
      "name": "Appendix E MD5 hash '001dd76872d80801692ff942308c64e6'", <-- what is this??
      "pattern": "[file:hashes.md5 = '001dd76872d80801692ff942308c64e6']",
      "labels": [
        "malicious-activity"
      ],
      "valid_from": "2015-05-15T09:00:00.000Z"
    },
