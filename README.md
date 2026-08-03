# Multi-Site Healthcare IT Transformation

![Case Study](https://img.shields.io/badge/type-case%20study-2563eb)
![Focus](https://img.shields.io/badge/focus-IT%20transformation-0f766e)
![Security](https://img.shields.io/badge/security-privacy%20aware-7c3aed)
![Status](https://img.shields.io/badge/status-v1.0-brightgreen)

A practical case study on transforming a fragmented, multi-site healthcare IT environment into a centralized, secure, automated, and documented operation.

> This public portfolio version is intentionally anonymized. It contains no patient data, credentials, internal addresses, account numbers, employee records, or confidential configuration details.

## Executive Snapshot

| Dimension | Portfolio-safe scope |
| --- | --- |
| Environment | 20+ healthcare locations |
| Technology | Windows, macOS, cloud services, networking, telecom, and print |
| Assets | 200+ devices brought into a structured inventory process |
| Operating model | Small IT team supporting distributed clinics |
| Primary objective | Replace reactive, location-by-location support with consistent central management |
| Delivery approach | Discover, standardize, automate, secure, document, and measure |

## The Challenge

The environment had grown clinic by clinic. Processes, devices, vendors, and access methods were not consistently documented or centrally governed. Routine changes often required an on-site visit, device information was spread across multiple sources, and technical ownership was not always separated clearly from financial and operational approval.

The transformation therefore had to improve technology and operating discipline at the same time—without interrupting clinical services.

## Before and After

| Before | After |
| --- | --- |
| Reactive, clinic-by-clinic support | Centralized visibility and repeatable support workflows |
| Manual workstation provisioning | Modular, one-command PowerShell bootstrap |
| Inconsistent endpoint protection | Standard RMM and EDR deployment program |
| Spreadsheet fragments and physical audits | Structured asset portal and management dashboard |
| Vendor and subscription sprawl | Documented ownership, review, and consolidation process |
| Knowledge held by individuals | SOPs, checklists, handover records, and training |
| Unclear request and approval paths | Defined roles for IT, Finance, HR, managers, and vendors |

## Transformation Model

```mermaid
flowchart LR
    A[Discover] --> B[Standardize]
    B --> C[Automate]
    C --> D[Secure]
    D --> E[Govern and measure]
```

The program was organized around seven connected workstreams:

1. [Current-state discovery](docs/01-current-state.md)
2. [Transformation roadmap](docs/02-transformation-roadmap.md)
3. [Endpoint management](docs/03-endpoint-management.md)
4. [Security improvements](docs/04-security-improvements.md)
5. [Automation and standardization](docs/05-automation.md)
6. [Asset and service governance](docs/06-asset-governance.md)
7. [Network, telecom, and continuity](docs/07-network-telecom-continuity.md)

A summary of outcomes and lessons learned is available in [Results and Lessons](docs/08-results-and-lessons.md).

## Selected Outcomes

The figures below are rounded or expressed as relative improvements to protect internal business information.

| Outcome | Result |
| --- | --- |
| Workstation provisioning | Reduced from a long manual checklist to a one-command bootstrap with modular validation |
| Endpoint visibility | Central management introduced for 100+ endpoints, with continued rollout |
| Asset visibility | More than 200 assets organized into a decision-ready inventory workflow |
| Cloud licensing | Approximately 40% monthly cost reduction through license consolidation |
| Field-support travel | More than 60% reduction in avoidable transportation spend through governance and remote support |
| Security | Standard EDR, email controls, access-removal procedures, and device baselines introduced |
| Operational resilience | Repeatable outage, onboarding, offboarding, procurement, and clinic-review processes documented |

## Key Deliverables

- Modular PowerShell deployment framework
- Central remote monitoring and management rollout
- Endpoint detection and response deployment
- macOS management through Jamf Pro and Apple Business Manager
- Asset inventory portal and live management reporting
- Google Workspace access, email, and group governance
- Telecom, print, and subscription consolidation reviews
- Standard onboarding, offboarding, procurement, outage, and site-health processes
- Clear responsibility boundaries between IT, Finance, HR, managers, and vendors

## Reusable Templates

The repository includes sanitized templates that demonstrate the operating model:

- [IT onboarding checklist](templates/it-onboarding-checklist.md)
- [IT offboarding checklist](templates/it-offboarding-checklist.md)
- [Technology procurement workflow](templates/technology-procurement-workflow.md)
- [Internet outage response](templates/internet-outage-response.md)
- [Clinic IT health check](templates/clinic-it-health-check.md)

These templates are examples, not organization-specific policies. They must be adapted to local privacy, employment, procurement, and regulatory requirements.

## Leadership Principles Demonstrated

- Start with operational risk and business impact, not tools.
- Standardize the process before automating it.
- Keep technical ownership with IT while approvals and payments remain with the appropriate business functions.
- Design controls that a small team can actually maintain.
- Document every recurring task so the operation does not depend on one person.
- Use measurable outcomes to prioritize the next phase.

## Repository Map

```text
.
├── README.md
├── DISCLAIMER.md
├── docs/
│   ├── 01-current-state.md
│   ├── 02-transformation-roadmap.md
│   ├── 03-endpoint-management.md
│   ├── 04-security-improvements.md
│   ├── 05-automation.md
│   ├── 06-asset-governance.md
│   ├── 07-network-telecom-continuity.md
│   └── 08-results-and-lessons.md
└── templates/
    ├── it-onboarding-checklist.md
    ├── it-offboarding-checklist.md
    ├── technology-procurement-workflow.md
    ├── internet-outage-response.md
    └── clinic-it-health-check.md
```

## Author

**Reza Mansouri**  
IT Infrastructure, Automation, and Operations Leadership  
Vancouver, British Columbia, Canada

- [GitHub](https://github.com/rezamans)
- [LinkedIn](https://www.linkedin.com/in/reza-mansouri-67297455/)
- [Portfolio](https://rezamansouri.net/)

## Use and Disclosure

Read [DISCLAIMER.md](DISCLAIMER.md) before reusing any material. No production configuration should be copied without independent security and compliance review.
