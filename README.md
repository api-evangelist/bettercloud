# BetterCloud (bettercloud)
BetterCloud is the end-to-end SaaS management platform that enables IT teams to discover, manage, and secure the growing SaaS environment. The platform provides automated workflows, security policies, and management capabilities for SaaS applications in enterprise environments, handling billions of API calls per day across 100+ SaaS application integrations.

**URL:** [https://developer.bettercloud.com/](https://developer.bettercloud.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, Compliance, Enterprise, IT Operations, SaaS Management, Security, Workflows, User Lifecycle

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### BetterCloud Platform API
The BetterCloud Platform API provides REST API access for managing SaaS application operations, automated workflows, user lifecycle management, and security policies. It enables IT and security teams to programmatically automate management workflows and enforce security policies across cloud technology stacks.

**Human URL:** [https://developer.bettercloud.com/](https://developer.bettercloud.com/)

#### Tags:

 - Automation, REST API, SaaS Management, Security, User Lifecycle, Workflows

#### Properties

- [Documentation](https://developer.bettercloud.com/)
- [GettingStarted](https://support.bettercloud.com/s/article/BCCINT4000--BetterCloud-API-Overview-bc33451)
- [OpenAPI](openapi/bettercloud-platform-api.yaml)

## Common Properties

- [Portal](https://developer.bettercloud.com/)
- [GettingStarted](https://support.bettercloud.com/s/article/BCCINT4000--BetterCloud-API-Overview-bc33451)
- [Pricing](https://www.bettercloud.com/pricing/)
- [Blog](https://www.bettercloud.com/monitor/)
- [Support](https://support.bettercloud.com/s/)
- [Login](https://support.bettercloud.com/s/login/)
- [SignUp](https://www.bettercloud.com/monitor/sign-up/)
- [GitHubOrganization](https://github.com/BetterCloud)

## Features

| Name | Description |
|------|-------------|
| User Lifecycle Management | Automate user onboarding and offboarding workflows across all connected SaaS applications. |
| SaaS Discovery | Automatically discover all SaaS applications in use across the organization. |
| Automated Workflows | Build no-code automation workflows triggered by events, schedules, or manual action. |
| Security Policy Enforcement | Create and enforce security policies that monitor and remediate violations across SaaS apps. |
| Group Management | Manage groups and memberships across Google Workspace, Azure AD, and other directory services. |
| Audit Logging | Comprehensive audit trail of all actions taken by users and automated workflows. |
| SaaS Integrations | Connect and manage 100+ enterprise SaaS applications including Google Workspace, Slack, Salesforce, and more. |
| License Management | Track and optimize SaaS licenses to reduce spend and identify unused seats. |

## Use Cases

| Name | Description |
|------|-------------|
| Employee Offboarding | Automatically revoke access and deprovision users across all SaaS applications when an employee leaves. |
| Employee Onboarding | Automatically provision new employees with appropriate SaaS access based on role and department. |
| SaaS Spend Optimization | Identify underutilized licenses and redundant applications to reduce SaaS spend. |
| Security Incident Response | Immediately suspend and deprovision compromised accounts across all SaaS platforms. |
| Compliance Auditing | Generate audit reports showing who has access to what across all connected SaaS applications. |
| Access Reviews | Periodically review and certify user access to ensure least-privilege principles. |

## Integrations

| Name | Description |
|------|-------------|
| Google Workspace | Manage Google Workspace users, groups, Drive files, and calendar access. |
| Slack | Manage Slack workspace users, channels, and app connections. |
| Salesforce | Manage Salesforce user provisioning and deprovisioning. |
| Microsoft 365 | Manage Microsoft 365 users, licenses, and Azure AD groups. |
| Okta | Connect BetterCloud workflows with Okta identity management. |
| ServiceNow | Trigger BetterCloud workflows from ServiceNow ITSM tickets. |
| Jira | Integrate SaaS management actions with Jira issue workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [BetterCloud Platform API](openapi/bettercloud-platform-api.yaml)

### JSON Schema

- [bettercloud-event-schema.json](json-schema/bettercloud-event-schema.json)
- [bettercloud-event-list-response-schema.json](json-schema/bettercloud-event-list-response-schema.json)
- [bettercloud-group-schema.json](json-schema/bettercloud-group-schema.json)
- [bettercloud-group-create-request-schema.json](json-schema/bettercloud-group-create-request-schema.json)
- [bettercloud-group-list-response-schema.json](json-schema/bettercloud-group-list-response-schema.json)
- [bettercloud-group-member-schema.json](json-schema/bettercloud-group-member-schema.json)
- [bettercloud-group-member-add-request-schema.json](json-schema/bettercloud-group-member-add-request-schema.json)
- [bettercloud-group-member-list-response-schema.json](json-schema/bettercloud-group-member-list-response-schema.json)
- [bettercloud-group-member-response-schema.json](json-schema/bettercloud-group-member-response-schema.json)
- [bettercloud-group-response-schema.json](json-schema/bettercloud-group-response-schema.json)
- [bettercloud-integration-schema.json](json-schema/bettercloud-integration-schema.json)
- [bettercloud-integration-list-response-schema.json](json-schema/bettercloud-integration-list-response-schema.json)
- [bettercloud-meta-response-schema.json](json-schema/bettercloud-meta-response-schema.json)
- [bettercloud-user-schema.json](json-schema/bettercloud-user-schema.json)
- [bettercloud-user-list-response-schema.json](json-schema/bettercloud-user-list-response-schema.json)
- [bettercloud-user-response-schema.json](json-schema/bettercloud-user-response-schema.json)
- [bettercloud-user-update-request-schema.json](json-schema/bettercloud-user-update-request-schema.json)
- [bettercloud-workflow-schema.json](json-schema/bettercloud-workflow-schema.json)
- [bettercloud-workflow-create-request-schema.json](json-schema/bettercloud-workflow-create-request-schema.json)
- [bettercloud-workflow-list-response-schema.json](json-schema/bettercloud-workflow-list-response-schema.json)
- [bettercloud-workflow-response-schema.json](json-schema/bettercloud-workflow-response-schema.json)
- [bettercloud-workflow-run-request-schema.json](json-schema/bettercloud-workflow-run-request-schema.json)
- [bettercloud-workflow-run-response-schema.json](json-schema/bettercloud-workflow-run-response-schema.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [BetterCloud Platform API](capabilities/shared/bettercloud.yaml) — 19 operations for user lifecycle management, group management, workflows, events, and integrations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [SaaS Lifecycle Management](capabilities/saas-lifecycle-management.yaml) | BetterCloud | 11 | IT Administrator, Security Engineer |

## Vocabulary

- [BetterCloud Vocabulary](vocabulary/bettercloud-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [BetterCloud Spectral Rules](rules/bettercloud-spectral-rules.yml) — 28 rules across 10 categories enforcing BetterCloud API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
