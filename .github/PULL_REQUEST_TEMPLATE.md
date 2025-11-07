# Security PR Checklist

Before merging, ensure the following:

- [ ] Server-side auth checks implemented
- [ ] Input validation & encoding applied
- [ ] Secrets not in code/config
- [ ] Dependencies scanned/updated
- [ ] Secure headers / CORS verified
- [ ] Unit/integration tests for critical flows
- [ ] Threat model updated if data flow/trust boundaries changed
