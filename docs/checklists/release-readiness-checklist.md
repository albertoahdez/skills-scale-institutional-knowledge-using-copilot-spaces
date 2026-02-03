# Release Readiness Checklist

## Purpose
Pre-release verification checklist mapped to specific roles to ensure all critical items are complete before deployment.

## How to Use
1. Start this checklist 1-2 weeks before planned release
2. Assign each item to the responsible role
3. Track completion in your project management tool or copy to a GitHub issue
4. Hold a release readiness review to confirm all items before go/no-go decision

---

## Pre-Release Checklist

### Code & Build Quality

- [ ] **CI Pipeline Green**: All automated builds passing
  - **Who verifies**: DevOps Engineer / Dev Lead
  - **Status**: ☐ Complete | Date: ____
  - **Notes**: _____________________________________

- [ ] **Unit Tests Passing**: All unit tests pass with adequate coverage
  - **Who verifies**: Developers / Dev Lead
  - **Status**: ☐ Complete | Date: ____
  - **Target coverage**: _____% | **Actual**: _____%

- [ ] **Integration Tests Passing**: Integration test suite passes
  - **Who verifies**: QA Lead / Developers
  - **Status**: ☐ Complete | Date: ____
  - **Notes**: _____________________________________

- [ ] **E2E Tests Passing**: End-to-end tests pass in staging
  - **Who verifies**: QA Lead
  - **Status**: ☐ Complete | Date: ____
  - **Notes**: _____________________________________

### Security & Compliance

- [ ] **Security Scan Complete**: Vulnerability scan completed and reviewed
  - **Who verifies**: DevOps Engineer / Security Team
  - **Status**: ☐ Complete | Date: ____
  - **Critical/High vulnerabilities**: ☐ None | ☐ Resolved | ☐ Accepted risk
  - **Notes**: _____________________________________

- [ ] **Dependency Audit**: Dependencies scanned for known vulnerabilities
  - **Who verifies**: DevOps Engineer / Developers
  - **Status**: ☐ Complete | Date: ____
  - **Notes**: _____________________________________

- [ ] **Secrets/Credentials Check**: No hardcoded secrets or credentials in code
  - **Who verifies**: Dev Lead / DevOps Engineer
  - **Status**: ☐ Complete | Date: ____
  - **Notes**: _____________________________________

- [ ] **Compliance Requirements Met**: Any regulatory/compliance requirements addressed
  - **Who verifies**: Project Manager / Compliance Team
  - **Status**: ☐ Complete | ☐ N/A | Date: ____
  - **Notes**: _____________________________________

### Data & Infrastructure

- [ ] **Database Migrations Tested**: Migration scripts tested in staging
  - **Who verifies**: DevOps Engineer / Database Admin
  - **Status**: ☐ Complete | ☐ N/A | Date: ____
  - **Rollback tested**: ☐ Yes | ☐ N/A
  - **Notes**: _____________________________________

- [ ] **Infrastructure Capacity**: Resources scaled appropriately for expected load
  - **Who verifies**: DevOps Engineer
  - **Status**: ☐ Complete | Date: ____
  - **Notes**: _____________________________________

- [ ] **Backup Verified**: Current backups exist and restoration tested
  - **Who verifies**: DevOps Engineer
  - **Status**: ☐ Complete | Date: ____
  - **Last backup**: __________ | **Restoration test**: __________

### Monitoring & Observability

- [ ] **Monitoring Configured**: Alerts and dashboards set up for key metrics
  - **Who verifies**: DevOps Engineer / Data Analyst
  - **Status**: ☐ Complete | Date: ____
  - **Dashboard URL**: _____________________________________
  - **Notes**: _____________________________________

- [ ] **Logging Enabled**: Application logging configured and tested
  - **Who verifies**: DevOps Engineer / Developers
  - **Status**: ☐ Complete | Date: ____
  - **Notes**: _____________________________________

- [ ] **Error Tracking Active**: Error monitoring (e.g., Sentry, Rollbar) configured
  - **Who verifies**: DevOps Engineer
  - **Status**: ☐ Complete | Date: ____
  - **Notes**: _____________________________________

### Documentation & Communication

- [ ] **Release Notes Written**: User-facing changes documented
  - **Who verifies**: Technical Writer / Product Manager
  - **Status**: ☐ Complete | Date: ____
  - **Review completed by**: __________
  - **Location**: _____________________________________

- [ ] **User Documentation Updated**: Guides and help docs reflect new features
  - **Who verifies**: Technical Writer
  - **Status**: ☐ Complete | ☐ N/A | Date: ____
  - **Documentation URLs**: _____________________________________

- [ ] **API Documentation Updated**: If applicable, API docs current
  - **Who verifies**: Technical Writer / Developers
  - **Status**: ☐ Complete | ☐ N/A | Date: ____
  - **Notes**: _____________________________________

- [ ] **Internal Runbook Updated**: Operational procedures documented
  - **Who verifies**: DevOps Engineer
  - **Status**: ☐ Complete | Date: ____
  - **Location**: _____________________________________

- [ ] **Support Team Briefed**: Support trained on new features and known issues
  - **Who verifies**: Customer Support Lead / Product Manager
  - **Status**: ☐ Complete | Date: ____
  - **Training date**: __________ | **Materials location**: __________

### Stakeholder Alignment

- [ ] **Stakeholder Notification Prepared**: Communication to key stakeholders drafted
  - **Who verifies**: Project Manager / Product Manager
  - **Status**: ☐ Complete | Date: ____
  - **Notification plan**: _____________________________________

- [ ] **Customer Communication Ready**: If applicable, customer announcement prepared
  - **Who verifies**: Product Manager / Marketing
  - **Status**: ☐ Complete | ☐ N/A | Date: ____
  - **Notes**: _____________________________________

- [ ] **Release Window Confirmed**: Deployment time scheduled and communicated
  - **Who verifies**: Project Manager
  - **Status**: ☐ Complete | Date: ____
  - **Release window**: __________
  - **Notified**: ☐ Team | ☐ Stakeholders | ☐ Customers

### Deployment Readiness

- [ ] **Rollback Plan Documented**: Steps to rollback if deployment fails
  - **Who verifies**: DevOps Engineer / Dev Lead
  - **Status**: ☐ Complete | Date: ____
  - **Rollback tested**: ☐ Yes | ☐ No
  - **Plan location**: _____________________________________

- [ ] **Smoke Test Plan Ready**: Critical path tests defined for post-deploy
  - **Who verifies**: QA Lead
  - **Status**: ☐ Complete | Date: ____
  - **Test scenarios**: _____________________________________

- [ ] **On-Call Assignments**: On-call coverage confirmed for release window
  - **Who verifies**: Project Manager / DevOps Lead
  - **Status**: ☐ Complete | Date: ____
  - **On-call roster**: _____________________________________

- [ ] **Feature Flags Configured**: If applicable, feature flags set correctly
  - **Who verifies**: DevOps Engineer / Developers
  - **Status**: ☐ Complete | ☐ N/A | Date: ____
  - **Notes**: _____________________________________

### Final Approvals

- [ ] **QA Sign-Off**: QA lead confirms quality gates met
  - **Who approves**: QA Lead
  - **Status**: ☐ Approved | Date: __________
  - **Signature/Name**: _____________________________________

- [ ] **Product Sign-Off**: Product manager confirms feature readiness
  - **Who approves**: Product Manager
  - **Status**: ☐ Approved | Date: __________
  - **Signature/Name**: _____________________________________

- [ ] **Technical Sign-Off**: Tech lead confirms technical readiness
  - **Who approves**: Dev Lead / Tech Lead
  - **Status**: ☐ Approved | Date: __________
  - **Signature/Name**: _____________________________________

- [ ] **Release Manager Sign-Off**: PM/Release manager confirms overall readiness
  - **Who approves**: Project Manager
  - **Status**: ☐ Approved | Date: __________
  - **Signature/Name**: _____________________________________

---

## Go/No-Go Decision

**Decision Date**: __________  
**Decision Time**: __________  

**Attendees**:
- Project Manager: __________
- Product Manager: __________
- Dev Lead: __________
- QA Lead: __________
- DevOps Engineer: __________

**Decision**: ☐ GO | ☐ NO-GO | ☐ GO with conditions

**Conditions (if applicable)**:
_____________________________________
_____________________________________

**Decision rationale**:
_____________________________________
_____________________________________

**Approved by**: __________  
**Date/Time**: __________

---

## Post-Deployment

- [ ] **Deployment Completed**: Feature deployed to production
  - **Who verifies**: DevOps Engineer
  - **Completion time**: __________
  
- [ ] **Smoke Tests Passed**: Post-deploy critical path tests passed
  - **Who verifies**: QA Lead / DevOps Engineer
  - **Completion time**: __________
  
- [ ] **Monitoring Shows Healthy**: Metrics and alerts show normal operation
  - **Who verifies**: DevOps Engineer
  - **Verification time**: __________
  
- [ ] **Stakeholders Notified**: Release completion communicated
  - **Who notifies**: Project Manager
  - **Notification time**: __________

---

## Notes
- Customize this checklist based on your organization's requirements
- Add project-specific items as needed
- Some items may not apply to all releases (mark as N/A where appropriate)
- Save completed checklists for audit trail and continuous improvement
