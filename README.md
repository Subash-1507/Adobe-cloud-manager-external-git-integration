# Adobe Cloud Manager External Git Integration | Bitbucket | CI/CD

## Overview

This repository demonstrates the integration of a customer-managed Git repository (Bitbucket) with Adobe Cloud Manager’s provisioned Git repository.

The implementation enables external code repositories to be used as the primary source for CI/CD pipelines in Adobe Cloud environments.

---

## Documentation

Detailed steps are available in:

/docs/external-git-integration.pdf

---

## Core Skills Demonstrated

* Git Repository Management
* CI/CD Pipeline Integration
* Adobe Cloud Manager
* Bitbucket Integration
* Webhooks Configuration
* Access Token Management
* DevOps Workflow Automation

---

## Technical Implementation

### Repository Configuration

* Cloned Bitbucket repository to local system
* Configured multiple Git remotes (origin + adobe)
* Verified repository connections using `git remote -v` 

### Integration Setup

* Added external repository in Adobe Cloud Manager
* Selected customer-managed repository option
* Configured repository URL and authentication details 

### Authentication & Security

* Generated Bitbucket access tokens
* Configured secure access for Cloud Manager
* Managed repository permissions and access control 

### Webhook Configuration

* Created webhook in Bitbucket for push events
* Connected webhook to Adobe Cloud Manager endpoint
* Enabled automated pipeline triggers on code changes 

### CI/CD Workflow

* Pushed code changes to external repository
* Triggered Cloud Manager pipeline automatically
* Validated integration through deployment flow (Dev → Stage → Production) 

---

## Key Achievements

* Successfully integrated external Git with Adobe Cloud Manager
* Enabled automated CI/CD pipeline execution
* Implemented webhook-based deployment triggers
* Managed multiple Git remotes for flexible workflows
* Improved deployment efficiency and automation

---

## Tools & Technologies

Git | Bitbucket | Adobe Cloud Manager | CI/CD | Webhooks

---

## Purpose

This project demonstrates how external repositories can be integrated into enterprise CI/CD pipelines, enabling flexible and scalable deployment workflows.

---

## Note

This repository focuses on practical DevOps implementation using Adobe Cloud Manager and external Git systems.
