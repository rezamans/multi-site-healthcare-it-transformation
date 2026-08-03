# 04 — Security Improvements

## Security Approach

Security improvements were designed as operational controls, not one-time product installations.

## Control Areas

### Endpoint security

- Standard EDR deployment and health monitoring
- Patch and operating-system visibility
- Disk-encryption verification
- Administrative-account governance
- Controlled remote support

### Identity and access

- Standard account request and approval records
- Role-based access wherever supported
- Prompt HR-triggered offboarding
- Periodic review of privileged and inactive accounts
- Separation of personal and shared accounts

### Email and collaboration

- SPF, DKIM, and DMARC alignment
- Privacy-aware bulk-email standards
- BCC-only guidance for approved mass messages
- Review and approval before broad distribution
- Managed group ownership and membership

### Operational resilience

- Documented Internet and telecom escalation paths
- Known vendor and support ownership
- Standard configuration and recovery records
- Incident notes that preserve evidence without exposing sensitive content

## Design Principle

A control is only considered implemented when it has an owner, a verification method, an exception process, and a recurring review date.

## Public Case-Study Boundary

This repository intentionally excludes the technical values that would make security controls reproducible against a real environment, including credentials, tenant identifiers, network addressing, exact policy payloads, and recovery procedures.
