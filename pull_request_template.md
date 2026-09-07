## 🩺 Description & Motivation
<!-- Provide a clear, concise description of the changes and the clinical/business reason behind them. -->
- **Issue/Ticket Link:** #
- **Feature/Bug Fix/Refactor:** 

## 🛡️ Security, Privacy & Compliance (HIPAA / GDPR / SOC2)
- [ ] **No PII/PHI Leakage:** Verified that no Personally Identifiable Information (PII) or Protected Health Information (PHI) is exposed in logs, error messages, URLs, or client-side storage.
- [ ] **Data Encryption:** Confirmed data is encrypted both in transit and at rest for any database schema or API modifications.
- [ ] **Access Control:** Any new endpoints, resources, or UI components strictly enforce Role-Based Access Control (RBAC) (e.g., patient vs. clinician views).
- [ ] **Audit Logging:** Implemented or verified audit trails for any operations involving creating, reading, updating, or deleting (CRUD) patient data.

## 🧪 Clinical Quality Assurance & Testing
### Automated Testing
- [ ] Unit tests added/updated
- [ ] Integration/E2E tests added/updated
- [ ] Code coverage meets or exceeds project thresholds

### Manual Verification Steps
<!-- Clear instructions on how a reviewer can manually test this change safely. -->
1. Go to...
2. Click on...
3. Verify that...

### Edge Cases Evaluated
- [ ] **Data Anomalies:** Handled null/missing clinical records, boundary values (e.g., extreme lab results, age limits).
- [ ] **Network Failures:** Checked application behavior during intermittent connectivity (critical for point-of-care mobile tools).

## 📸 Visual Documentation (If Applicable)
<!-- Attach screenshots, wireframes, or screen recordings demonstrating UI/UX changes, particularly patient-facing workflows. -->

## 🚀 Deployment & Data Migration Risks
- [ ] **Database Migrations:** Schema changes have been heavily vetted, backfilled safely, and will not cause application downtime.
- [ ] **Feature Flags:** This change is safely wrapped behind a feature flag (`FLAG_NAME`).
- [ ] **Rollback Plan:** Documented strategy to safely revert this change without causing clinical data corruption.
