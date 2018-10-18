![alt tag](https://user-images.githubusercontent.com/24201238/29351849-9c3087b4-82b8-11e7-8fed-350e3b8b4945.png)

# Panopticon Project

## Contributing Guidelines

Thank you for wanting to contribute!

### Table of contents

- [What should I know before I get started?](#what-should-i-know-before-i-get-started)
  - [The vision for P2](#the-vision-for-p2)
  - [The Code of Conduct](#the-code-of-conduct)
  - [What's already been done and what's underway](#whats-already-been-done-and-whats-underway)
  - [How to contact the maintainers to discuss contributions, where to interact with other contributors and how to ask for help](#how-to-contact-the-maintainers-to-discuss-contributions-where-to-interact-with-other-contributors-and-how-to-ask-for-help)
  - [The basic structure of P2](#the-basic-structure-of-p2)
  - [Working from GitHub issues is required](#working-from-github-issues-is-required)
  - [Posting your work to GitHub, where possible, is required](#posting-your-work-to-github-where-possible-is-required)
  - [Comments are required](#comments-are-required)
  - [The standards maintainers will adhere to](#the-standards-maintainers-will-adhere-to)
  - [How contributions are recognised](#how-contributions-are-recognised)
- [How can I contribute?](#how-can-i-contribute)
  - [Types of contributions](#types-of-contributions)
  - [How do I find things people have already flagged as needing work?](#how-do-i-find-things-people-have-already-flagged-as-needing-work)
  - [I have something I want to work on, what's the next step?](#i-have-something-i-want-to-work-on-whats-the-next-step)
  - [Report bugs](#report-bugs)
- [Enhancements](#enhancements)
  - [Making an enhancement](#making-an-enhancement)
  - [Suggesting an enhancement](#suggesting-an-enhancement)
- [Beginner issues](#beginner-issues)
- [Pull requests](#pull-requests)
- [Style Guide](#style-guide)

## What should I know before I get started?

### The vision for P2

Panopticon Project (P2) is an open database of open source intelligence (OSINT) covering the electronic capabilities of Advanced Persistent Threats (APTs), nation states, and corporations that exercise nation state capabilities. The [README](https://github.com/Panopticon-Project/panopticon-admin/blob/master/README.md) is your introduction to the project and the overarching vision of what we are trying to achieve together. 

### The Code of Conduct

We have one, it is located [here](https://github.com/Panopticon-Project/panopticon-admin/blob/master/code_of_conduct.md), please look over before contributing.

### What's already been done and what's underway

To give you an idea of where we've come from, what ground we've already covered, where we are going and what needs doing, check out our [roadmap](https://github.com/Panopticon-Project/panopticon-admin/blob/master/ROADMAP.md).

### How to contact the maintainers to discuss contributions, where to interact with other contributors and how to ask for help

* You can email the maintainer on panopticonproject at protonmail.com to discuss your contribution
* We are small at the moment and the community is still forming. Currently it's suggested if you want to talk to others contributing to the project, reach out to them on the email address/social media details listed in their GitHub profiles.
* As the community grows and other communication channels become popular we will look at setting those up. 
* We are integrating with the [Commons Platform](https://blog.p2pfoundation.net/the-commons-platform-an-interview-with-sophie-varlow-and-nick-wood/2018/08/22) and will have a specific forum for members of the Commons Platform who want to contribute to P2. You can join the Commons Platform by emailing welcome at commonsplatform.org

### The basic structure of P2

To ensure you are contributing to the right repository (repo) it's a good idea to look over the repos to get an idea for what goes where. 

#### Organisation

* [**panopticon-admin**](https://github.com/Panopticon-Project/panopticon-admin) - information about the project and its organisation, such as the project README, licence file, etc. (You're in this repo right now!)

#### Resources

* [**panopticon-Primer**](https://github.com/Panopticon-Project/panopticon-Primer) - Readings if you have no idea about a particular topic. This is your orientation into the fundamentals of the project to get you on the right page before contributing.

* [**panopticon-T-T**](https://github.com/Panopticon-Project/panopticon-T-T) - T-T stands for tools and techniques. This is where all the information on different tools available to people, along with examples of action OSINT investigations are kept. If you don't know how to contribute, read other this repo and it should give you some starting points. Try them out. Come back and read more. This is your classroom and as you learn new things that aren't in this repo, feel free to contribute.

#### Groups this project gathers information on

These are broken into three types:

* Nation State
* APT
* Corporation

#### Why are APTs and Nation States separate?

Because attribution is rarely one hundred per cent provable. The nation state repos will link to the APTs its strongly believed they sponsor and vice versa. Nation state repos will also cover things that are specific to the overall nation state but not specific to particular APTs.

### Posting your work to GitHub, where possible, is required

If you are working on something like gathering intelligence, processing raw intelligence, anything that can be saved rather can contributions like posting to social media etc., it's asked you post the material to GitHub. This will give oversight to your work, not just for the maintainers so they can track progress but for other volunteers as well so they can see where work is at, enabling volunteers to clearly see where and how they can contribute.

Please also give periodic updates if you're working on something spanning a length of time. Every two weeks is a good rule of thumb.

### Comments are required

If your contribution will take place in any way on GitHub or you use Git please read over [this](https://chris.beams.io/posts/git-commit/) blogpost. It's heavy on using Git from the command line but the fundamentals are still relevent. Comments make things easier for everyone, so please leave comments when making commits. Taken from the aforementioned blogpost, please follow these seven rules:

* Separate subject from body with a blank line (Github does this automatically)
* Limit the subject line to 50 characters (GitHub will warn you of this but not restrict you)
* Capitalize the subject line
* Do not end the subject line with a period
* Use the imperative mood in the subject line (your subject should be able to complete the following sentence: If applied, this commit will *your subject line here*)
* Wrap the body at 72 characters
* Use the body to explain what and why vs. how (unless the title is explanation enough, in which case leave the body out)

Examples:

Stop Embark crashing (*"If applied, this commit will stop embark crashing"* is a workable sentence as per the above rule)

This addition to the flux capacitor stablises Embark.

or the one liner:

Fix a typo in the Contributing guidelines

### The standards maintainers will adhere to

With the caveat that this is a volunteer project and everything is provided on a best efforts basis, below are the standards that maintaiers will adhere to and anyone wanting to be a maintainer will aspire to:

* Acknowledge when a new issue is posted by a contributor
* Notify users when you start and finish work
* Summarize the state of the issue
* Give periodic status updates
* Inform everyone if you slip
* Inform everyone if you’re on track
* Make responsibility handoffs clear
* Notify when new functionality is added to the project, and when fixes are made
* Always use a non-threatening tone and correct grammar to increase legibility

## How can I contribute?

### Types of contributions

P2 is a community, so contributing takes many forms.

* Do you want to contribute to P2 by finding and analysing articles? This is the traditional and entry level why people will contribute to this project. Below will run through the P2 intelligence cycle and STIX (Structured Threat Information Expression) which this project uses. 

* Do you want to contribute to P2 by performing your own research? The [Tools and Techniques](https://github.com/Panopticon-Project/panopticon-T-T) repo has resources to get you started on performing your own research. A methodology outling your process along with all relevent information found should be saved to the applicable repository. Often, people will use tools like [Maltego](https://www.paterva.com/web7/) for displaying their reserach. Maltego and many other OSINT tools come bundled with [Kali Linux](https://www.kali.org/).

* Do you want to contribute to P2 by writing code? P2 isn't a traditional open source project working on software, but there is a lot that can be contributed through code. As an example, there are lots of [tools](http://automatingosint.com/blog/) you could build a front end for. If that's your thing, this Contributing document outlines how you can do that. The below guidelines for contributing to code are just that, guidelines, not hard and fast rules that must be adhered to. We ask that you use your best judgement and as a rule of thumb, put yourself in the shoes of the project maintainers. If you ran a project and someone submitted what you are going to submit, does it make sense? Is it appropriate? 

* Do you want to contribute to P2 through other means (such as helping with social media or any other means that come to mind)? If so, please email the maintainers and contributions will be handled on a case by case basis.

### How do I find things people have already flagged as needing work?

Each repository will have a README file. Generally, that file will have gathered information, but at the bottom it will have links to articles yet read. Check below for the Infomration Cycle, but basically you can read those documents, strip out the facts and add them to the applicable categories on the README. 

Each repository will also have issues. Issues are sometimes used for things other than issues, like hosting images or working notes (becuase it's the easiest place for them), but generally you should find issues contain actual issues. Feel free to look over the issues in each of the repositories, and action any you feel comfortable with. In the interest of making contribution as easy as possible as the project grows we will create labels for issues.

Labels like [*Good Beginner Issue*](https://github.com/search?q=org%3Aaletheia-foundation+label%3A%22good+beginner+issue%22&state=open&type=Issues) let people know that the particular issue might be a good place for someone new to P2 or someone who may not have a great deal of opensource experience to start.

We also have labels corresponding with skillsets, so if you're looking for something in particular you should be able to find it.

The maintainers of Aletheia can only take a best guess at the type of contributions you want to make, so we have created labels as best we can but if you don't see an issue that corresponds to your skillsets, do not fret. You can still look over the existing issues, but we would also suggest you email the maintainers on contact@aletheia-foundation.io and let us know we should accomodate your skillset by adding labels for those skills. This will ensure that those with simmilar skills coming after you have a smooth journey. Helping the next person is all part of community building!

### I have something I want to work on, what's the next step?

Please email the maintainers on contact@aletheia-foundation.io, your email should be tended to within 24 hours in most instances. If you want something more immediate please join our [Slack](https://aletheiafoundation.slack.com/) channel to discuss your contribution with the maintainers and other Aletheians.

Non coders, this is where you leave off. Coders continue on!

### I want to work with GitHub and/or Git - add to index

Here are some resources:
https://www.tygertec.com/find-stuff-git/

### Report bugs

First you must:

* **Check** the [outstanding issues](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Aaletheia-foundation+) Aletheia has currently. Someone may have already reported it.
* **Determine** which repo the issue should be opened against, this is why it is a good idea to have a rough idea of Aletheia's building blocks. Not how they work, just want they are.

Once you have followed these steps you are ready to submit your bug report. Bugs are reported as GitHub issues.  

* navigate to the desired repo, click **Issues** from the options running along the top of the page, then click the green **"New Issue"** button.

To make your bug report as useful to others as possible, please consider the below and try to answer as many of them as possible:

**Explain the problem and include additional details to help maintainers reproduce the problem:**

* Use a clear and descriptive title for the issue to identify the problem.
* Describe the exact steps which reproduce the problem in as many details as possible.
* Describe the behaviour you observed after following the steps and point out what exactly is the problem with that behaviour.
* Explain what behaviour you expected to see instead and why.
* Include screenshots where possible.
* If you're reporting that Alethia crashed, include a crash report with a stack trace from the operating system if possible. Include the crash report in the issue in a code block, a file attachment, or put it in a gist and provide link to that gist.
* If the problem is related to performance, include a CPU profile capture and a screenshot with your report if possible.
* If the problem wasn't triggered by a specific action, describe what you were doing before the problem happened and share more information using the guidelines below.

**Provide more context by answering these questions:**

* Can you reproduce the problem in safe mode?
* Did the problem start happening recently (e.g. after updating to a new version of Aletheia) or was this always a problem?
* If the problem started happening recently, can you reproduce the problem in an older version of Aletheia? What's the most recent version in which the problem doesn't happen?
* Can you reliably reproduce the issue? If not, provide details about how often the problem happens and under which conditions it normally happens.

**Include details about your configuration and environment:**

* Which version of Aletheia are you using?
* What's the name and version of the OS you're using?
* Are you running Aletheia in a virtual machine? If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
* Are you using Aletheia with multiple monitors? If so, can you reproduce the problem when you use a single monitor?
* Which keyboard layout are you using? Are you using a US layout or some other layout?

## Enhancements

It would be great if our software did exactly what we wanted, and it can, that's the whole point of opensource. In that spirit if you have an enhancement you'd like to suggest and you know some programming, you are encouraged to work on the enhancement here on GitHub. If you don't know any programming you're encouraged to learn, it's a great skill! But in the meantime you can suggest an enhancement that someone else might build.

### Making an enhancement

* **Check** the [outstanding issues](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Aaletheia-foundation+) Aletheia has currently. Someone may be planning to work on something similar.
* **Read** the latest version of the [whitepaper](https://github.com/aletheia-foundation/whitepaper) first. This will align you with the project vision.
* **Email** contact@aletheia-foundation.io to discuss your enhancement before you start. Aletheia has been designed to overcome problems in very particular ways, and we need to ensure the the enhancement meshes with the rest of Aletheia and isn't something already being worked on. We don't want your time and effort to go to waste. Down the track it is envisaged that the go/no go call for an enhancement will be made by the community in keeping with Aletheia's principles of decentralisation.

### Suggesting an enhancement

* **Check** the [outstanding issues](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Aaletheia-foundation+) Aletheia has currently. Someone may have already reported it.
* **Determine** which repo (see *Aletheia repositories* above for a reminder) the enhancement should be opened against; this is why it is a good idea to have a rough idea of Aletheia's building blocks. Not how they work, just want they are.

Once you have followed these steps you are ready to submit your enhancement suggestion. Enhancements are suggested through GitHub issues much the same way bugs are reported.  

* navigate to the desired repo, click **Issues** from the options running along the top of the page, then click the green **"New Issue"** button.

To make your enhancement suggestion as useful to others as possible, please consider the below and try to answer as many of them as possible:

* Use a clear and descriptive title for the issue to identify the suggestion.
* Provide a step-by-step description of the suggested enhancement in as many details as possible.
* Provide specific examples to demonstrate the steps. Include copy/pasteable snippets which you use in those examples, as Markdown code blocks if possible.
* Describe the current behaviour and explain which behaviour you expected to see instead and why.
* Include screenshots which help you demonstrate the steps or point out the part of Aletheia which the suggestion is related to.
* Explain why this enhancement would be useful to most Aletheia users.
* List some other applications where this enhancement exists.
* Specify which version of Aletheia you're using.
* Specify the name and version of the OS you're using.

## Beginner issues

Want to help build Aletheia but unsure where to start? We've marked good beginner issues with the label *Good beginner issue*. Click [here](https://github.com/search?q=org%3Aaletheia-foundation+label%3A%22good+beginner+issue%22&state=open&type=Issues) to see all the open ones, and pitch in!

## Pull requests

 * Please adhere to the contributing guidelines listed above.
 * Add unit tests for any contracts or code that can be tested.

## Style Guide

  * [**aletheia-app**](https://github.com/aletheia-foundation/aletheia-app) Uses [Javasccript Standard Style](https://standardjs.com/).
  * The forked libraries each maintain their own code style standards.
  
## Gathering Intelligence

There are a number of disciplines that fall under the broad term intelligence. [The Intelligence Cycle](https://en.wikipedia.org/wiki/Intelligence_cycle) walks through the creation of intelligence.

* Direction - there is a need for intelligence and someone directs another party to provide it
* Collection - the gathering of intelligence through [various means](https://en.wikipedia.org/wiki/List_of_intelligence_gathering_disciplines) such as HUMINT (human intelligence), IMINT (imagery intelligence), ELINT (electronic intelligence), SIGINT (Signals Intelligence), OSINT (open source, or publicly available intelligence), etc.
* Processing - any process raw intelligence has to go through before analysis. This can include translation of materials from a foreign language, evaluation of relevance and reliability, and collation of intelligence
* Analysis - creating the actual contents of a "report", deciding the significance and implications of processed intelligence,  identifying collateral information and patterns by combining disparate pieces of information, then interpreting the significance of any newly developed knowledge.
* Dissemination - the actionable intelligence is given to the directing party in whatever format they wanted it in
* Feedback - based on a number of different things, only one being the intelligence you provided, further direction will be given on new intelligence required

We romanticise intelligence but this is what it is. Most people that have held down a desk job will recognise this process as creating the "executive summary", wehre a large amount of information needs to be conveyed to the higher ups and you pick and choose what the key messages are since you're the subject matter expert, and those key messages are generally all that is ever read. The key bit here is that the writer picks and chooses the key messages (the Analysis phase), it's terribly subjective. Intelligence can step away from being a science post the processing phase and can become an art. Or can just become an opinion piece. There is a lot of debate around the accuracy and usefulness of intelligence once it steps into the analysis phase. This is problematic for P2 as we're trying to adhere to verifiable facts. Some of the above steps also aren't applicable for P2.

* Direction - No one is directing us in most cases, we're doing this because we see a general need rather than something specific. We might be interested in what a particular government is up to generally, rather than needing to know the specific people a specific APT is going to target at a specific time, for instance. 
* Collection - This is fundamentally what P2 is all about, so this step is applicable
* Processing - Once we have the raw intelligence it needs to be presented in a logical and coherent manner, so yes this also applicable
* Analysis - As stated above, this is where we start stepping into the world of inferences. Past attribution of actions we largely want to stay away from this area
* Dissemination - In the case of P2, the information is disseminated online
* Feedback - As there was no real direction this isn't terribly applicable

## The Panopitcon Project Intelligence Cycle

This leaves us with the cut down Panopitcon Project Intelligence Cycle
* We need to understand what is going on online - we aren't being directed by anyone, but linking back to [Why Does Pantopicon Project Exist?](https://github.com/Panopticon-Project/panopticon-admin#why-does-panopticon-project-exist) from our README and our [Open Canvas](https://github.com/Panopticon-Project/panopticon-admin/blob/master/open-canvas.md) the world is becoming more dystopic, we need to understand what is going on as the first step at pushing back against it. P2's mission statement is "we need to understand the electronic capabilities of Advanced Persistent Threats (APTs), nation states, and corporations that exercise nation state capabilities.
* Collection - the gathering of intelligence through [various means](https://en.wikipedia.org/wiki/List_of_intelligence_gathering_disciplines) largely through OSINT (open source, or publicly available intelligence)
* Processing - logically presenting the intelligence here on the P2 GitHub repo 
* Dissemination - Comitting the intelligence to the P2 GitHub repo and elsewhere should people want to store the data in multiple locations

## Adding to a repository
When adding your own research to a repository, click create new file, then on the file name put the date in this format 00Month2018 (01Jan2018 for example), then press /, this creates a folder with the date your uploading the documents, then create a markdown file with a relevent name. This means individual research is grouped by date, which is important because research is often time sensitive. As an example, please see [this repository](https://github.com/Panopticon-Project/panopticon-fancybear/tree/master/01Jan2018).

## Advice for reading through written material

* Stick to the piece you're reading - Given the nature of the web we can often be reading something with links to other articles, and those have links to other things and so on. You can end up reading something entirely unrelated and have no idea how you got here. Stick to the piece you're reading, note down links for further material, read them once you finish what you're reading right now. Jumping around and not being systematic is how things get missed.

## Searches to run IPs, Domains etc through
* https://www.threatcrowd.org/
* Shodan
* https://www.riskiq.com/products/community-edition/
* https://whois.domaintools.com/ - Whois is free
* http://statuslite.com/domain/<website here> 

## Recomended software
### Maltego
It's suggested that [Maltego](https://en.wikipedia.org/wiki/Maltego) be used to visually display the research and put it all in one file that can be easily downloaded and examined by others. Maltego is proprietary software, which is sad, but it has a free community addition, is relatively straight forward to use, and already has acceptance in the information security community. Maltego is pre-installed with Kali Linux.

### Kali Linux
It's also suggested you use [Kali Linux](https://en.wikipedia.org/wiki/Kali_Linux). As well as giving you Maltego, Kali comes with a number of other open source intelligence tools, again all free. Really though, you can use any linux distribution, if you aren't using one specifically built for hacking/information gathering though you might find yourself spending a lot of time hunting for and downloading tools, so unless you're an old hand Kali is a good option. 

### Virtualisation software
Most people don't run Linux at home, but setting up a linux distribution isn't that difficult on Windows or Mac. For an easy route you can use virtualisation software, which will allow you to run multiple operating systems on the one computer. Installing an ISO file, the file type the linux operating system is downloaded in, on virtualisation software has a number of steps to it. Unless you've done this many times before I'd suggest searching for guides on how to install the particular Linux distribution you have on the particular virtualisation software you're using. YouTube is a good resource for this. Popular virtualisation software include VirtualBox and VMWare Player.

## Advice for using Maltego

* To get stared, Paterva have a good introduction video [here](https://www.youtube.com/watch?v=sP-Pl_SRQVo).
* Make sure all the transforms you have access to are installed before you start building your graph. The transforms give you access to additional entities to save you having to create some yourself and then trying to get all the background entity information correct so the data mining you do later actually works. 
* Build your graph as you go. Compiling all your information in a text editor is fine but by visualising the data as you discover things your search will be informed. You'll see what threads should be tugged on next, what's missing and you will be able to see and focus in on what you need to know.

## Use brackets in URLs, domain names email addresses and server names
so people don't accidentally nagivate to the address and potentially infect themselves
In the instance there are multiple dots just do the last dot
IP addresses can be left as is
example 
unisecproper[.]org
le0nard0@mail[.]com
nemohosts[.]com
ns1.nemohosts[.]com

## Stix
https://oasis-open.github.io/cti-documentation/stix/intro
* Attack Pattern - A type of Tactics, Techniques, and Procedures (TTP) that describes ways threat actors attempt to compromise targets.
* Campaign - A grouping of adversarial behaviors that describes a set of malicious activities or attacks that occur over a period of time against a specific set of targets.
* Course of Action - An action taken to either prevent an attack or respond to an attack.
* Identity - Individuals, organizations, or groups, as well as classes of individuals, organizations, or groups.
* Indicator - Contains a pattern that can be used to detect suspicious or malicious cyber activity.
* Intrusion Set - A grouped set of adversarial behaviors and resources with common properties believed to be orchestrated by a single threat actor.
* Malware - A type of TTP, also known as malicious code and malicious software, used to compromise the confidentiality, integrity, or availability of a victim’s data or system.
* Observed Data - Conveys information observed on a system or network (e.g., an IP address).
* Report - Collections of threat intelligence focused on one or more topics, such as a description of a threat actor, malware, or attack technique, including contextual details.
* Threat Actor - Individuals, groups, or organizations believed to be operating with malicious intent.
* Tool - Legitimate software that can be used by threat actors to perform attacks.
* Vulnerability - A mistake in software that can be directly used by a hacker to gain access to a system or network.

### How to fill out STIX
Shared Exploits and Malware go in the ShrdExpltsMlwr repo

Copy and paste this into the readme for the repo

![alt tag](https://user-images.githubusercontent.com/24201238/29351849-9c3087b4-82b8-11e7-8fed-350e3b8b4945.png)

# Panopticon Project

## Name
Common name of the threat actor

## Aliases
Other names the threat actor is known by
Use list
*
*

## Overview
A high level summary of the threat actor

## Date
The year the information pertains to

### Attack Pattern
A type of Tactics, Techniques, and Procedures (TTP) that describes ways threat actors attempt to compromise targets.

### Campaign 
A grouping of adversarial behaviors that describes a set of malicious activities or attacks that occur over a period of time against a specific set of targets.

### Course of Action 
An action taken to either prevent an attack or respond to an attack.

### Identity
Individuals, organizations, or groups, as well as classes of individuals, organizations, or groups.

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

## Next Date
Copy and paste the categories from Attack Pattern through to Vulnerabilities for subsequent years

## Raw Intelligence
Information pulled from articles. Should for formatted with the article link, date if possible, and the information

## Links
Articles that are yet to be read
