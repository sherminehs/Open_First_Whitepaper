[« Previous Page : Open Standards](2_Open_Standards.md) | [Table of Contents](../README.md#table-of-contents) | [Next Page: Open Source Software Contribution »](4_Open_Source_Software_Contribution.md)

## Open Source Software Use

- [Disambiguation](#disambiguation)
- [History](#history)
- [Intellectual property](#intellectual-property)
- [Using open source software](#using-open-source-software)
- [Benefits](#benefits)
- [Risks and Drawbacks](#risks-and-drawbacks)
- [Best Practices for using OSS](#best-practices-for-using-oss)
- [Contributing to Open Source Software](#contributing-to-open-source-software)
- [Preferred Open Source Software](#preferred-open-source-software)
- [Examples](#examples)

### Disambiguation

Free software and open source software is software where the source code is distributed and can be used, copied, studied and redistributed.

Free software and open source software are almost equivalent but represent two different visions and neither want to be included in the other. You will find authors using "free open source software (FOSS)" or "free/Libre open source software (FLOSS)". For the purposes of this whitepaper we opted to use "open source software (OSS)" to talk about free (in the sense of freedom) software and open source software.

### History

OSS goes back to the beginnings of computer science. Many of the successes of Open Government could only be possible because of open source code and the generosity of internet communities. We should pay that back.

Software licensing (open source and proprietary) trace their origins from a common source: the Unix operating system. ([source](https://opensource.com/article/17/9/open-source-licensing)) The story is detailed in the [Origins and History of Unix](http://www.faqs.org/docs/artu/ch02s01.html). Unix was developed by AT&T Bell Laboratories in the late 1960s and early 1970s and was the first general-purpose operating system. At that time, the US Justice Department issued a consent decree barring AT&T from engaging in commercial activities outside the field of its primary business, telephone service. Because of the consent decree, AT&T could not exploit Unix as a commercial product, so Bell Labs gave Unix away in source code form under terms that allowed its modification and redistribution. This led to Unix’s widespread use and popularity among computer scientists in the 1970s and 1980s.

After the US Justice Department lifted the consent decree in 1983, AT&T commercialized Unix as a proprietary product and adopted more closed licensing terms. Meanwhile, the 1980s saw the advent of microcomputers (PCs), which led to the standardization of software. This standardization, in turn, encouraged companies to distribute their software in binary-only form because there was less need for users to investigate or troubleshoot source code. And so proprietary licensing became the dominant model for licensing software.

Following to this change, Richard Stallman and the GNU Project started to build an operating system that would be a free alternative to UNIX. This is around the same time as the Free Software Foundation was started to promote the use of free software. The operating system needed both kernel and the tools necessary to install, run and develop programs for it. The GNU Project developed the tools but was missing a working kernel. This is when Linus Torvalds, a teenager in Finland, developed the first Linux kernel as a school project.

The combination of the Linux kernel and the GNU tools - most commonly called Linux - was released under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) (GPL), a licensing model that was created by the GNU Project. The GPL granted recipients unfettered rights to redistribute software with the condition that the source code could not be kept secret. As Linux grew in popularity, with thousands of contributors and billions of users, the industry learned to follow and adopt GPL’s terms. By the late 1990s, GPL and the open source licensing paradigm more broadly gained traction and industry-wide acceptance.

### Intellectual property

#### Licences

Today, the GPL licence is in its third version (GNU GPLv3) and is only one of several dozen types of open source licences. The Open Source Initiative has approved more than 80 open source licences. These generally fall into one of two categories: permissive licences and reciprocal licences.

Even amongst the licences that the FSF and OSI approve as sharing the basic characteristics of OSS, the various terms and obligations vary greatly. However, there are several categories of clauses commonly encountered:

- General disclaimers of warranty and/or liability;
- Notice obligations, which generally require notifying downstream users of the particular OSS licence that applies to the work;
- Source code obligations, which generally require providing the source code of the software upon distribution; and
- Reciprocal licensing obligations, which generally require releasing any modifications or improvements as OSS, under the same licence.

The first two types of clauses - disclaimers and notice obligations – are present in nearly every OSS licence. In fact, the short and popular [2-Clause BSD License](https://opensource.org/licenses/BSD-2-Clause) contains little more than these two bare obligations. Other more expansive licences, such as the GPL, contain clauses setting out all four of these obligations.

For more details on licence clauses and other legal issues, see: [Annex A - Legal](9_Annex_Legal.md)

#### Copyright

Licence and copyright are two separate things. In some cases the licence may grant additional rights to the copyright holder(s). Work done by Government of Canada employees during work hours is Copyright (c) Crown Copyright, Government of Canada.

### Using open source software

Within the context of OSS use where one does not distribute the software, there are five scenarios in which organizations typically make use of OSS: web and file services, desktop office suites, specialty software applications, customized software for in-house use, and customized software for use within other departments in the same organization.

The Smile [Open Source Guide](http://www.open-source-guide.com/en) currently lists over 350 "professional" OSS solutions with reviews and evaluations.

#### Server-side software

Especially on the internet, OSS has long been a cornerstone of server software. OSS web server software such as Apache and Nginx run more than 65% of the active sites on the internet according to [Netcraft February 2017 Web Server Survey](https://news.netcraft.com/archives/2017/02/27/february-2017-web-server-survey.html). The OSS database server MySQL and MariaDB is widely popular, and the OSS-licensed TomCat software captures a majority of the Java application servers market. ([source](https://blog.jelastic.com/2016/04/14/software-stacks-market-share-first-quarter-of-2016/))

Public sector organizations deploy OSS for servers as readily as private sector organizations. For example, the primary Government of Canada website at [Canada.ca](https://www.canada.gc.ca) runs on the open source Apache web server. The National Research Council (NRC) uses Apache, MySQL, and the OpenLDAP authentication tool for electronic publications. In fact, overall, server-side software remains the primary use of OSS within public sector organizations. (more recent examples..)

#### Desktop Productivity Software

Compared to server-side OSS use, institutional and business use of open source desktop software is a relatively new occurrence. However, a 2008 research paper [The Migration of Public Administrations Towards Open Source Desktop Software](https://www.igi-global.com/chapter/migration-public-administrations-towards-open/10088) shows that this area of open source software has seen increased interest in recent years, especially in the public sector. For example, public administrators in the City of Paris decided to migrate 17,000 desktop computers with Microsoft Office and Microsoft Internet Explorer over to using OpenOffice.org and Mozilla Firefox. According to an [article published on the European Union's Interoperability Solutions for Public Administrations website](https://joinup.ec.europa.eu/news/french-gendarmerie-open-sou), the French Gendarmerie Nationale (national police) began by using OpenOffice on all it 90,000 PCs. In 2006 it installed web browser Mozilla Firefox and email client Mozilla Thunderbird on all PCs, followed by other OSS desktop tools, including image manipulation software Gimp and multimedia application VLC. In 2008 it implemented Ubuntu Linux on the first 5000 desktops and now have 72,000 Ubuntu Linux workstations. Although LibreOffice and Firefox are amongst the most common OSS desktop productivity applications, a broad range of applications are available.

#### Specialty Software

Many OSS utilities and applications serve a particular business area or other interest. In the case of highly-specialized software, alternatives to a particular OSS application may not even exist if no sufficiently large market has developed to attract closed-source vendors. In many cases, academic researchers directly release their specialized research initiatives as OSS software libraries and applications.

As one example within the specialty area of geomatics, [MapServer](http://mapserver.org/) is a OSS package commonly used to display dynamic spatial maps over the internet. MapServer was originally developed at the University of Minnesota. Released under OSS licence, it is now administered by the Open Source Geospatial Foundation (OSGeo) and used and supported by a worldwide developer community.

#### Internal Modification

All OSS licences grant users broad rights to modify the software. Recalling that reciprocal obligations only engage upon distribution, one can exercise this right to modify the software for internal use without triggering any additional legal obligations. The legal context of modifying OSS and using it internally is the same as merely using it internally without modification.

However, although there is no legal difference between these two scenarios, some organizations and businesses may still wish to establish a policy of handling modified software differently, like the `NRC Open Source Software Guidelines` (available on GCpedia). Tracking and handling modified software with extra caution can help ensure that an organization or business does not mistakenly distribute the software at a future time (which would then raise additional legal implications).

#### Internal Distribution

The scenario of “use without distribution” (i.e., the context which does not engage reciprocal licensing obligations) is relatively broad in scope. In general, internal distribution within a business or organization does not constitute a legal “distribution” or “conveyance” and does not implicate reciprocal licensing obligations. For example, the GPL considers distribution as “any kind of propagation that enables other parties to make or receive copies”. A corporation is only a single legal party and can make, modify and distribute OSS to its employees without engaging additional obligations.

Given that separate government departments operate semi-autonomously, there is a possible argument that the different departments constitute different “parties”. However, this interpretation is unlikely. Such an understanding would be incongruent with the general legal understanding of a federal or provincial Crown as being a single legal entity. A 2005 research paper [Legal Issues for the Use of Free and Open Source Software in Government](http://www.austlii.edu.au/au/journals/MelbULawRw/2005/13.html) show that Eben Moglen, general counsel for the FSF, which typically promotes a strong and wide understanding of distribution, takes the view that “[f]ederal Government agencies may share free software without making a ‘distribution’“.

However, distribution between the different legal entities of the federal crown and a provincial crown, or between provincial crowns, almost certainly constitutes “distribution”.

### Benefits

A key feature of OSS is that anyone can freely distribute the software. As a result, most OSS is available for download on the internet without cost, but there are certainly still maintenance and management expenses. For businesses choosing to use OSS, the nil up-front licensing cost is an attractive and key policy driver for making this decision. It can lower operating expenses. For the public sector, cost is also important. In addition, other public benefits can motivate public sector use of OSS.

OSS is how modern organizations build software. Documented advantages over software built by a handful of developers include the quality of solutions generated through the diversity of ideas and communities that form around a shared challenge. Exposing the problem space to other interested organizations also provides additional human capital to tackle challenges. For example, Linux, an open source operating system, is the largest development project in the world, with thousands of people contributing to every release. Many competing companies contribute to Linux and other OSS, allowing them to leverage the work of a global community of OSS developers and shift developers from low-value work to high-value work.

Using OSS allows for product customization, advances interoperability between tools through the use of [Open Standards](2_Open_Standards.md), and improves the overall quality of the final product. Other benefits include:

#### Avoiding Vendor Lock-in

When a closed-source software application becomes entrenched into an organization’s or business’s processes or products, the organization becomes beholden, or “locked-in”, to that software vendor for any new features, for bug fixes, and in many cases, for receiving product support. Where a vendor is unwilling to implement a new feature, you may need to switch to an alternative – often at considerable cost. Where a particular vendor is slow to provide bug fixes or support, this can adversely affect your own timelines and may also impose a security risk.

OSS provides an advantage in that it creates an open marketplace for providers of all types of support. Any support business with sufficient software development competencies can add new features and fix bugs in the software; OSS users can also switch to a different support provider whenever an existing company no longer meets their needs or timelines.

The flexibility of using OSS compel GC to meet user needs by modifying existing or creating new OSS. OSS is particularly suitable for rapid prototyping and experimentation. The testing process generates minimal costs, and the process encourages the identification and elimination of defects not recognized by the original development team.

#### Support for the Local Economy and Communities

Depending on the dynamics of a software industry in a particular locality, OSS use may better support local businesses in the area. Because OSS is openly available, distributable, and modifiable, a wider breadth of smaller “support service” businesses may provide commercial services. Rather than a single vendor providing the warranty and technical support, any competent local IT business can provide these services. Rather than a single vendor being the only party in a position to customize software, a local consulting or software development business can provide specialized versions of the software. This dynamic can directly contribute to Canadian economic growth.

Publicly available source code enables continuous and broad peer review. Whether simply publishing the completed code or opening the development process, the practice of expanding the review and testing process to a wider audience beyond the development team ensures increased software reliability and security. Developing in the open also allows for other opinions to help adjust the direction of a product to maximize its usefulness to the community it serves.

The code created by public administration belongs to the public. By developing OSS, we help populate a larger commons that cities, states, businesses, and individuals can participate in. This creates real economic value by lowering the burden of replicating similar work or by allowing the private sector to build off of and create new businesses around code developed by the GC. OSS is globally recognized as a major enabler of innovation.

#### Cost

The total cost of ownership for using any software application involves three over-arching categories of expenses: (1) up-front licensing and implementation costs, (2) on-going maintenance and support costs, and (3) software upgrade or transition costs.

When using OSS, the up-front licensing cost is zero (aside from internal costs of assessing the software and the licence). A OSS licence is always “open” and granted to the world, in that it licenses everyone to use the software without any fees due. Moreover, due to the fact that OSS licences grant everyone the right to redistribute the software, nearly all OSS packages are available for free download over the internet.

As well, OSS software often incurs lower on-going maintenance costs. With closed-source software, the vendor and its select business partners are quite often the only businesses able to provide adequate support (either because the software licence grants the vendor an exclusive support contract, or due to the vendor's specialized expertise with the software and its sole ability to examine and work with the source code). This can potentially undermine competitive tendering and, in some cases, result in poor support with no available alternative. OSS, on the other hand, permits anyone to install, fix, and otherwise support the software. This can allow for a more competitive tendering of support services amongst firms. With respect to software upgrades, some closed-source vendors require licensees to purchase a new licence, or pay an upgrade fee, for new versions of the software. For OSS, on the other hand, no new licence is necessary to start using a new version of the software.

The flexibility of OSS enables rapid response to changing missions and markets as well as rapid provisioning of both known and unanticipated users. Being scalable in both directions leads to a risk reduction of longer term financial implications (and potential redundant licences). Support and maintenance of OSS - as opposed to more burdensome usages of proprietary software - provides a real cost advantage where multiple copies of software are required, or when the user base grows. The total cost of ownership is shared with a community, rather than solely the Government of Canada.

#### Security

One of the most misunderstood aspects of the Open Source Software (OSS) development model is the security benefits it offers. OSS security relies on genuinely hardened code that is tested by a large number of reviewers in a wide variety of circumstances. Linus Torvalds simply noted, "talk is cheap, show me the code."

When using OSS, all of the source code is openly published. This makes it difficult for anyone to surreptitiously insert malicious code. It also allows security auditors and security researchers to inspect the code for flaws. While software security is a concern for all entities, it is of paramount importance to governments. For this reason, defence and national security agencies very often use OSS. As shown in the 2008 research paper [Open Source Technology and Policy](http://www.cambridge.org/gb/academic/subjects/computer-science/computing-and-society/open-source-technology-and-policy#reAzLTMdGB0YmGoC.97) gives the example of extensive use of OSS within U.S. D.o.D. and NSA and explain the security benefits:
>  A key factor in the attractiveness of open software in security (and national security) applications is its auditability. It is obviously harder to conceal things in open source code, while, conversely, governments may have reason to be leery of what may lurk inside proprietary code...In the U.S. context, the major proprietary vendor Microsoft is a domestic corporation, so at least the government can be expected to work out disclosure mechanisms with the vendor. However, this is a less likely scenario for foreign-held entities. For example, is Microsoft likely to disclose proprietary code to the government of Venezuela because that government wants to scrutinize Microsoft applications for security flaws or traps?

Thus, where OSS is well-developed and well-inspected by third parties, security is generally improved. There are some security risks as well, discussed below.

##### Reliance on Hardening, Not Obfuscation

OSS relies on good security practices instead of obscurity. A common misconception is that hiding code helps to prevent successful attacks. As NIST standard body recommends: "System security should not depend on the secrecy of the implementation or its components." Open Source development practices rely on hardening (or improving the security of) code by making it available for peers to test and try to break, and then fixing the problems found.

OSS is not always more secure, however in both theory and practice the OSS security model has proven that it can more quickly respond to and correct security issues.

Obfuscation relies on attacker ignorance and hides poor security practices. Within five months of the source code release of InterBase version 6, a hard-coded backdoor that had existed for seven years was found by the OSS community and fixed.

##### Wide Peer Review

Assuming that the goal is to make secure software, it is obvious that the easiest way to find flaws in a project is to make all of the project's code completely transparent. This approach may seem counter-intuitive, if the ultimate goal is anything other than the integrity of the technology.

By openly releasing a project's code and making it readily available via the Internet the community of peer reviewers is expanded worldwide. The community will quickly find flaws and the project team can take action to fix them. This simultaneously garners exceptionally wide and deep testing feedback from developers who need the code to be as secure as possible for their own use as well as the community's. Both the project owners and community benefit from sharing flaws and fixes.

Because the OSS security model is established on industry-accepted best practices and the actual code is widely available, projects are widely reviewed, thoroughly scrutinized, practically improved and quickly hardened.

Sound security practices are only possible with open peer review. This is the basis of an evidence-based approach to any field of study. Technology is no different and shouldn't be treated as if vendors have special access to the truth.

If you'd like to read more on OSS security, you can consult [UK CESG | OSS – Exploring the Risk (PDF)](https://www.ncsc.gov.uk/content/files/guidance_files/GPG%2038%20-%20Open%20Source%20Software%20%20-%20issue%201.1%20-%20Oct%2015%20-%20NCSC%20Web.pdf) and [US DoD | OSS FAQ](http://dodcio.defense.gov/Open-Source-Software-FAQ/#OSS_and_Security.2FSoftware_Assurance.2FSystem_Assurance.2FSupply_Chain_Risk_Management).

#### Productivity Gains

OSS project openness and availability of source code allows IT professionals to be more efficient in many ways, for example:

- Quickly assess/test a platform with minimal costs and administrative delays (e.g. Proof of Concept);
- Easily interact with the community (developers, users) to ask questions, suggest enhancements and report bugs;
- Quickly find relevant information through many open channels (e.g. documentation, wiki, forum, bug tracking system) and improve it as required; and
- Influence the roadmap of the project.

#### IT Talent

There's a growing number of IT professionals with OSS background/experience due to many reasons:

- OSS is widely used by companies, from development to production, generating high demand for talent;
- Contributions to OSS projects help being part of a public "network of trust" and lead to a valuable resume; and
- Some prefer to work with OSS because it improves their job satisfaction (see next benefit).

Therefore, being OSS friendly is increasingly becoming a necessity to attract talented and innovative IT Talent.

##### Job Satisfaction

OSS can as well increase the satisfaction of employees supporting OSS solutions:

- More learning opportunities as they have access to everything running under the hood;
- The positive feeling that they contribute to something bigger than themselves through OSS contributions (source code fixes, bug reports, documentation updates, etc.); and
- Improvement of collaboration skills as they engage with other developers from the OSS project (and learn from more experienced ones).

#### Reduction in liability

OSS licenses don't create obligations on the mere use of software and reduce the increased legal risks associated with the use of closed-source solutions. Not allowing obligations for the mere use of the software is part of the FSF's definition of free software, and the OSI's definition of open source. If an obligation from the use of the software exists, then the software doesn't qualify as OSS.

### Risks and Drawbacks

Of course, a business or government organization must balance these benefits against several drawbacks, such as lower user familiarity with OSS software packages.

#### Lower User Familiarity

User familiarity with OSS software packages is often much lower than with closed-source software packages. Closed-source software has a strong foothold in schools (at least in Canada) and many people learn to use computers through closed-source software, due to its pre-installation by hardware suppliers. For this reason, OSS can require more training and support.

#### Security

Because all of the source code of OSS is openly published, anyone – including “black hat hackers” – can examine the code for security holes. In particular, malicious attackers can observe where OSS software shares the same design, code base, or architecture as software that may have known security vulnerabilities. ([source](https://www.igi-global.com/book/handbook-research-open-source-software/494))

Of course, one must weigh this drawback against the aforementioned security benefits. In many cases, malicious hackers can still obtain access to the source code of closed-source software where non-disclosure agreements, company ethics procedures, or vendor security mechanisms fail. Or they can disassemble the closed binary and analyze it to identify potential flaws. Whereas closed-source software security depends on an attempt to maintain an information imbalance between the “white hats” (computer security analysts) and the “black hats” (malicious computer hackers), OSS software security depends upon an open competitive process of finding and closing security holes. The models rely on different strategies, and each has its particular risks that an organization must weigh and consider.

#### Loss of Control over Software Management

The ease and no-cost option of downloading OSS from the internet, and instantly installing it, can create an attractive proposition for employees to side-step procurement processes altogether. As a consequence, IT staff may lose track of what software is running on employee workstations, making systems security management more difficult.

The same is true for source code modified or mixed without proper oversight, including through an external contractor, legal risks may arise around intellectual property (copyright and licence). It is important to ensure legal compliance with the Copyright Act and make sure such activities are integrated and planned in the software development lifecycle.

#### In-house Expertise

Those considering using and developing open source "in-house" must ensure that they have the right level of expertise to manage it effectively. Staff are often traditionally trained in using proprietary software so the introduction of new open source solutions may require retraining.

#### Supplier Availability

Large system integrators may be reluctant to propose open source solutions which may generate less revenue and not be aligned with their product or skill set.

#### Rate of Change

Some open source projects evolve rapidly with short release cycles, which can require more work to deploy the updates to the users. On the other side, some projects can have a very slow rate of change attributed by a lack of participation by the community (users, vendors...). This is why it is important to carefully assess the level of activity of a given community if we envision relying on it in some ways.

### Best Practices for using OSS

#### Software Evaluation and Procurement

##### Evaluating Software Features

In general, the same factors applicable to an evaluation of the feature set and maturity of closed-source software also apply to OSS. The following factors merit consideration when evaluating OSS:

- **Community** A strong user community involved in a project provides people to answer questions, test the software, report bugs, suggest improvements and drive forward overall interest in the software.
- **Release Activity** A strong developer community with a history of releases and continued involvement tends to demonstrate that fixes and improvements to the software will continue into the future.
- **Longevity** Longevity, measured in both in terms of the age of the product and the number of versions released, indicates a project's stability and chance of survival.
- **Licence** Software is available for re-use under an OSS licence and code is in a common code repository. The licence of a project can affect the level of legal risk which you must assume (see [Legal Risk Management](9_Annex_Legal.md#legal-risk-management)).
- **Support Availability** Support considerations include user support (i.e., the availability of assistance with installation and usage) and maintenance (i.e., fixing problems in the software). Support for OSS can be provided by the community and/or paid support services businesses.
- **Documentation** User documentation provides important information to help users install software and use its features.  Technical documentation provides requirments and instructions for installation, development, deployment and configuration of the software.
- **Security** Although OSS code is auditable, this does not necessarily mean it is secure. The quality of the code and the typical response time for patching security-related flaws help indicate the security level of the software.
- **Functionality** Specific functionality needs depend on the business case for the software and need to be assessed on a case-by-case basis.
- **Integration** Where a software package will interact with other pieces of software, or with particular data formats, compatibility and the ability to integrate the software and data together becomes a paramount consideration.

The [OpenHub](https://www.openhub.net/) Website provides many useful metrics to help with evaluation of OSS. For example, it lists security vulnerabilities of the project, the number of contributors, and the frequency of software updates.

##### Comparing OSS and Closed-source software

In making software procurement decisions, it is common practice to assess OSS on equal footing with closed-source software (examples..). Starting from a list of business requirements, a government organization or business can assess how well the feature set of a OSS software package matches the requirements, and calculate the overall cost-per-feature over the required lifetime of the software.

This type of assessment provides a useful starting point. However, several interviewees reported difficult experiences in making “apples-to-apples” comparisons between OSS and closed- source software. Although an assessment of the total cost of ownership is feasible for both, it is difficult to account for factors such as benefits to the public (e.g., overall economic efficiency, support for local businesses, etc.).

Compounding this difficulty, established software procurement and service tendering processes are sometimes tailored towards closed-source solutions. The processes are not always flexible enough to properly assess and address OSS solutions. For example, a procurement process may first involve a call for tenders on the initial licensing contract. Here, OSS-based businesses are not likely to bid, as they have no licences to sell. Where the next stage of a procurement process would call for tenders on support services, OSS-based support businesses may already be closed out. Closed-source software vendors often prohibit anyone else from servicing or providing support for their product, thereby barring OSS-based businesses from the whole process. ([source](http://www.cbc.ca/news/technology/an-open-door-for-open-source-1.810739))

Thus, although a direct comparison between all potential solutions – both OSS and closed-source – is a helpful practice, it may also be necessary for businesses and organizations to revisit existing processes and procedures in order to ensure that these adequately envision both categories of software.

#### Training and Support

Depending on the context, it is prudent to allocate appropriate resources for training and assistance with OSS. Although this may not be necessary when merely installing new OSS on a server (where only knowledgeable staff are likely to interact with it), it is particularly important when migrating over to OSS desktop software. Often, users are more accustomed to traditionally-popular closed-source software packages, and may have little familiarity with OSS. Organizations which have made the switch to OSS desktop applications identify several helpful lessons learned and best practices. ([source](https://www.igi-global.com/chapter/migration-public-administrations-towards-open/10088))

##### Analysis and Preparation

- Analyze and plan the costs and business cases for the migration;
- Conduct pilot studies.

##### Migration

- Moderate the pace of migration, avoiding a “big bang” approach (e.g., first institute voluntary adoption to cultivate a base of experienced users who can then assist their colleagues);
- Provide a transition phase where users have access to both existing software and the open source alternative;
- Secure the support of top management;
- Create a positive attitude with users.

##### Training

- Provide proper training and focus on the general everyday functionalities of the software.

##### Support

- Provide access to several kinds of support, such as FAQs and guides, access to telephone and email support, and access to a contact person.

##### Format conversion

- Make a significant effort to ensure that file and data formats from the incumbent closed-source software can be easily imported and exported by the OSS solution;
- Keep in mind that document conversion, such as between MS Office and LibreOffice, can become a labour-intensive task for any complex documents, especially where they include precise formatting or MS Office macros.

##### Functionality

- Although the general functionalities are often equivalent in the OSS analogues, there is not always a direct alignment of feature sets and specific issues may arise for users.

#### Legal Risk Management

Overall, the particular OSS licence is unlikely to strongly impact a decision on whether or not to use OSS. As previously noted, few licence obligations engage upon the mere use of OSS. Most importantly, reciprocal licensing obligations do not apply. Only three features of OSS licences tend to strongly differ from closed-source licences in this context and merit special consideration: (1) the lack of a warranty; (2) the disclaimer of liability and lack of indemnification; and (3) the lack of choice of law and choice of forum clauses.

For more details on legal risk management and other legal issues, see: [Annex A - Legal](9_Annex_Legal.md)

#### Interoperability and Licence Alignment

Licence interoperability is rarely an issue for mere OSS use, as long as there is no distribution of the software. As previously discussed, generally the only licence obligations that one must accept and follow in the case of mere use are a disclaimer of warranty and disclaimer of liability. Even when software from multiple sources is modified and combined under multiple licences, these disclaimers are never likely to conflict. Disclaimers impose only a passive obligation – that is, they do not require you to take any particular action or forebear from any particular action. A licensee need only accept the legal risk imposed.

Although licence interoperability is not a concern for OSS use, format and data interoperability can affect decisions on whether or not to use OSS. To assess the interoperability of data, it is important to conduct a case-by-case analysis. Closed-source software can still implement widely-interoperable “open standards” for data. By the same token, OSS may in some cases use specialized non published and non-open standards for storing data.

However, cultural tendencies and the dynamics of the OSS business model tend to drive OSS projects towards the use of interoperable and [Open Standards](2_Open_Standards.md) for reading, writing and storing data. Indeed, even where OSS does not implement an open standard for data interchange, at the very least the availability of the source code always provides an “open implementation”. The source code serves as an example that anyone else can follow to implement the same functionality for reading and writing the underlying data format.

### Contributing to Open Source Software

See [Open Source Code](4_Open_Source_Code.md).

### Preferred Open Source Software

The criteria used for evaluating OSS are defined above in the [Software Evaluation and Procurement](#software-evaluation-and-procurement) section. Preferred OSS must also support the use of [Open Standards](2_Open_Standards.md).

To achieve maximum benefits both economically and in terms of quality, OSS should be used in a concerted and coordinated manner. A list of preferred OSS will be maintained by the Enterprise Architecture Review Board (EARB) at TBS based on solutions assessments departments present. This list is not an obstacle to innovation or testing of new solutions, which can help the evolution of the list. On the other hand it defines OSS to privilege and with time will indicates the OSS to give up. It thus participates in the gradual convergence of OSS use and promotes a culture of collaboration between departments and agencies, but also with OSS communities. As such, it must be integrated into the IM-IT strategic plans of departments and agencies and taken into account during new developments, purchases, upgrades or migrations.

### Examples

#### US

- [Digital Services Playbook](https://playbook.cio.gov/) - Contract ensures open source solutions are evaluated when technology choices are made and consider OSS solutions at every layer of the stack.
- [18F Open Source Policy](https://github.com/18F/open-source-policy/blob/master/policy.md) - Use OSS in our projects and contribute back to the open source community.
- [DoD Open Source Software FAQ](http://dodcio.defense.gov/Open-Source-Software-FAQ/) - Educational resource for government employees and government contractors to understand the policies and legal issues relating to the use of OSS in the DoD.
- [DoD Memorandum on Guidance Regarding Open Source Software](http://dodcio.defense.gov/Portals/0/Documents/OSSFAQ/2009OSS.pdf) - There have been misconceptions and misinterpretations of the existing laws, policies and regulations that deal with software and apply to OSS, that have hampered effective DoD use and development of OSS.

#### UK

- [Technology Code of Practice](https://www.gov.uk/government/publications/technology-code-of-practice/technology-code-of-practice) - Make things open by giving equal consideration to free or open source software when you choose technology - taking account of the total cost of ownership of the service, including exit and transition costs.

#### France

- France has a list of recommended OSS in it's [Socle interministériel des logiciels libres](http://references.modernisation.gouv.fr/socle-logiciels-libres). It's been updated every year since 2012 and covers OSS for workstations, servers, databases and development environments.

#### Australia

- [Australian Government Open Source Software Policy](http://www.finance.gov.au/sites/default/files/australian-government-open-source-software-policy-2013.pdf) - Procurement processes must actively and fairly consider all types of available software. Agencies will actively participate in OSS communities and contribute back where appropriate.

#### Canada

Examples of the GC’s continuous utilization of open source software (OSS) can be found in Environment Canada’s weather infrastructure, TBS’s Government of Canada 2.0 tools (i.e. GCpedia and GCconnex), the [Open Government Portal](open.canada.ca), as well as in multiple departments openly contributing to the Web Experience Toolkit OSS project on GitHub. ([Source](http://www.ssc-spc.gc.ca/pages/itir-triti/itir-triti-afac-271115-pres1-eng.html)) Although prevalent, there has been little done to update GC policies, governance, funding and processes to ensure that open source tools are being used at the right place and at the right time. Moreover, a need exists to ensure that OSS is supported in a sustainable way and that there is appropriate policy and guidance for employees.

This whitepaper aims to assess the GC’s current use of OSS tools, programs and activities. It also aims to identify current gaps to outline a path forward in creating a more complete open environment.

- [Natural Resources Canada Free and Open Source Software Licensing Primer](http://ftp.maps.canada.ca/pub/nrcan_rncan/publications/ess_sst/295/295663/cgdi_ip_33_e.pdf)
