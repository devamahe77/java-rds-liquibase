# AWS Account Service

This service manages AWS account data.

## Changes

- Created a Spring Boot application with Liquibase to manage database schema changes.
- Added a Liquibase changeset to create the `aws_account` table in the `cads` schema with columns `aws_account_id` and `data_classification`.
- Added a Liquibase changeset to insert 10 records into the `aws_account` table.

## Configuration

To run this application, you need to configure the Oracle database connection in `src/main/resources/application.properties`.
