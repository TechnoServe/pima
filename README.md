# PIMA on Google Cloud – Products Overview

**Goal:** Replace Salesforce, Klipfolio, and OpenFn with a simpler, scalable, lower-cost stack on Google Cloud.

## Core Services
- **Cloud Run** – Runs our backend APIs, ETL jobs, and hosts the Superset dashboards and frontend. Scales up and down automatically. *(Replaces custom app hosting/OpenFn jobs.)*
- **Cloud SQL for PostgreSQL** – Managed PostgreSQL database for the system of record. Automated backups and maintenance. *(Replaces Salesforce data storage.)*
- **Pub/Sub** – Reliable messaging for event-driven data pipelines and decoupling services. *(Replaces OpenFn orchestration.)*
- **Cloud Storage** – Durable, low-cost object storage for files/exports and backups.
- **Cloud Logging & Monitoring (Cloud Operations)** – Centralized logs, metrics, and alerting across services.

## Analytics & Dashboards
- **Apache Superset (hosted on Cloud Run)** – Self-service dashboards and charts over Cloud SQL. *(Replaces Klipfolio.)*

## Notes
- Services are configured for minimal baseline cost and scale linearly with usage.
- Future add-ons (only if needed) could include **Cloud Composer** for complex workflows or **BigQuery** for large-scale analytics.
