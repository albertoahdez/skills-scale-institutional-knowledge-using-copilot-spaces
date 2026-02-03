# Feature Handoff Checklist Template

## Purpose
Ensure smooth transitions between development phases and teams by tracking required artifacts, verifications, and notifications at each handoff point.

## How to Use
1. Copy this checklist to your feature/project documentation
2. Check items as they're completed during each phase
3. Ensure the "Verified By" person confirms before proceeding to next phase
4. Attach this checklist to backlog items requiring cross-functional handoffs

---

## Development → QA Handoff

**Required Before QA Can Begin:**

- [ ] **Code Complete**: All code merged to staging/QA branch
  - Verified by: [Dev Lead Name] | Date: ____
  
- [ ] **PR Links**: All relevant pull requests documented
  - PR URLs: ________________
  - Verified by: [Dev Lead Name] | Date: ____
  
- [ ] **Test Plan Available**: Test scenarios and acceptance criteria documented
  - Test plan location: ________________
  - Verified by: [PdM/Dev Lead Name] | Date: ____
  
- [ ] **Environment Ready**: Feature deployed to QA/staging environment
  - Environment URL: ________________
  - Verified by: [DevOps Engineer Name] | Date: ____
  
- [ ] **Data/Test Accounts**: Required test data and accounts created
  - Test account details location: ________________
  - Verified by: [Dev Lead Name] | Date: ____
  
- [ ] **Known Limitations**: Any scope limitations or known issues documented
  - Documentation location: ________________
  - Verified by: [Dev Lead Name] | Date: ____

**Notifications Sent:**
- [ ] QA team notified via [Slack/Email] on [Date]
- [ ] Handoff meeting held: [Date/Time] or async handoff confirmed

---

## QA → Release Handoff

**Required Before Release:**

- [ ] **All Tests Passed**: Test execution complete with passing results
  - Test results location: ________________
  - Verified by: [QA Lead Name] | Date: ____
  
- [ ] **Defects Resolved**: All blocking/critical defects fixed or waived
  - Defect summary: ________________
  - Verified by: [QA Lead Name] | Date: ____
  
- [ ] **Regression Testing**: Regression test suite passed
  - Verified by: [QA Lead Name] | Date: ____
  
- [ ] **Performance/Load Testing**: If applicable, performance validated
  - Results location: ________________
  - Verified by: [QA/DevOps Name] | Date: ____
  
- [ ] **Security Scan**: Security/vulnerability scan completed and reviewed
  - Scan results: ________________
  - Verified by: [DevOps/Security Name] | Date: ____
  
- [ ] **Accessibility Check**: If applicable, accessibility standards validated
  - Verified by: [QA/UX Name] | Date: ____
  
- [ ] **Release Notes Draft**: User-facing changes documented
  - Draft location: ________________
  - Verified by: [Technical Writer/PdM Name] | Date: ____

**Notifications Sent:**
- [ ] PM notified of QA sign-off via [Slack/Email] on [Date]
- [ ] Release readiness review meeting held: [Date/Time]

---

## Release → Production Handoff

**Required for Deployment:**

- [ ] **Release Plan**: Deployment steps and timeline documented
  - Plan location: ________________
  - Verified by: [PM/DevOps Name] | Date: ____
  
- [ ] **Runbook Available**: Operational procedures documented
  - Runbook location: ________________
  - Verified by: [DevOps Engineer Name] | Date: ____
  
- [ ] **Monitoring Setup**: Alerts and dashboards configured
  - Dashboard links: ________________
  - Verified by: [DevOps Engineer Name] | Date: ____
  
- [ ] **Rollback Plan**: Rollback steps documented and tested
  - Rollback procedure: ________________
  - Verified by: [DevOps Engineer Name] | Date: ____
  
- [ ] **Database Migrations**: If applicable, migration scripts reviewed and tested
  - Migration details: ________________
  - Verified by: [Dev Lead/DevOps Name] | Date: ____
  
- [ ] **Deployment Window**: Release window scheduled and communicated
  - Scheduled for: ________________
  - Verified by: [PM Name] | Date: ____
  
- [ ] **Go/No-Go Decision**: Final release approval obtained
  - Decision by: [PM/PdM/Tech Lead Names] | Date: ____

**Notifications Sent:**
- [ ] Deployment window communicated to stakeholders: [Date]
- [ ] On-call team notified: [Date]
- [ ] Deployment initiated notification sent: [Date/Time]

---

## Production → Support Handoff

**Required for Support Readiness:**

- [ ] **Feature Deployed**: Feature live in production
  - Deployment completion: [Date/Time]
  - Verified by: [DevOps Engineer Name] | Date: ____
  
- [ ] **Post-Deploy Smoke Tests**: Critical paths validated in production
  - Test results: ________________
  - Verified by: [QA/DevOps Name] | Date: ____
  
- [ ] **Monitoring Checks**: Alerts and metrics showing healthy state
  - Verified by: [DevOps Engineer Name] | Date: ____
  
- [ ] **Support Documentation**: User guides and troubleshooting docs available
  - Documentation links: ________________
  - Verified by: [Technical Writer Name] | Date: ____
  
- [ ] **Known Issues**: Any known limitations or workarounds documented
  - Known issues location: ________________
  - Verified by: [QA/PdM Name] | Date: ____
  
- [ ] **Support Training**: Support team briefed on new feature
  - Training session: [Date] or training materials location: ________________
  - Verified by: [PdM/Support Lead Name] | Date: ____
  
- [ ] **Escalation Path**: Support escalation process confirmed
  - On-call contact: ________________
  - Verified by: [PM Name] | Date: ____
  
- [ ] **Customer Communication**: If applicable, customer announcement sent
  - Communication sent: [Date]
  - Verified by: [PdM/Marketing Name] | Date: ____

**Notifications Sent:**
- [ ] Support team notified of launch: [Date]
- [ ] Feature metrics dashboard shared with team: [Date]
- [ ] Post-launch review scheduled: [Date]

---

## Notes
- Customize this checklist based on your project's specific needs
- Not all items may be required for every feature (e.g., simple bug fixes may skip some steps)
- Add project-specific requirements as needed
- Archive completed checklists for retrospective review
