# Secure-Web-Application-Deployment-on-Google-Cloud
# Secure Web Application Deployment on Google Cloud

## Overview

This project demonstrates the deployment of a secure web application on Google Cloud Platform (GCP) using Compute Engine, Cloud SQL, and Cloud Storage. The lab focuses on cloud infrastructure provisioning, secure connectivity between services, and validating application-to-database communication.

## Objectives

* Deploy a Linux virtual machine using Compute Engine.
* Configure an Apache web server with PHP.
* Create and configure a Cloud SQL (MySQL) instance.
* Establish secure connectivity between the web server and the database.
* Store and serve static content from Cloud Storage.
* Validate application functionality and database connectivity.

## Security Responsibilities

As part of this lab, the following cloud security practices were implemented:

* Configured firewall rules to allow only required HTTP traffic.
* Restricted Cloud SQL access by authorizing only the web server's public IP address.
* Applied the principle of least privilege for database access using a dedicated database user.
* Validated secure communication between the application and Cloud SQL.
* Managed Cloud Storage object permissions for controlled public access.
* Verified network connectivity and application availability after deployment.

## Technologies Used

* Google Cloud Platform (GCP)
* Compute Engine
* Cloud SQL (MySQL)
* Cloud Storage
* Apache Web Server
* PHP
* Google Cloud Shell
* gcloud CLI

## Skills Demonstrated

* Cloud Infrastructure Deployment
* Cloud Security Configuration
* Identity and Access Management (IAM) Concepts
* Network Access Control
* Firewall Configuration
* Secure Database Connectivity
* Cloud Storage Security
* Linux Administration
* Troubleshooting Cloud Resources

## Outcome

Successfully deployed a functional web application with secure database connectivity, implemented basic cloud security controls, and validated secure communication between cloud services following Google Cloud best practices.
