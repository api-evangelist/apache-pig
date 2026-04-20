# Apache Pig (apache-pig)
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
