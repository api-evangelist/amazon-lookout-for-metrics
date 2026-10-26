# Amazon Lookout for Metrics (amazon-lookout-for-metrics)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon Lookout for Metrics uses machine learning to automatically detect anomalies in business and operational metrics such as revenue performance, customer engagement, and user activity. It continuously monitors data from various sources including Amazon S3, CloudWatch, RDS, Redshift, Athena, and AppFlow, providing root cause analysis and alert notifications when anomalies are detected.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-metrics/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Anomaly Detection, AWS, Business Intelligence, Machine Learning, Metrics, Monitoring

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Lookout for Metrics API
The Amazon Lookout for Metrics API provides programmatic access to create and manage anomaly detectors, anomaly groups, alerts, and datasets for automated anomaly detection in business metrics. Supports detector lifecycle management, metric set configuration, alert creation, anomaly analysis, feedback collection, and resource tagging across 30 operations.

**Human URL:** [https://aws.amazon.com/lookout-for-metrics/](https://aws.amazon.com/lookout-for-metrics/)

#### Tags:

 - Anomaly Detection, Machine Learning, Metrics, Monitoring

#### Properties

- [Documentation](https://docs.aws.amazon.com/lookoutmetrics/latest/api/Welcome.html)
- [OpenAPI](openapi/amazon-lookout-for-metrics-openapi-original.yaml)
- [GettingStarted](https://aws.amazon.com/lookout-for-metrics/getting-started/)
- [Pricing](https://aws.amazon.com/lookout-for-metrics/pricing/)
- [FAQ](https://aws.amazon.com/lookout-for-metrics/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/lookout-for-metrics/)
- [Documentation](https://docs.aws.amazon.com/lookoutmetrics/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/machine-learning/tag/amazon-lookout-for-metrics/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/lookoutmetrics/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [SpectralRules](rules/amazon-lookout-for-metrics-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-lookout-for-metrics-vocabulary.yaml)
- [NaftikoCapability](capabilities/anomaly-detection-operations.yaml)

## Features

| Name | Description |
|------|-------------|
| Automated Anomaly Detection | Uses ML to automatically detect anomalies in business and operational metrics without requiring ML expertise. |
| Root Cause Analysis | Identifies the top contributors to each anomaly to help determine root causes quickly. |
| Multi-Source Data Ingestion | Connects to Amazon S3, CloudWatch, RDS, Redshift, Athena, and AppFlow as data sources. |
| Continuous Monitoring | Continuously monitors metrics and sends real-time alerts when anomalies are detected. |
| Alert Configuration | Configure alerts via Amazon SNS, Lambda, or other AWS services when anomalies occur. |
| Anomaly Feedback | Provide feedback on detected anomalies to improve future detection accuracy. |
| Resource Tagging | Tag anomaly detectors and related resources for cost allocation and organization. |

## Use Cases

| Name | Description |
|------|-------------|
| Revenue Anomaly Detection | Monitor revenue metrics and detect unexpected drops or spikes that could indicate fraud or system issues. |
| Customer Engagement Monitoring | Track customer engagement metrics and alert teams when patterns deviate from expected ranges. |
| Operational Metrics Monitoring | Monitor operational metrics such as system performance, error rates, and throughput for anomalies. |
| E-Commerce Performance | Detect anomalies in e-commerce metrics like conversion rates, cart abandonment, and sales volume. |
| User Activity Analysis | Analyze user activity patterns and detect unusual behavior that may indicate security incidents. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Use S3 buckets as a data source for metric data in CSV or JSON format. |
| Amazon CloudWatch | Ingest CloudWatch metrics directly for anomaly detection. |
| Amazon RDS | Connect to RDS databases to retrieve metric data for analysis. |
| Amazon Redshift | Use Redshift data warehouse as a source for business metrics. |
| Amazon Athena | Query Athena tables to feed metric data into anomaly detectors. |
| AWS AppFlow | Use AppFlow connectors to ingest data from SaaS applications. |
| Amazon SNS | Send alert notifications via SNS topics when anomalies are detected. |
| AWS Lambda | Trigger Lambda functions in response to detected anomalies for custom workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Lookout for Metrics OpenAPI](openapi/amazon-lookout-for-metrics-openapi-original.yaml)

### JSON Schema

229 schema files available in the [json-schema/](json-schema/) directory.

### JSON Structure

229 structure files available in the [json-structure/](json-structure/) directory.

### JSON-LD

- [Amazon Lookout for Metrics Context](json-ld/amazon-lookout-for-metrics-context.jsonld)

### Examples

229 example files available in the [examples/](examples/) directory.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Lookout for Metrics](capabilities/shared/lookout-for-metrics.yaml) — 20 operations for anomaly detection, alerting, and feedback

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Anomaly Detection Operations](capabilities/anomaly-detection-operations.yaml) | Amazon Lookout for Metrics | 12 | Data Scientist, Operations Engineer |

## Vocabulary

- [Amazon Lookout for Metrics Vocabulary](vocabulary/amazon-lookout-for-metrics-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 10 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Lookout for Metrics Spectral Rules](rules/amazon-lookout-for-metrics-spectral-rules.yml) — 22 rules across 8 categories enforcing Amazon Lookout for Metrics API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
