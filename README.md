# Apache Libcloud (apache-libcloud)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache Libcloud is a Python library for interacting with many popular cloud service providers using a unified API. It supports over 30 providers for compute, object storage, DNS, load balancers, and container services under the Apache 2.0 license.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-libcloud/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Abstraction Layer, Cloud, Multi-Cloud, Open Source, Python

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Libcloud Compute API
The Libcloud Compute API provides a unified Python interface for managing virtual machine instances, images, sizes, and networks across AWS EC2, Azure, GCP, DigitalOcean, and 25+ other providers.

**Human URL:** [https://libcloud.readthedocs.io/en/stable/compute/](https://libcloud.readthedocs.io/en/stable/compute/)

#### Tags:

 - Cloud, Compute, Python, VM Management

#### Properties

- [Documentation](https://libcloud.readthedocs.io/en/stable/compute/)
- [SDK](https://pypi.org/project/apache-libcloud/)

### Apache Libcloud Storage API
The Libcloud Storage API provides a unified Python interface for object storage operations across AWS S3, Azure Blob Storage, GCP Cloud Storage, and OpenStack Swift.

**Human URL:** [https://libcloud.readthedocs.io/en/stable/storage/](https://libcloud.readthedocs.io/en/stable/storage/)

#### Tags:

 - Cloud, Object Storage, Python

#### Properties

- [Documentation](https://libcloud.readthedocs.io/en/stable/storage/)

### Apache Libcloud DNS API
The Libcloud DNS API provides a unified Python interface for managing DNS zones and records across Route53, Azure DNS, Google Cloud DNS, and other providers.

**Human URL:** [https://libcloud.readthedocs.io/en/stable/dns/](https://libcloud.readthedocs.io/en/stable/dns/)

#### Tags:

 - Cloud, DNS, Python

#### Properties

- [Documentation](https://libcloud.readthedocs.io/en/stable/dns/)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/libcloud)
- [Documentation](https://libcloud.readthedocs.io/)
- [GettingStarted](https://libcloud.readthedocs.io/en/stable/getting_started.html)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)
- [Versioning](https://libcloud.readthedocs.io/en/stable/changelog.html)
- [SDK](https://pypi.org/project/apache-libcloud/)

## Features

| Name | Description |
|------|-------------|
| Multi-Cloud Portability | Unified Python API across 30+ cloud providers with no vendor lock-in. |
| Compute Management | Create, delete, and manage VMs and images across cloud providers. |
| Object Storage | Unified blob/object storage API across all major cloud storage providers. |
| DNS Management | Manage DNS zones and records across cloud DNS providers. |
| Load Balancer API | Unified load balancer management across cloud providers. |
| Container API | Docker container management via Libcloud container API. |

## Use Cases

| Name | Description |
|------|-------------|
| Multi-Cloud Infrastructure | Manage cloud infrastructure across multiple providers from a single Python codebase. |
| Cloud Provider Migration | Migrate cloud workloads between providers with minimal code changes. |
| Infrastructure Automation | Automate VM provisioning, storage, and DNS across cloud providers. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon Web Services | EC2 compute, S3 storage, Route53 DNS, and ELB load balancer support. |
| Microsoft Azure | Azure Compute, Blob Storage, and Azure DNS integration. |
| Google Cloud Platform | GCP Compute Engine, Cloud Storage, and Cloud DNS support. |
| OpenStack | Full OpenStack Nova, Swift, and Neutron integration. |
| DigitalOcean | DigitalOcean Droplets, Spaces, and DNS support. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
