# PIMA on Google Cloud – Products Overview

**Goal:** Replace Salesforce, Klipfolio, and OpenFn with a simpler, scalable, lower-cost stack on Google Cloud.

## Core Services
- **Cloud Run**: Runs our backend APIs, ETL jobs, and hosts the Superset dashboards and frontend. Scales up and down automatically.
- **Cloud SQL for PostgreSQL**: Managed PostgreSQL database for the system of record. Automated backups and maintenance. *(Replaces Salesforce data storage.)*
- **Pub/Sub**: For Event-driven data pipelines.
- **Firestore**: 
- **Cloud Storage**: Storage for files/exports and backups.
- **Cloud Logging & Monitoring**: Centralized logs, metrics, and alerting across services.

## Analytics & Dashboards
- **Apache Superset (hosted on Cloud Run)**: Dashboards and charts over Cloud SQL. *(Replaces Klipfolio.)*

