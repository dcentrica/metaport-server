<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./metaport-logo-readme.png" />
    <img alt="Metaport Logo" src="./metaport-logo-readme.png" />
  </picture>
</div>

[![Pipeline Status](https://gitlab.com/dcentrica/metaport/metaport-server/badges/master/pipeline.svg?style=flat-square)](https://gitlab.com/dcentrica/metaport/metaport-server/-/pipelines)
[![Latest Release](https://gitlab.com/dcentrica/metaport/metaport-server/-/badges/release.svg?style=flat-square&value_width=80)](https://gitlab.com/dcentrica/metaport/metaport-server/-/releases)
[![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white&style=flat-square)](README.md)
[![phpstan](https://img.shields.io/badge/PHPStan-level%206-brightgreen.svg?style=flat-square)](#)
[![Software License](https://img.shields.io/badge/license-AGPLv3-brightgreen.svg?style=flat-square)](LICENSE)
[![Docs](https://img.shields.io/badge/Docs-brightgreen.svg?style=flat-square)](https://docs.metaport.sh)

# Metaport CE

[Metaport](https://getmetaport.com/) is for web-development teams in **agencies**, **studios**, **government**, and **education** or wherever multiple web-apps are managed.

Development teams deal with the messy reality of maintaining dozens of projects, multiple tech stacks, and multiple hosting solutions without a reliable way of seeing what's about to break or what's at risk **in any of them** from a **maintenance**, **security**, and **C&A** perspective.

 Metaport is the essential **portfolio** and **inventory** management solution your team doesn't yet have. It's well-suited to teams where;

- Multiple client projects, environments, tech stacks, and hosting solutions exist
- Only higher-value projects are connected to AppSec, ASPM, or CSPM tooling
- There's no single place to see all project health

Metaport maps what's actually running across all projects — frameworks, CMSs, OS's, databases, webservers, language runtimes, and SSL certificates — and flags things that are about to turn into problems, such as:

- Dependencies or software products hitting end-of-life (now, **and in the future**)
- Security vulnerabilities affecting multiple projects at once
- Expiring SSL certificates or environment issues

Metaport's value is highlighted in common agency situations:

- "We just found Laravel is EOL on one site — but how many others are also affected?"
- "Why are we only finding out about this now?"
- "We just upgraded DJango for a customer, but which others need the same treatment?"
- "I just got a call from the customer, they're asking why Ubuntu on prod is EOL!"

Most delivery teams are still piecing this together manually — spreadsheets, Google Docs, CRMs, Jira, and developer's memories with arbitrary check-ins — all of which breaks down as soon as the number of managed applications changes.

Metaport provides teams with a continuously updated view across everything, so they can:

- Surface and identify risk across all projects
- Surface and identify repeated issues across environments and across projects
- Plan upgrade work with confidence instead of just reacting to incidents

Metaport's overarching value is to teams. Almost every adjacent product is designed for Engineering or Security or Ops roles. But when communication is key between these traditional silos, then data and timing are everything. If your Project Managers don't have the same information as their engineers, and the engineers don't see what Ops do, the team is effectively spinning its wheels when it should be actioning the work.

The result is fewer surprises, a reduction in firefighting, and a clearer picture of what maintenance work actually needs to happen across portfolios.

Metaport is technology agnostic which means your PHP, Node, Python, or .Net apps can all use it. See more at: [getmetaport.com](https://getmetaport.com/) and checkout the docs at [docs.metaport.sh](https://docs.metaport.sh/).

**Do you work in a delivery team?** [Take our survey](https://getmetaport.us11.list-manage.com/survey?u=50f1fdd65147cfedfbaa69727&id=994b835794) and tell us how you manage maintenance where you work.

<div align="center">
  <p>&nbsp;</p>
  <img src="docs/img/metaport-ecosystem.png" alt="Metaport Ecosystem" />
  <p>&nbsp;</p>
</div>

## Features

* **Multitenant:** Every team and application belongs to an organisational unit
* **Integrations:** [OWASP DependencyTrack](https://dependencytrack.org), [Dependabot](https://dependabot.com), [Jira](https://jira.atlassian.com), [KeyCloak](https://keycloak.org)
* **Technology Agnostic:** Metaport works with your PHP, Node, Python, or .Net apps, and works with Github and Gitlab
* **Role Based Access:** Role-Based Access Control (RBAC) applies distinct roles to your team, so they access only what they should, nothing more
* **Single Sign-on:** Metaport integrates with [KeyCloak](https://keycloak.org/) to provide comprehensive SSO for your organisation
* **Encryption** API keys, tokens and other integration secrets are managed by a secrets manager like Vault or KMS
* **Proactive Planning:** Share lifeycle gantt charts with customers and stakeholders. Import schedules into shared calendars.
* **Portfolio Insights:** Quickly surface components, dependencies and vulnerabilities across **entire application portfolios** <sup>1</sup>
* **Executive Health Report** An executive level report with charts which summarises overall org health
* **Application Health Report** Individual reports summarise recommendations for next steps
* **Birds Eye View:** At-a-glance views into the current maintenance standing of your team's apps
* **Stay Informed:** Custom policies and notifications keeps teams on top of application maintenance of an ever-changing portfolio
* **Open Source:** With Metaport's [open source codebase](https://gitlab.com/dcentrica/metaport/metaport-server), common interfaces, and great docs, it's easy to build new features

## Not keen on managing infra yourself?

Metaport SaaS is now generally available! Pick the most suitable [subscription tier](https://getmetaport.com/pricing/).

* [**Contact us**](https://getmetaport.com/contact/)
* [**Pricing**](https://getmetaport.com/pricing/)

## End User Documentation

See the documentation site at [docs.metaport.sh](https://docs.metaport.sh/)

## Resources

* [Our YouTube channel](https://youtube.com/@metaport)
* [Read our blog](https://blog.metaport.sh/)
* [Our LinkedIn](https://linkedin.com/company/dcentrica)
* [Subscribe to our newsletter](https://confirmsubscription.com/h/y/C8098BBB7726E89E)

## Issues

Metaport CE is open source software! Use our [issue tracker](https://gitlab.com/dcentrica/metaport/metaport-server/-/issues) and be sure to read our [software license](./LICENSE), [license exceptions](./LICENSE_EXCEPTION) and [contributing guidelines](./CONTRIBUTING.md).

## License

Metaport is licensed under the GNU Affero GPL version 3.

In addition, the copyright holder grants the additional permission described in [LICENSE-EXCEPTION](/LICENSE_EXCEPTION), permitting certain proprietary extensions distributed by Dcentrica to be combined with Metaport.

## Thanks

Credit also goes to [Catalyst IT](https://catalyst.net.nz/) for the original investment and development of [Mataara](https://gitlab.com/Mataara) (formerly Archimedes) which heavily influenced the development of Metaport.
