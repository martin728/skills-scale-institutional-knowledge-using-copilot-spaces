# Release Security Checklist

Before each release, confirm that all security controls are in place and vulnerabilities have been addressed.

## Pre-Release Security Review

### Code & Dependency Scanning
- [ ] SAST (static analysis) scan completed; no high/critical findings
- [ ] Dependency scanning completed; all high/critical CVEs resolved
- [ ] Third-party libraries are up-to-date and supported
- [ ] Code review included security considerations

### Authentication & Authorization
- [ ] Authentication mechanism is secure (OAuth, JWT, etc.)
- [ ] Authorization checks are in place for sensitive operations
- [ ] Session management and token expiration are configured
- [ ] Secrets are not hardcoded; using secrets management system

### Data Protection
- [ ] Sensitive data is encrypted in transit (TLS 1.2+)
- [ ] Sensitive data is encrypted at rest (where applicable)
- [ ] No PII/sensitive data in logs or error messages
- [ ] Data retention policies are documented and enforced

### Infrastructure & Deployment
- [ ] Web Application Firewall (WAF) rules are configured
- [ ] Security group / network policies limit access
- [ ] Monitoring and alerting for security events are enabled
- [ ] Deployment uses secure, authenticated channels (no hardcoded credentials)

### Compliance & Legal
- [ ] Privacy policy is updated if data handling changes
- [ ] Terms of service are updated if needed
- [ ] GDPR/compliance requirements are met (if applicable)
- [ ] Audit logging is enabled for sensitive operations

### Known Issues
- [ ] All known security issues are documented with mitigation plans
- [ ] High/critical issues have dates for remediation
- [ ] Low/medium issues are tracked in the backlog

## Sign-off
- [ ] Security Officer approves release from security perspective
- [ ] Compliance Officer approves regulatory requirements
- [ ] Project Manager confirms security blockers are resolved

---

## Post-Release Monitoring
- [ ] Monitor security alerts and logs for 24–48 hours
- [ ] Log any incidents and trigger security incident response if needed