# Mike Raynham

# Contact

* mikeraynham@gmail.com | +44 7813 307561

# Summary

* Hands-on Tech Lead and senior software engineer with over 30 years of
  experience across backend development, cloud platforms, and large-scale
  legacy systems.

* Specialising in modernising long-lived systems, migrating embedded legacy
  logic into high-performance architectures.

* Exploring Specification Driven Development (SDD) workflows that use agentic
  orchestration (LLM agents) to translate business requirements into
  documented, tested code.

* Experienced with GCP, Terraform, and PostgreSQL, with a track record of
  decoupling monolithic systems into modular services.

* Remote, UK.  Open to fully remote roles with flexible working hours, where
  technical versatility and a disciplined approach to engineering are valued.

# Employment

## Situation Publishing
### May 2017 to present (Tech Lead)
### May 2017 to December 2022 (Senior Developer)

Lead engineer for the backend systems powering The Register and the company's
lead-generation platform, covering cloud architecture, legacy modernisation,
and infrastructure automation.

* Cut call centre contact searches to near-instant by rewriting the
  lead-generation matching logic for a PostgreSQL-backed CRM, using
  denormalised, heavily indexed tables (B-tree, GIN trigram, tsvector), Redis
  per-campaign queues, and Kafka event logs.

* Progressively decoupling legacy Perl logic by building modern API endpoints,
  automation utilities, and event-driven pipelines, using Kafka and Debezium
  for replication and CDC.

* Developed production services in Rust to replace components of monolithic
  systems, including a database replication monitor, a short-URL redirector,
  and a Kafka consumer for lead-generation events.  All deployed with
  Terraform.

* Designing and deploying GCP services (Cloud Run, Cloud Build, IAM, VPC
  access, IAP, HTTPS load balancers, Private Service Connect) via modular
  Terraform with secure defaults and automated deployments.

* Designing and optimising PostgreSQL/MySQL schemas and queries, and
  diagnosing system-wide production issues from databases to cloud services.

* Currently exploring agentic coding by designing a workflow where specialised
  LLM agents produce IEEE 830 specifications, refine them into EARS syntax and
  Gherkin scenarios, then validate generated code against the resulting
  BDD/TDD suite and bespoke LLM-oriented coding standards.  The workflow is
  still in active development; applying it to production coding is the next
  step.

##  SpareRoom.co.uk
### August 2011 to May 2017 (Technical Lead)

Technical Lead for one of the UK's busiest flat-sharing websites, driving
improvements to code quality, performance, scalability, and development
processes.

Key achievements:

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

# Technical Skills

* Languages: Perl (primary), JavaScript, SQL (PostgreSQL & MySQL),
  Rust (novice), Bash
* Cloud: Google Cloud Platform (Cloud Run, Cloud Build, IAM, IAP, VPC, PSC,
  AlloyDB)
* Infrastructure: Terraform, CI/CD pipelines, automated deployments
* Data & Streaming: PostgreSQL, MySQL, Apache Kafka, Debezium
* Systems & Ops: Linux, Git, systemd
* Web: HTML/CSS/JavaScript, Apache HTTP Server
