# Security Notice

## What?

This is the security notice for all Government Digital Service (GDS) `alphagov` repositories. The notice explains how vulnerabilities should be reported to GDS. There are cyber security and information assurance teams, as well as security-conscious people within the programmes, that assess and triage all reported vulnerabilities.

## Reporting a Vulnerability

GDS are advocates of responsible vulnerability disclosure. If you’ve found a vulnerability, great! We would like to know so we can fix it.

- If you believe a vulnerability affects the data (release of sensitive data or personal identifiable information) of a system: 
  - Send details to [disclosure@digital.cabinet-office.gov.uk], include:
    - the website, page or repository where the vulnerability can be observed
    - a brief description of the type of vulnerability and any related [OWASP category]
    - non-destructive exploitation details
  - Prefix your subject with `[Vulnerability]`
  - GDS use ZenDesk as a ticketing system, so you may get a reply or response from that platform


- For all other vulnerabilities, you can leave an issue against the repository:
  - (if you are not sure about which repository to raise an issue against, you can still email details through to [disclosure@digital.cabinet-office.gov.uk])
  - Prefix the issue title with `[Vulnerability]`
  - Label the issue `vulnerability`
  - Add details to the issue about the impact and any related [OWASP category]
  - Don’t include detailed exploitation steps publically, GDS may respond in the issue's comments or contact you via your GitHub profile (alternatively, you can leave other contact means)

## Bug bounty
Unfortunately, GDS doesn't offer a paid bug bounty programme. GDS will make efforts to show appreciation to people who take the time and effort to disclose vulnerabilities responsibly.

# Code of Conduct

GDS have a contributors code of conduct, which you can find here: [CODE_OF_CONDUCT.md]

[disclosure@digital.cabinet-office.gov.uk]: mailto:disclosure@digital.cabinet-office.gov.uk
[CODE_OF_CONDUCT.md]: ./CODE_OF_CONDUCT.md
[OWASP category]: https://www.owasp.org/index.php/Category:OWASP_Top_Ten_2017_Project
