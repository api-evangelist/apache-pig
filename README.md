# Apache Pig (apache-pig)

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

Apache Pig is a platform for analyzing large data sets that provides a high-level language (Pig Latin) for expressing data analysis programs. It compiles Pig Latin programs into MapReduce/Tez jobs and runs them on Hadoop clusters.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-pig/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Big Data, Data Analysis, ETL, Hadoop, Scripting, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Pig
Pig provides the Pig Latin scripting language for data analysis, an embedded Pig API for programmatic execution from Java, and a UDF (User Defined Function) API for custom data transformation functions.

**Human URL:** [https://pig.apache.org/docs/latest/](https://pig.apache.org/docs/latest/)

#### Tags:

 - Data Analysis, Java, Pig Latin, UDF, Apache, Open Source

#### Properties

- [Documentation](https://pig.apache.org/docs/latest/)
- [OpenAPI](openapi/apache-pig-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/pig)
- [Documentation](https://pig.apache.org/)
- [SpectralRules](rules/apache-pig-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-pig-vocabulary.yaml)
- [NaftikoCapability](capabilities/pig-workflow.yaml)
- [JSON-LD](json-ld/apache-pig-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Pig Latin Language | High-level dataflow language for expressing data transformations |
| MapReduce/Tez Backend | Compiles Pig Latin to MapReduce or Apache Tez execution plans |
| UDF Support | User-defined functions in Java, Python, JavaScript, and Ruby |
| Streaming | Process data through external programs using STREAM operator |
| Schema Evolution | Flexible schema handling for semi-structured data |
| Optimization | Automatic logical and physical plan optimization |

## Use Cases

| Name | Description |
|------|-------------|
| ETL Pipelines | Build data transformation pipelines from raw logs to structured data |
| Ad-hoc Data Analysis | Analyze large datasets with ad-hoc Pig Latin queries |
| Data Preparation | Clean and prepare data for machine learning workflows |
| Log Processing | Process and aggregate web server and application logs |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop | Native MapReduce execution on YARN/HDFS |
| Apache Tez | High-performance Tez execution engine support |
| Apache HBase | HBase storage handler for reading/writing HBase tables |
| Apache Hive | HCatalog integration for Hive metastore access |
| Amazon S3 | S3 input/output for cloud-based data processing |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Pig API](openapi/apache-pig-api.yaml)

### JSON Schema

- [Job](json-schema/apache-pig-job-schema.json)
- [Job Request](json-schema/apache-pig-job-request-schema.json)
- [Job Logs](json-schema/apache-pig-job-logs-schema.json)
- [Validation Result](json-schema/apache-pig-validation-result-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache Pig JSON Structures](json-structure/)

### JSON-LD

- [Apache Pig Context](json-ld/apache-pig-context.jsonld)

### Examples

- [Apache Pig Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Processing Workflow](capabilities/pig-workflow.yaml) | Apache Pig | 6 | Data Engineer, Data Analyst |

## Vocabulary

- [Apache Pig Vocabulary](vocabulary/apache-pig-vocabulary.yaml) — Unified taxonomy mapping Pig data processing resources, actions, workflows, and personas

## Rules

- [Apache Pig Spectral Rules](rules/apache-pig-spectral-rules.yml) — Rules enforcing Apache Pig API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
