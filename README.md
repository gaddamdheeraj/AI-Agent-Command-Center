# AI Agent Command Center — Salesforce

An intelligent project operations platform built on Salesforce to monitor project health, manage tasks, identify risks, and automate operational decisions using Salesforce automation and AI capabilities.

## Overview

The AI Agent Command Center centralizes project and task management in Salesforce. It helps teams identify blocked and high-risk tasks, monitor project status, and trigger appropriate operational actions through automated workflows.

This project demonstrates practical Salesforce development, declarative automation, data modeling, and AI-assisted enterprise workflow design.

## Key Features

- **Project Management:** Custom Salesforce objects for managing projects and their tasks.
- **Task Risk Monitoring:** Identify blocked tasks, high-priority work, and potential project risks.
- **Flow Automation:** Record-triggered and scheduled automation for project and task operations.
- **Operational Issue Management:** Connect project risks with operational follow-up.
- **Team Coordination:** Track team members, responsibilities, availability, and workload.
- **AI-Ready Architecture:** Designed to support agent-assisted analysis, contextual grounding, and governed AI-driven workflows.
- **Salesforce Metadata Source Control:** Retrieve and version Salesforce configuration using Salesforce CLI and Git.

## Salesforce Data Model

The retrieved metadata includes custom objects such as:

- `Project__c` — Project information and health tracking.
- `Project_Task__c` — Project tasks, status, priority, and risk-related information.
- `Team_Member__c` — Team member information and workload.
- `Operational_Issue__c` — Operational issues and follow-up.
- `Employee__c` — Employee information.
- `Onboarding_Task__c` — Employee onboarding tasks.
- `Equipment__c` — Equipment tracking.
- `Document_Checklist__c` — Required document tracking.
- `Training__c` — Training and completion tracking.

The repository also contains metadata for additional objects and supporting Salesforce components.

## Automation Examples

The retrieved metadata includes Salesforce Flows for scenarios such as:

- Project task risk monitoring.
- Blocked-task risk updates.
- High-priority task risk handling.
- Operational issue creation for high-risk tasks.
- Overdue-task automation.
- Project updates following task completion.
- Team-member issue notifications.

## Technology Stack

- Salesforce Platform
- Salesforce DX and Salesforce CLI
- Salesforce Flow Builder
- Apex
- Custom Objects and Fields
- Git and GitHub
- AI-assisted development concepts

## Repository Structure

```text
force-app/
  main/
    default/
      objects/
      flows/
      classes/
      triggers/
      layouts/
      tabs/
      applications/
manifest/
  package.xml
scripts/
  apex/
  soql/
sfdx-project.json
```

## Setup and Retrieval

1. Install Salesforce CLI and Visual Studio Code.
2. Clone this repository.
3. Authenticate to a Salesforce org where you have appropriate permissions.
4. Review `manifest/package.xml` to understand the metadata included in the retrieval.
5. Retrieve or deploy metadata using Salesforce CLI as appropriate for your target org.

**Important:** Review the target org and metadata dependencies before deploying. Deployment can change existing Salesforce configuration.

## Project Goals

- Improve visibility into project health and operational risks.
- Reduce repetitive manual monitoring through automation.
- Demonstrate Salesforce metadata management and source control.
- Explore responsible AI-assisted operations and incident analysis.

## Author

**Dheeraj Reddy**

Salesforce Administrator | Platform App Builder | Salesforce Development and AI Automation

