# Mike Raynham

# Contact

* mikeraynham@gmail.com | +44 7813 307561

# Summary

* Hands-on Technical Lead and Senior Software Engineer with over 30 years of experience managing, maintaining, and modernising large-scale, long-lived production back-end systems.

* Deep expertise in back-end systems, high-performance databases, and Linux infrastructure.

* An advocate for comprehensive testing.  Experienced in establishing unit, integration, and characterisation tests to ensure operational reliability, performance, and stability of critical business logic.

* Proven track record of decoupling monolithic platforms into modern Rust and
  Python services on Google Cloud, while keeping critical systems reliable
  throughout.

* Built a spec-driven development system that orchestrates LLM agents through
  IEEE 830, EARS, and Gherkin into tested code, governed by traceability and
  mechanical CI gates, and used it to produce production Python services with
  clean architecture and full test suites.

* Experienced with GCP, Terraform, and PostgreSQL, with a track record of
  decoupling monolithic systems into modular services.

* Remote, UK.  Open to fully remote roles with flexible working hours, where
  technical versatility and a disciplined approach to engineering are valued.

# Technical Skills

* Languages: Perl, Rust, JavaScript/TypeScript, SQL (PostgreSQL & MySQL),
  Bash
* AI / Agentic: LLM agent orchestration (Claude Code skills, plugins, MCP,
  Agent Teams), spec-driven development (IEEE 830 / EARS / Gherkin),
  agent-directed Python services
* Cloud: Google Cloud Platform (Cloud Run, Cloud Build, IAM, IAP, VPC, PSC,
  AlloyDB)
* Infrastructure: Terraform, Ansible, Docker, CI/CD pipelines, automated
  deployments
* Data & Streaming: PostgreSQL, MySQL, Apache Kafka, Debezium, Redis
* Systems & Ops: Linux, Git, systemd.
* Web: HTML/CSS/JavaScript, Apache HTTP Server

# Employment

## Situation Publishing
### December 2022 to present (Tech Lead)
### May 2017 to December 2022 (Senior Developer)

Lead engineer for the back-end systems powering The Register and the company's lead-generation platform, covering cloud architecture, legacy modernisation, and infrastructure automation.

* Cut call centre contact searches to near-instant by rewriting the lead-generation matching logic for a PostgreSQL-backed CRM, using denormalised, heavily indexed tables (B-tree, GIN trigram, tsvector), Redis per-campaign queues, and Kafka event logs.  All backed by a comprehensive suite of unit and integration tests executed against real, ephemeral databases.

* Progressively decoupling legacy Perl logic by building modern API endpoints, automation utilities, and event-driven Kafka and Debezium pipelines.  All with thorough, multi-layered testing strategies.

* Built production Rust services (tokio/axum) to carve functionality out of the Perl monolith: a short-URL redirector with GeoIP routing, a Kafka-to-PostgreSQL lead pipeline, a database replication monitor, and a signature-verified SendGrid webhook handler.  Authored Infrastructure-as-Code (IaC) Terraform for reproducible deployments.

* Directed AI agents, through my spec-driven development system, to build production Python services with clean architecture and comprehensive tests: a domain-driven CRM microservice replacing the legacy platform, and a Django/Wagtail CMS on Cloud Run/AlloyDB.

* Own the GCP estate as modular Terraform: 30+ services across Cloud Run, AlloyDB, Managed Kafka, Private Service Connect, Certificate Manager, and Cloud Build, with Packer image builds, Ansible/systemd deployment, and GitHub Actions CI/CD.

* Designing and optimising PostgreSQL/MySQL schemas and queries, and diagnosing system-wide production issues from databases to cloud services.

* Instrument services with OpenTelemetry and structured logging, and test against real, ephemeral databases and browsers (testcontainers, Playwright).

* Built an agentic development workflow where specialised LLM agents produce IEEE 830 specifications, refine them into EARS syntax and Gherkin scenarios, then validate generated code against the resulting BDD/TDD suite and bespoke LLM-oriented coding standards.

##  SpareRoom.co.uk
### August 2011 to May 2017 (Technical Lead)

Technical Lead for one of the UK's busiest flat-sharing websites, driving
improvements to code quality, performance, scalability, and development
processes.

Key achievements:

* Led the migration from managed servers to colocation, successfully switching
  live traffic to the new infrastructure with zero downtime and zero issues.
  Refactored the codebase to remove years of hard-coded, hardware-specific
  configurations.  Built a highly available, HAProxy-fronted MySQL read-write
  and read-only replica architecture to support the move.  Used Puppet for
  fully reproducible server builds.
* Introduced Perl coding standards, code reviews, unit testing, and structured
  refactoring practices.
* Migrated version control from Subversion to Git.
* Improved scalability with memcached and Gearman; upgraded legacy Perl and
  MySQL systems.
* Built standardised development/testing environments using VirtualBox.
* Moved advert photo storage to AWS S3 behind EC2/ELB.
* Implemented HAProxy for front-end and database load balancing.
* Automated deployments using Perl, Rex, and Pinto.
* Led the migration of core search from MySQL to Sphinx Search, delivering
  major performance gains.

##  Self Employment
### August 2005 to August 2011

Freelance web development and IT support for small businesses, including
building database-driven sites (Linux, Apache/nginx, MySQL, PHP, Perl),
creating custom CMS platforms, and delivering bespoke data-processing
utilities.

##  Cheshire Building Society
### July 2001 to April 2003 (Technical Support Programmer)
### April 2003 to August 2005 (Infrastructure & Security Analyst)

Third-level support for critical systems, followed by infrastructure and
security work covering disaster recovery testing and firewall maintenance.

## Building Design Partnership
### July 1996 to July 2001 (Third-Level Technical Support)

## Expert Systems Design
### July 1995 to July 1996 (Developer & On-Site Support)

## Atkins Odlin & Partners
### April 1992 to July 1995 (Computer Administrator & AutoCAD Technician)
