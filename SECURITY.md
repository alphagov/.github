# Security Notice

## What?

This is the security notice for all GDS (Government Digital Service) repositories. The notice explains how vulnerabilities should be reported to GDS. At GDS there are cyber security and information assurance teams, as well as security-conscious people within the programmes, that assess and triage all reported vulnerabilities.

## Reporting a Vulnerability

GDS is an advocate of responsible vulnerability disclosure. If you’ve found a vulnerability, we would like to know so we can fix it. Quick links can be found at our [security.txt](https://vdp.cabinetoffice.gov.uk/.well-known/security.txt).

You can [report a vulnerability to GDS using HackerOne](https://hackerone.com/44c348eb-e030-4273-b445-d4a2f6f83ba8/embedded_submissions/new), please include:
- the website, page or repository where the vulnerability can be observed
- a brief description of the vulnerability 
- details of the steps we need to take to reproduce the vulnerability
- optionally the type of vulnerability and any related [OWASP category]
- non-destructive exploitation details
- screenshots or logs if you have them

Alternatively, you can send details to [disclosure@digital.cabinet-office.gov.uk]. GDS use ZenDesk as a ticketing system, so you may get a reply or response from that platform.

## Scope
The following are **not** in scope:
- break the law
- access unnecessary or excessive amounts of data
- modify data
- use high-intensity invasive or destructive scanning tools to find vulnerabilities
- try a denial of service - for example overwhelming a service on GOV.UK with a high volume of requests
- disrupt GOV.UK’s services or systems
- tell other people about the vulnerability you have found until we have disclosed it
- social engineer, phish or physically attack our staff or infrastructure
- demand money to disclose a vulnerability

Only submit reports about exploitable vulnerabilities through HackerOne.

If you are not sure, or you have found:
- a non-exploitable vulnerability
- something you think could be improved - for example, missing security headers
- TLS configuration weaknesses - for example weak cipher suite support or the presence of TLS1.0 support

Then you can still [reach out via email](disclosure@digital.cabinet-office.gov.uk) or using the [GOV.UK contact form](https://www.gov.uk/contact/govuk).

## Bug bounty
Unfortunately, GDS doesn't offer a paid bug bounty programme. GDS will make efforts to show appreciation to people who take the time and effort to disclose vulnerabilities responsibly. We do have [an acknowledgements page for legitimate issues found by researchers](https://vdp.cabinetoffice.gov.uk/thanks.txt).

# Code of Conduct

GDS have a contributors code of conduct, which you can find here: [CODE_OF_CONDUCT.md]

---

#### Further reading and inspiration about responsible disclosure and `SECURITY.md`
- <https://www.gov.uk/help/report-vulnerability>
- <https://mojdigital.blog.gov.uk/vulnerability-disclosure-policy/>
- <https://www.ncsc.gov.uk/information/vulnerability-reporting>
- <https://github.com/Trewaters/security-README>

[disclosure@digital.cabinet-office.gov.uk]: mailto:disclosure@digital.cabinet-office.gov.uk
[CODE_OF_CONDUCT.md]: https://github.com/alphagov/.github/blob/master/CODE_OF_CONDUCT.md
[OWASP category]: https://www.owasp.org/index.php/Category:OWASP_Top_Ten_2017_Project
