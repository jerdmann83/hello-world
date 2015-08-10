# Jason Erdmann
> jerdmann83@gmail.com

------

### Skills

* Programming languages:  Python, Ruby, Perl, POSIX shell, less so: C/C++, JavaScript
* Monitoring:  Icinga/Nagios, Graphite, Splunk
* Operating Systems:  Ubuntu 14.x, CentOS 6.x, Windows Server 2003/2008
* Virtualization:  VMWare ESX 3.x/4.x, Oracle VirtualBox
* Deployment Automation:  Chef, Vagrant
* Tools:  vim, tmux, zsh, git, strace, regex

------

### Experience

**Trading Technologies** *TTNET Monitoring Systems Engineer* __2013 to present__
- Designed and implemented a distributed Graphite system for storing and rendering arbitrary application metrics.  Also implemented a client-side script that parses counters from sysstat/sar, and the Grafana front-end for user-driven dashboard creation and improved realtime charting support.
- Designed and implemented a distributed Icinga-based monitoring system that monitors 2200 hosts and 30,000 services across 8 datacenters with zero ongoing maintenance.
- Designed and implemented a client-side services check for the above Icinga system that monitors service state based on the local host configuration, freeing the monitoring team from tedious server-side schedule updates for things like timezone changes, exchange schedule changes, etc.
- Implemented a distributed Splunk system to index various data sources.  Wrote sets of transform rules to parse TT-specific application logs into Splunk-parsable formats for zero-maintenance automatic field extraction.
- Implemented numerous Splunk inputs and dashboards for exposing information on core TT infrastructure, including things like power draw across all bare-metal servers via HP iLO and discards across network interfaces via SNMP.
- Implemented numerous Icinga service checks and handlers for checking various components, including additional summary output to help operations quickly zoom in on problems.
- Designed and implemented a port389 directory server solution for replicating the IT-managed Active Directory environment into all hosted datacenters to provide LDAP logon support for applications and Linux hosts.  Also wrote deployment automation for zero-touch installation and peer configuration, and implemented a public-key replication scheme for passwordless logons.
- Ongoing development and maintenance of Chef cookbooks for monitoring components.  Promoted code modularity and reuse when possible by abstracting certain functionality into modules or providers when appropriate.
- Implemented a deployment script providing simple provisioning of new VMs in a locally-hosted VMWare vCloud Director environment.  This script is used company-wide by various engineering teams to deploy and remove VMs for test/dev purposes.
- Some TT-platform application debugging including components written in C++ and JavaScript.

**Trading Technologies** *IT Senior Systems Administrator* __2010 to 2013__
- Designed and implemented a disk aggregate layout for the corporate NetApp storage arrays, eliminating resource silos and simplifying ongoing maintenance and provisioning.
- Implemented a clustered Exchange 2010 environment, including offsite passive database copies for DR purposes.  Also implemented NetApp snapshot-based backups and Single MailBox Recovery for simple recovery of arbitrary mailboxes and/or items.
- Managed the company migration from Exchange 2010 to Gmail.  Executed the mail migrations themselves, including some linux shell work for automatically detecting mailbox copy/API failures in the output logging.
- Designed and implemented SCOM 2007 for monitoring about 250 Windows servers.  Designed and implemented automation of routine patching of same, saving the department from tedious all-hands weekends.
- Wrote and recorded a series of about 30 training videos covering various IT knowledge areas.  Held live "lunch 'n' learn" sessions and answered questions.

**Trading Technologies** *IT Systems Administrator* __2007 to 2010__
- Monitored 8 discrete VMWare Lab Manager environments used by various engineering teams for test/dev purposes.  Discovered SAN bottleneck issues which ultimately led to the purchase of proper storage hardware.
- Wrote simple health dashboard to collect performance data from Lab Manager environments by programatically scraping the web front-ends.
- Planned and executed a SAN migration strategy to migrate all Windows servers from a legacy HDS storage array to a NetApp one.
- Handled escalation of various incidents from IT support, and in many cases saved an escalation to an engineering team.
- Performed basic network maintenance duties on Juniper firewalls and Cisco iOS-based switches.

**Sterling Network Integration** *Network Engineer* __2006 to 2007__
- Travelled to various client sites to put out fires with zero preparation or knowledge of said client's environment.  Most incidents involved Windows desktops and servers, Active Directory, and miscellaneous peripherals (printers).
- Zero network engineering involved despite the title.

------

### Education
B.S. Computer Engineering - DeVry University Addison IL 2005

------

### Miscellany
Modded my 4-year-old daughter into Pixel Dungeon on Android.  She still prefers the wizard. =/
