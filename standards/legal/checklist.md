# GDPR / EU Privacy Compliance Checklist

## 1. Data Collection

- [ ] Collect only data necessary for the intended purpose
- [ ] Define the purpose for every collected personal-data field
- [ ] Identify the legal basis for each processing activity
- [ ] Do not collect personal data "just in case"
- [ ] Avoid collecting sensitive/special-category data unless legally justified

## 2. Forms

- [ ] Every form collects only necessary fields
- [ ] Required fields are actually required
- [ ] Users are informed about how submitted data will be used
- [ ] Privacy notice is accessible before/at the point of collection
- [ ] Marketing consent is separate from necessary form submission
- [ ] Consent is not pre-selected
- [ ] Consent can be withdrawn

## 3. Authentication & Accounts

- [ ] Store only necessary account information
- [ ] Never store plaintext passwords
- [ ] Use secure password hashing where applicable
- [ ] Do not expose personal data in URLs
- [ ] Do not expose personal data in client-side logs
- [ ] Protect authenticated endpoints
- [ ] Implement appropriate session expiration
- [ ] Allow account/data deletion where applicable

## 4. API

- [ ] Validate incoming data
- [ ] Authorize every protected request
- [ ] Return only the data required by the client
- [ ] Do not expose internal database fields unnecessarily
- [ ] Do not expose secrets or credentials in API responses
- [ ] Avoid logging personal data
- [ ] Apply appropriate rate limiting where necessary

## 5. Database & Storage

- [ ] Define what personal data is stored
- [ ] Define why each field is stored
- [ ] Define retention periods
- [ ] Delete/anonymize data when it is no longer necessary
- [ ] Do not retain data indefinitely
- [ ] Restrict database access
- [ ] Encrypt data where appropriate
- [ ] Backups follow the same privacy requirements

## 6. Logs & Monitoring

- [ ] Do not log passwords
- [ ] Do not log access tokens
- [ ] Do not log API keys
- [ ] Avoid logging email addresses unless necessary
- [ ] Avoid logging IP addresses unless necessary
- [ ] Define log retention periods
- [ ] Restrict access to logs

## 7. Cookies & Browser Storage

- [ ] Identify all cookies
- [ ] Identify localStorage/sessionStorage usage
- [ ] Classify cookies by purpose
- [ ] Necessary cookies are separated from optional tracking
- [ ] Non-essential tracking requires appropriate consent
- [ ] Consent preferences are respected before optional tracking starts
- [ ] Users can change/revoke their preferences

Cookies and similar technologies need to be considered separately from general GDPR processing; the EU ePrivacy framework is relevant here as well. :contentReference[oaicite:1]{index=1}

## 8. Analytics & Tracking

- [ ] Identify every analytics/tracking service
- [ ] Document what data each service receives
- [ ] Verify the legal basis
- [ ] Do not initialize optional tracking before required consent
- [ ] Do not send unnecessary personal data to analytics providers
- [ ] Provide a way to withdraw tracking consent

## 9. Third-Party Services

- [ ] Maintain an inventory of third-party services
- [ ] Document what personal data is shared with each provider
- [ ] Verify the provider's privacy/data-processing terms
- [ ] Determine whether a DPA is required
- [ ] Check international data transfers
- [ ] Do not send personal data to third parties unnecessarily

## 10. International Data Transfers

- [ ] Identify services processing data outside the EU/EEA
- [ ] Document the transfer mechanism where required
- [ ] Check applicable safeguards
- [ ] Document relevant subprocessors

## 11. User Rights

- [ ] Support access requests
- [ ] Support correction requests
- [ ] Support deletion requests
- [ ] Support restriction requests where applicable
- [ ] Support data portability where applicable
- [ ] Support objection where applicable
- [ ] Provide a way to withdraw consent
- [ ] Verify identity appropriately before fulfilling requests

## 12. Data Retention

- [ ] Define retention period for each category of personal data
- [ ] Automatically delete data where practical
- [ ] Do not keep inactive accounts indefinitely without justification
- [ ] Define retention for backups
- [ ] Define retention for logs

## 13. Security

- [ ] Use HTTPS
- [ ] Keep dependencies updated
- [ ] Protect secrets using environment variables/secrets management
- [ ] Never commit credentials
- [ ] Apply least-privilege access
- [ ] Protect sensitive endpoints
- [ ] Validate and sanitize untrusted input
- [ ] Use secure authentication/session mechanisms
- [ ] Encrypt sensitive data where appropriate

## 14. Privacy by Design / Default

- [ ] Privacy considered during feature design
- [ ] Privacy-friendly defaults are used
- [ ] Minimum necessary data is processed
- [ ] Access to personal data is limited
- [ ] Personal data is not exposed by default

GDPR explicitly requires privacy by design and by default to be considered from the beginning of processing activities. :contentReference[oaicite:2]{index=2}

## 15. Data Breaches

- [ ] Have a process for detecting security incidents
- [ ] Have a process for assessing personal-data breaches
- [ ] Document incidents
- [ ] Define notification responsibilities
- [ ] Define escalation procedures

## 16. Documentation & Accountability

- [ ] Maintain a data-processing inventory
- [ ] Document legal basis for processing
- [ ] Document third-party processors
- [ ] Document retention periods
- [ ] Document security measures
- [ ] Review privacy requirements when introducing new features
- [ ] Keep privacy documentation synchronized with the actual implementation

## 17. Development Rules

- [ ] Do not add a new personal-data field without documenting its purpose
- [ ] Do not add a new third-party service without privacy review
- [ ] Do not add analytics/tracking without checking consent requirements
- [ ] Do not log personal data unnecessarily
- [ ] Do not expose personal data through API responses unnecessarily
- [ ] Do not store data indefinitely
- [ ] Review privacy impact when introducing new features
