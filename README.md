# DomainBL - Domain BlockList

What is DomainBL?
* A periodically updated list of malicious domains observed on a given day.
* We create two lists
  * ApexBL - malicious apex domains
  * PublicBL - malicious full qualified domains hosted on public hosting domains

How do we create DomainBL?
* We utilize state of the art ML/AI technologies to identify malicious domains.

Why malicious domains instead of malicious URLs?
* Most of the blocklists out there focus on malicious URLs, but our goal is one step beyond to provide better protection by identifying malicious domains (i.e. domains created by attackers to launch attacks) with minimal collerateral damage (i.e. malicious domains due to benign domains being compromised). Knowing such domains makes the blocking easier as all future URLs under the same domains are blocked.

Who can use these malicious domains?
* We make them available for non-commercial consumption. Please contact us if you'd like to have premimum access with a fee.

Please add the following citation if you are utilizing this feed for your research:
```
@misc {domainbl,
  title = {DomainBL: A Proactive Malicious Domain Blocklist},
  author = {Mohamed Nabeel},
  year = {2022},
  url = {https://github.com/nabeelxy/domainBL}
}
```
