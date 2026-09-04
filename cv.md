# Professional Experience

## Utah Broadband - Senior Systems Engineer

I joined Utah Broadband as the sole Systems Engineer for AireBeam Fiber Internet, a sister company delivering *high-speed fixed wireless internet* to over 8,000 underserved rural households. This role covered system administration, network engineering, and security compliance needs typical for **Small and Medium Businesses (SMBs)**.

My *primary responsibility* was supporting the Network Engineers, who were ultimately responsible for *customer and employee support*. This included reviewing RADIUS logs, deciphering MySQL schemas, writing utilities to automate common networking tasks, rebuilding aging servers with configuration management, and creating redundancy within budget constraints.

My most significant project was deploying a robust virtualization cluster. The entire infrastructure was failing without any budget for repair, making capacity planning exceptionally difficult. Using clearly defined capacity requirements, I worked with an external vendor who provided a single-socket server that outperformed our dual-socket plan, *reducing hardware and electricity costs by over 30%*. I collaborated with the Finance team to build an asset depreciation plan to ensure we have budget for future needs.

<br>
<br>
Rather than lifting existing servers into the new cluster, the migration became a full rebuild that placed every server under configuration management. This also *resolved many long-standing security issues* previously deferred due to technical debt and resource constraints. After one year, only three servers remained to be migrated, blocked by the expectation of customer-visible outages and the need for further network changes before proceeding.

**System Administration:**

* Supported the Network Engineers as an escalation path for difficult customer and employee issues
* Deployed **Ansible** to adopt and manage all servers, enabling centralized configuration and audits
* Announced every **Git** commit in **Slack**, giving all engineers visibility into infrastructure changes
* Rebuilt many servers that were too old or fragile, making regular server updates possible
* Placed all but three servers under configuration management, deferring those needing planned outages
* Established a routine of **regular software updates**, providing windows of potential outages
* Created a company-wide **knowledge base** that included all known issues and standard processes
* Regularly reviewed **backup logs** and tested restoration, verifying the quality of documentation
* Examined all **server logs** and **alerts** daily, promptly addressing any irregularities
* Separated **DNS** into public and private zones, removing private records from public view
* Wrote **health check** scripts that automatically repaired issues and notified administrators
* Automated **health checks** and automatic recovery for known issues, reducing manual intervention
* Implemented **proactive monitoring** to catch problems before they impacted business services
* Created **runbooks** documenting common failure scenarios and automated recovery procedures

**Data Center Operations:**

* Rolled back an incomplete attempt to introduce a second data center, reducing architecture complexity
* Coordinated with **remote hands** to review existing hardware, removing unused servers and VPN devices
* Reviewed **capacity requirements** and made recommendations for a new virtualization cluster
* Worked with an external **vendor** to specify hardware that cut purchase and power costs by over 30%
* Built an asset depreciation plan with the **Finance** team, protecting budget for future refreshes
* Deployed and tested a three-node **Proxmox** cluster, providing resiliency against potential failures
* Restructured **NetApp** storage, ensuring backup capacity will be exhausted prior to critical storage
* Recovered from a catastrophic storage outage, diagnosed **root cause**, and implemented a permanent fix

**Security & Compliance:**

* Created a **security policy** for servers that balanced best practices against usability
* Wrote **automated tests** to ensure all configuration changes adhered to security standards
* Resolved long-standing security issues that had been deferred due to technical debt and tight budgets
* Consolidated various "engineering" servers onto a single device with strict **access controls**
* Enforced **user management**, revoking any account that was not documented and approved
* Deployed LLNG **SSO** that merged O365 and Google accounts, enabling migration to on-site AD
* Implemented **Active Directory**, allowing the creation of much-needed user management utilities

**Network Administration:**

* Created an Ansible project for network engineers, encouraging normalized switch configurations
* **Trained** network engineers to effectively use Ansible in a Git-based workflow
* Migrated switch backups to **version-controlled snapshots**, replacing a faulty backup process
* Maintained **RADIUS** services used for authenticating network devices and network engineers
* Reviewed **RADIUS** logs to trace authentication failures reported by the network engineers
* Analyzed **packet captures** in **Wireshark**, supporting engineers through difficult troubleshooting
* Configured **host-level firewall**, improving security enough to support a complete network rebuild

**Software Development:**

* Wrote utilities that automated common networking tasks, removing repetition from daily operations
* Deciphered undocumented **MySQL** schemas to answer questions raised by the network engineers

## Volkswagen Group of America - Linux Desktop Engineer

I was contracted as the sole engineer on this project, designing and implementing a **Linux Endpoint** for developers who were creating autonomous driving software at Volkswagen Group of America for brands that included Volkswagen, Audi, Porsche, Bentley, Lamborghini, and Bugatti.

This project required identifying key stakeholders and *balancing competing priorities* from international teams, particularly between security and development departments. By researching company policies and sitting alongside developers, I created a **project plan** that addressed all collected requirements and guaranteed that all concerns would be addressed before completion---creating a solution that improved the experience enough to make developers excited to adopt a solution that met all corporate security policies.

The final laptop image was fully automated and secure, supporting self-service provisioning and recovery, secure boot with Nvidia GPUs, full-disk encryption with employee smartcards, and automated updates integrated with existing **Change Control** processes. This *replaced a fleet of one-off developer builds* that nobody was able to reproduce or support.

At the conclusion of this project, documentation and support were handed off to internal IT teams for ongoing support and maintenance. This included training sessions for support staff, documentation for end-users, escalation procedures for complex issues, and project documentation ready to present to the international Volkswagen Group.

**Business Analysis & ITIL:**

* Researched affiliates to identify all potential stakeholders and investigated any potential overlap
* Balanced competing priorities between international security and development departments
* Sat alongside developers to observe daily workflows, capturing needs that written policy missed
* Collected corporate **security policies** and **developer requirements** into a comprehensive project plan
* Collaborated with stakeholders to identify and document specific security exceptions for AI/ML teams
* Designed a **layered authentication system** supporting regular employee access and privileged recovery
* Coordinated with Support team Leads to provide support documentation, training, and escalation procedures
* Architected a fully automated **endpoint installer**, enabling both initial provisioning and remote rebuild
* Used a staged provisioning process to provide **ready-to-use endpoints** for new hires and contractors
* Worked with the Graphic Design team to create custom **branding** and **themes** for improved user experience
* Improved the endpoint experience enough that developers were eager to adopt a locked-down build
* Created **boot-time messages** to provide clear instructions, reduce information overload, and guide recovery
* Provided **documentation** and **training** to the Call Center team, enabling company-wide support for Linux
* **Integrated support** into the OS, providing instructions that exactly matched *call center scripts*
* Acted as the final escalation point for Linux endpoints throughout the life of the project
* Handed off documentation and ongoing support to internal IT teams at the conclusion of the project
* Prepared project documentation for presentation to the international **Volkswagen Group**

**Software Development:**

* Created a **self-service application**, letting end-users modify and repair their devices without IT assistance
* Customized **bootloader and login themes** to provide a comfortable and branded user experience
* Developed a **boot-time recovery** system to repair common mistakes or even initiate full reinstallation
* Wrote **User documentation** guiding developers through Linux basics, team resources, and AI engineering
* Delivered documentation using a **Static Website Generator**, ensuring fast and reliable access on every device
* Encouraged developers to contribute changes, giving some development teams their first **knowledge base**

**System Administration:**

* Engineered **Linux Endpoint** solution for 50+ AI developers that complied with corporate security policies
* Replaced a fleet of unreproducible one-off developer builds with a single **supportable image**
* Developed an **automated installer** that built fully configured and secure endpoints
* Enforced **secure boot** with Nvidia GPU support, enabling trusted execution of AI/ML workloads
* Integrated **automatic system updates** with existing Change Control processes, using test cycles for stability
* Extended **centralized logging** to include endpoints, improving troubleshooting and auditing capabilities
* Created **log alerts** to proactively notify users and support staff of potential issues

**Security & Compliance:**

* Implemented **full-disk encryption** using LUKS with PKI smartcards and rotating backup keys
* Generated **unique rotating recovery keys** using device tokens, enabling support for lost smartcards
* Worked with the System Administration team to build an Active Directory proxy for user authentication
* Built **automated compliance tests**, ensuring every endpoint adhered to corporate security policies
* Automatically revoked **Device Posture Checks** when certain actions were performed, requiring config sync
* Integrated **antivirus** and **DLP** software, working with the Security team to improve performance

## Basis Technologies - Database Administrator / Site Reliability Engineer

I was hired as a Site Reliability Engineer on the Database Operations team to maintain **Big Data** infrastructure supporting *Advertising Technology*. My three-person team handled MySQL and Hadoop clusters that processed *millions of transactions per minute*, demanding sub-millisecond response times and near-perfect uptime.

This required an in-depth understanding of the bid process, MySQL transactions, meticulous planning, and rigorous testing to ensure that any updates did not negatively impact overall database performance.

My most significant contribution came during a **catastrophic incident** in which a planned code update triggered a rare **MySQL** bug and the resulting database outage cascaded to backup servers, halting revenue generation entirely. Restoring from backup would have taken over 30 days. In response, I established a new **incident response** process using active-research cycles. In this approach, one team member oversaw the recovery effort, while others investigated the root cause and developed a long-term repair plan. At the end of each cycle, the team met to discuss findings, plan next steps, and hand off recovery duties to another team member.

Using this approach, we were able to maintain *non-stop recovery efforts without exhaustion* while simultaneously experimenting with alternative recovery methods. This allowed us to quickly pivot when a promising new method was discovered, and was ultimately responsible for reducing downtime from multiple days to under 12 hours, saving *over $800,000 per day* in lost revenue. This incident also drove a new backup process that cut worst-case recovery from over 30 days to *a single hour*.

**Database Administration:**

* Supported **big data infrastructure** and daily operations, including MySQL clusters and Hadoop environments
* Maintained sub-millisecond response times across clusters processing millions of transactions per minute
* Studied the **bid process** and MySQL transaction behavior to predict the impact of every change
* Created a **documentation website** that replaced scattered notes, improving discoverability and overall quality
* Improved documentation based on external feedback, improving speed and quality of incident response
* Monitored **system performance** and resource utilization, with close attention to specific high-load queries
* Analyzed **database performance** metrics to ensure optimal settings were in place for production workloads

**Incident Response:**

* Detected early signs of **critical incidents** while on-call and maintained logs for **root cause analysis**
* Coordinated team efforts during high-severity incidents, using active-research cycles to maintain momentum
* Rotated recovery duties at the end of each cycle, sustaining effort without exhausting the team
* Tested alternative recovery methods in parallel, pivoting quickly whenever a faster path was found
* Cut a multi-day outage to under 12 hours, saving over $800,000 per day in lost revenue
* Established a new **backup process**, reducing worst-case recovery time from over 30 days to a single hour

**Server Administration:**

* Maintained **Linux servers** running MySQL and Hadoop, thoroughly testing all changes prior to deployment
* Reviewed system logs, performed regular updates, and ensured backups were successfully completed
* Automated **routine maintenance tasks**, reducing manual effort and eliminating common mistakes
* Reviewed incidents and logs to develop improved **monitoring checks**, reducing time to detection
* Wrote **documentation** to guide team members through common maintenance and troubleshooting tasks
* Created a **CI/CD pipeline** to automatically test and deploy every configuration change
* Authored Pull Requests to create an informal **change control process**, improving cross-team communication

## Limelight Networks - Systems Engineer

My role at Limelight Networks, a *CDN provider*, began with improving their **configuration management** and assisting with standard system administration activities.

Following a series of organizational restructures, my focus became ensuring the regular rotation of passwords for all service accounts. This involved auditing existing scripts to identify hard-coded values and monitoring system logs to track active usernames.

**System Administration:**

* Assisted with daily system administration activities, including updates, monitoring, and issue resolution
* Created Ubuntu 20.04 templates used for manual testing, beginning plans to migrate all servers
* Updated SaltStack configuration and scripts to support Python 3, enabling management of new servers
* Reviewed SaltStack customizations and provided patches to remove legacy bugs and improve stability
* Refactored a custom Salt-Bootstrap script to improve maintainability and reliability
* Reviewed system logs and configuration to identify and report all currently active service accounts
* Audited existing scripts to locate hard-coded credentials that would break during password rotation
* Regularly rotated passwords for all service accounts, ensuring compliance with security policies

## Taos Mountain - Senior DevOps Consultant

Most of my time was spent providing *DevOps services to diverse clients*, with a focus on **automation and hardening**. Placements were typically *rescue engagements*\-\-\-clients called Taos in after something had already gone wrong\, whether a network needing to be hardened after a cyberattack or a program that was weeks from cancellation\. When things were slower\, I assisted with various internal company projects\.

**Internal Operations:**

* Assisted with various internal company projects between client placements
* Conducted "Technical Interviews" of fellow consultants as part of regular career growth evaluations
* Wrote company website articles focusing on the safe application of strong security standards

## Juniper Networks - Senior DevOps Consultant

I joined Juniper Networks, a multinational networking products corporation, as part of an established team of 22 Taos consultants tasked with building a **custom configuration management** solution, based on **Ansible**, for a fleet of more than 30,000 servers. I was initially responsible for guiding junior engineers through manual testing, but quickly began resolving bugs and improving the success rate of these system hardening scripts.

My most impactful contribution required deep troubleshooting skills to identify the root cause of frequent remediation failures that had left the program *weeks from cancellation*. Using a cloned VM and careful analysis of logs, I identified several underlying issues causing the remediation process to fail.

This **root cause analysis** allowed me to write patches that proactively resolved bugs, along with **Ansible** tasks that applied system-wide fixes, dropping the failure rate from *over 90% to only one* for the remainder of my tenure---transforming a failing project into a successful solution that met all security and compliance requirements.

Gaining a deep understanding of the environment and the custom solution allowed me to build robust testing processes that prevented common regressions. This included writing integration tests that tried to reproduce known failure scenarios, ensuring that any future changes would not reintroduce previously resolved issues.

**Business Analysis:**

* Gathered requirements from internal IT staff to improve a custom system hardening solution
* Worked with multiple security teams to gain access to a VM that could reliably reproduce failures

**System Administration:**

* Followed manual package testing procedures to prevent regression in custom configuration packages
* Guided junior engineers through manual testing, ensuring consistent and repeatable results
* Analyzed logs on a cloned VM to identify the root causes behind frequent remediation failures
* Wrote patches to resolve bugs in the custom management solution, resolving over 90% of remediation failures
* Wrote **Ansible** tasks with system-wide fixes, reducing failures to one across a fleet of 30,000+ servers
* Resolved performance issues in configuration scripts, eliminating over 80% of employee wait time
* Assisted in the development of CI/CD pipelines to automatically test all changes and prevent regressions
* Continued supporting regular system administration tasks after the remaining Taos team was disbanded

**Software Development:**

* Wrote a script to search user directories for **insecure SSH keys**, ensuring compliance with security policies
* Updated key scanning script to support edge cases and **parallel execution**, enabling timely completion of scans
* Wrote **integration tests** reproducing known failure scenarios, preventing regression of resolved bugs

## Suitable Technologies - Senior DevOps Consultant

At Suitable Technologies, I supported telepresence robots for both business and personal use. I replaced another Taos consultant who was falling short of expectations, thanks to my deep knowledge of **SaltStack** and **Linux internals**, as well as my ability to work effectively with demanding clients. My focus was modernizing infrastructure, reducing security risks, and adding redundancy to the servers that powered customer-facing services.

One of my most impactful contributions began when I was tasked with reviewing and updating a patch for a custom user authentication mechanism in Jabberd2. This patch was preventing a much-needed upgrade that was ten years overdue. After rewriting the patch in **C**, I created a custom **Debian package** that supported multiple TLS versions, enabling a *seamless upgrade* to new services. Completing the upgrade also required rewriting the internal **message queue** to add support for directional replies.

During this upgrade, I uncovered serious performance issues that led to the discovery of a critical configuration vulnerability, allowing user authentication to be bypassed entirely---the authentication backend had been deliberately configured to skip authentication, simply to survive production load. Resolving this required carefully reviewing the entire authentication stack and *cloning a Django token mechanism into the Jabberd2 plugin*, providing an effective cache. This cache dramatically improved authentication performance and even allowed the system to resist **Denial of Service (DoS)** attacks.

To further improve resiliency, I later revised this new cache from an in-memory **Python** dictionary to **Redis**. This provided redundancy and improved performance, ensuring that the authentication cache was instantly available during server restarts or fail-overs. With the upgrade complete and years of security debt closed, I was finally able to turn their primary product into a *highly-available service*.

**System Administration:**

* Maintained the customer-facing services powering **telepresence robots** for business and personal use
* Added redundancy to customer-facing servers, removing single points of failure from the platform
* Upgraded services that were as much as ten years out of date, closing years of security debt
* Resolved performance issues in SaltStack configuration, reducing execution time from **hours to minutes**
* Refactored management of secret keys, preventing information leakage and improving server scalability
* Constructed a new backup solution based on least-access principles, removing the use of root SSH keys
* Designed a deployment process that ensured users needed to call into support for an initial password
* Wrote scripts to automate regular system administration tasks, reducing manual effort and errors
* Converted the company's primary product into a **highly-available** service after clearing the blocked upgrade

**Security & Compliance:**

* Discovered and resolved a critical zero-day vulnerability that allowed bypass of user authentication
* Reviewed the entire **authentication** stack to restore enforcement without breaking production load
* Reviewed server configuration files to identify and resolve security vulnerabilities

**Software Development:**

* Refactored a custom authentication patch for Jabberd2, enabling a 10-year-overdue upgrade
* Built a multi-binary Debian package for Jabberd2, enabling TLS 1.2 support and a seamless upgrade
* Rewrote the internal **message queue** to support directional replies, unblocking the Jabberd2 upgrade
* Cloned a **Django** token mechanism into the Jabberd2 plugin, providing a proven caching design
* Designed and implemented an **in-memory cache** to improve authentication performance, preventing DoS
* Replaced an in-memory cache with a **Redis**-backed solution, improving redundancy and startup performance

## Sony Pictures Entertainment - Senior DevOps Consultant

My team was brought into Sony Pictures Entertainment, a multinational media and entertainment corporation, to assist with a **major security cleanup** effort following a devastating cyberattack. Although I was part of a larger team of Taos consultants, my primary responsibility was to assist with system hardening and automation for an air-gapped subsidiary network.

My most significant contribution was reviewing **CIS Level 2** benchmarks for Linux servers and creating automated solutions to *enforce selected policies*. This included writing **Chef recipes** to apply selected recommendations, as well as testing and validating each change. This hardening was later converted to a single **shell script** that could be run on any *server or container image*.

**System Administration:**

* Provided system hardening and automation for an **air-gapped** subsidiary network
* Supported standard system administration activities, including patching, updates, and issue resolution
* Deployed and maintained a **RHEL Satellite** server for repository mirroring and client license management
* Automated **Satellite** deployment and configuration, ensuring all servers could be regularly rebuilt
* Developed comprehensive **Chef recipes** to enforce security recommendations across production servers
* Converted the hardening recipes into a single **shell script** usable on any server or container image
* Thoroughly **tested** and validated policy changes to ensure zero negative impact on production workloads

**Security & Compliance:**

* Contributed to a company-wide **security cleanup** following a devastating cyberattack
* Reviewed **CIS Level 2** benchmarks for Linux servers and implemented every recommendation
* Documented every **policy** change, providing clear justification for any deviations from CIS recommendations

## Good Samaritan Society - Senior Systems Administrator (SRE)

As the sole Linux administrator for the nation's largest not-for-profit long-term healthcare provider, I supported over 10,000 employees across corporate offices, over 300 remote Skilled Nursing Facilities, and many more branch sites. My primary responsibility was maintaining *over 400 Linux servers* and all the applications they ran. This included email, print, file, and remote "boothost" servers.

My most significant contributions came from supporting employees at remote facilities, where I developed a deep understanding of the unique challenges faced by the nursing staff who were directly caring for patients. By focusing on their frustrations, I was able to design and deliver meaningful improvements that removed obstacles from their workflows.

I was extremely fortunate to work in an environment that encouraged *deep learning and creative problem-solving*, giving me the freedom to keep challenging *user-reported tickets* open and to chase down **root causes** until I was satisfied that the problem was permanently resolved.

**System Administration:**

* Introduced to this environment with a database service that was days from complete failure
* Assisted with management and troubleshooting of over 200 Windows and 50 AIX servers
* Automated server deployment and rebuilt all servers, providing fully configured remote servers
* Provided life support for over 150 remote servers running in harsh conditions (smoke, flood, etc.)
* Created a fully automated ESXi deployment system with auto-deployed and encrypted guests
* Connected remote servers to the monitoring system, gaining insight into previously unknown failures
* Prepared and shipped replacement servers, allowing planned outages that saved $400 per incident
* Introduced **configuration management**, enabling the rollout of standardized configuration
* Performed regular **patching** and updates across all Linux servers, minimizing facility disruption
* Maintained **email** and file servers used daily by corporate offices and remote facilities
* Maintained a centralized **print server** used to send special reports to remote line-feed printers
* Restored files from backup on request, prior to automating the process for end users
* Optimized scripts for efficiency, improving execution time from days (or weeks) to hours.
* Provided critical support during many migrations, including MS AD, Exchange, XIV, hardware refresh, etc.
* Worked closely with the network team to resolve countless network issues affecting remote facilities

**Incident Response:**

* Took over for a coworker when a NetWare failure took down the company file server, focusing on recovery
* Identified critical business units and **brought teams together** for a coordinated recovery effort
* Prioritized restoring business function during outages, investigating **root cause** afterward

**Security & Compliance:**

* Maintained server configuration and access controls that satisfied **HIPAA** requirements
* Managed McAfee Web Gateways and Web Reporter, which were responsible for internet security
* Utilized **Active Directory** deployment to automate certificate trust, enabling Data Loss Protection
* Replaced network authentication with **NTLMv2**, eliminating additional login requirements

**Support & ITIL:**

* Supported remote "boothost" servers that were used to facilitate employee access to the corporate network
* Gained enough knowledge to provide basic support for all applications used at every remote facility
* Provided an extra tier of support for other teams, ensuring all employee-facing issues were solved
* Kept challenging **user-reported tickets** open until the root cause was permanently resolved
* Studied the daily workflows of nursing staff, removing obstacles that interfered with patient care
* Wrote documentation to guide support staff through recurring issues, improving first-call resolution
* Established regular meetings with call center managers, permanently resolving some common problems

**Software Development:**

* Created a custom DCIM/IPAM website, replacing a slow document-based change request process
* Wrote scripts to scrape and parse legacy MS Office documents to extract network device information
* Developed a self-service file-restore application that eliminated hours of manual effort
* Wrote patches to resolve security-related issues in financial and healthcare applications

**Database Management:**

* Deployed and maintained a 5-node multi-master MySQL/MariaDB Galera cluster, replacing a fragile instance
* Planned database servers to reduce split-brain potential, ensuring network hiccups never cause an outage
* Monitored database performance and worked with development teams to optimize queries
* Worked with a database engineer to refine complex queries needed to extract data from a large database

## Kalliki Software - System Administrator / Website Developer

I served as the only system administrator at a small *10-person website development start-up*, while also contributing to the development team as a website developer. My role involved managing all server infrastructure and supporting a small development team.

The most interesting challenges arose from migrating development infrastructure from a basement to a shared office space and finally to a professional data center. Each move required learning about new networking requirements and coordinating with providers to plan a smooth transition.

**Website Development:**

* Migrated websites from WordPress, Joomla, and custom code to Drupal, often removing hidden defacement
* Created custom Drupal modules to address unique customer requirements
* Controlled access to staging websites, offering customer sign-off prior to delivery
* Integrated client approvals with the billing platform (QuickBooks), completely eliminating unpaid bills
* Trained other website developers, with a focus on troubleshooting PHP websites
* Worked closely with graphic designers and external vendors to ensure every custom website was doable

**Business Analysis:**

* Attended customer meetings involving custom module development, enabling immediate acceptance of quotes
* Provided a clean transition when the company was sold to a competitor

**Business Development:**

* Absorbed the graphic design team into my development team, improving product quality and turnaround time
* Interviewed prospective employees using sprint-style tasks designed to focus on feedback-driven development
* Set up and managed Mailman mailing lists that were used for internal and external communication

**System Administration:**

* Designed and implemented a secure, scalable Nginx+PHP stack, hosting over 50 isolated client websites
* Monitored system logs and resource usage to automatically notify administrators of potential issues
* Daily review of system logs to ensure no users have logged into production servers
* Wrote CI/CD pipelines that automatically tested and deployed server configuration changes and OS updates
* Maintained development and staging environments used daily by the development team
* Designed, implemented, and validated disaster recovery procedures
* Regularly updated all servers and workstations

**Network Administration:**

* Migrated development infrastructure from a basement to shared office space and then a data center
* Planned each relocation with providers, learning the networking requirements of every new site
* Coordinated with building network engineers, maintaining a zone for secure internal development

## Secure Banking Solutions - Application Developer

I developed specialized software for auditors conducting risk assessments and penetration tests for financial institutions. My most significant contribution was a script that converted Nessus results into a final device report.

**Software Development:**

* Built tools for auditors performing risk assessments and penetration tests at financial institutions
* Wrote a script that converted Nessus scan results into a final per-device report
* Automated generation of penetration test reports, eliminating over 40 hours of effort per report
* Contributed to the Technology Risk Assessment Calculator (TRAC) utility, used to complete audits
* Developed the first web-based version of TRAC, eliminating many customer-visible performance issues
* Created a USB-based phishing utility that enabled auditors to safely identify users needing additional training
* Wrote a mailing list plugin for the company website that yielded a \~20% increase in customer response rate

**System Administration:**

* Introduced virtualization in order to provide virtual workspaces to pen testers using spare resources
* Rebuilt BackTrack servers with Debian, removing many well-known internal security concerns
* Performed regular OS and software updates to ensure the latest security patches were applied

# Home Laboratory

Further details and a *Network Diagram* are available at *https://michael.lustfield.net/homelab*.

My home lab was born from a need to **test major changes** in a workplace where no test environment was currently available. This lab was treated like an enterprise environment and evolved into a full-scale, **hybrid (multi-cloud) deployment** with redundant services used by various open-source projects.

* Began with just **pfSense** and **Proxmox**, to test upgrading remote hardware from **Debian** 4 to 6
* Utilized **VLANs** and **Subnets** to replicate multiple remote facilities connected to a Central Office
* Throttled bandwidth to **replicate real-world lag** introduced by T1 network connections
* Added Cisco switch (iOS) to learn about **Link Aggregation (LAGG)** and investigate workplace challenges
* Migrated to MikroTik switches and added hardware to support a **fully redundant stack**, with fail-over ISP
* Created an **Out-of-Band** management device using a cellular modem to guarantee remote access
* Introduced **IPv6** to specific VLANs, enabling access to certain websites prior to ISP support for IPv6
* Secured access to VLANs using **bastion hosts** that required "SSH key + password + 2FA"
* Experimented with all available **Configuration Management** solutions, including home-grown scripts
* Implemented every **security standard** that could be found, evaluating for efficacy and usability
* Introduced all changes (and deployments) using **SaltStack** after **CI/CD** (automatic tests) passed
* Wrote thousands of **unit and integration tests** to provide the best chance of a successful update
* Re-deployed infrastructure from scratch, ensuring the entire stack (**metal to cloud**) can be automatically rebuilt
* Expanded infrastructure to **cloud** platforms, using **VLANs** and **VPN** to maintain tight security
* Utilized Netbox for **DCIM/IPAM** (Data Center Inventory Management / IP Address Management)
* Updated the environment via **Git** and **Netbox**, with **Salt** responsible for actual modification
* Backed up data to **AWS Glacier** using **GPG** for fully encrypted backups and **SquashFS** for space efficiency
* Managed personal and family devices using **automation**, gaining candid opinions on **usability**

# Certifications

My primary drive for pursuing certifications is to meet employment and volunteer requirements. In my free time, I prefer to focus on learning new skills and technologies through hands-on experience.

* **SSCE** (SaltStack Certified Engineer) [Record ID: [710C6EC7](https://ssc.saltstack.com/)]
* **GCP - Professional Cloud Architect** (Google Cloud Platform) [Record ID: [xuB2dH](https://www.credential.net/k315bwjm)]
* **CITI - Cancer GCP** (Good Clinical Practice) [Record ID: [46454315](https://www.citiprogram.org/verify/?w14434623-225d-451c-9b98-1d8894ae6658-46454315)]
* **CITI - Investigators HSR** (Investigator Health Science Research) [Record ID: [46454316](https://www.citiprogram.org/verify/?w61a429ad-2988-48e1-a11f-1d0b43737520-46454316)]
* **CITI - IRB HSR** (Institutional Review Board HSR) [Record ID: [46454314](https://www.citiprogram.org/verify/?w2f7881f1-dca7-4bfb-91ff-816694cbff43-46454314)]
* **CITI - Cancer HSR** (Cancer Health Science Research) [Record ID: [46454317](https://www.citiprogram.org/verify/?w263ac87a-5df9-4ab9-b326-19622be3d875-46454317)]

# Presentations

## From Server Chaos to Order with SaltStack, SaltConf15

Presented my experience using SaltStack to tame a chaotic server environment. I covered lessons learned, best practices, and provided practical tips for anyone undertaking a similar project.

# Volunteer Experience

Some of my most meaningful volunteer contributions include:

## Tallgrass Recovery

This nonprofit *helps people recover from substance abuse and addiction*. They offer support and resources, focusing on community outreach, education, and advocacy.

* Mentored individuals in recovery, walking them through the early steps of sobriety
* Presented my personal story, helping others understand the line between bad habits and addiction

## Avera Oncology Institutional Review Board

Avera Oncology provides cancer treatment to patients in several states. Its Institutional Review Board (IRB) oversees clinical research to *ensure patients are informed and protected*.

* Served as a non-scientific/unaffiliated patient-representative
* Also served on Health Science IRB (February 2021 --- April 2023)
* Reviewed studies to ensure human subjects were properly protected (Belmont Report)
* Became familiar with industry standards and regulations (FDA, OHRP, HIPAA, etc.)
* Reviewed patient consent forms for completeness, accuracy, and clarity

## Upper Midwest Great Dane Rescue

This nonprofit rescues, *rehabilitates, and re-homes Great Danes* in need. They also focus on educating people about responsible pet ownership and breed-specific health issues.

* Transported Great Danes hundreds of miles with frequent comfort stops, delivering them to new homes
* Conducted home visits to ensure prospective adopters provided a safe and loving environment
* Visited animals in shelters to provide socialization, exercise, and basic training

## Kids Against Hunger

KAH *packages and ships nutrition-packed dry meals* to struggling communities both locally and internationally, with a focus on teaching children to enjoy helping others.

* Assisted with packaging dry food for international shipment
* Led volunteer pack sessions of 10-80 volunteers, coordinating teams rotating kids through stations
* Unloaded bulk shipments and prepared tables for packing events, ensuring a smooth workflow
* Presented training sessions prior to each event, ensuring all volunteers understood who they were helping
* Assisted more experienced pack leaders with larger events, often taking over for frustrated parents