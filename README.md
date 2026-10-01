# Iamrabbyte

Independent Security Researcher focused on offensive web security, API security, and adversarial validation.

## Offensive Security Focus

- Web application penetration testing
- API attack surface analysis
- Authentication & authorization testing
- Access control and privilege boundary testing
- Session and token security
- Account recovery and identity flows
- Multi-tenant isolation
- Vulnerability validation
- Exploitability assessment
- Remediation verification

## Selected Research

Public, sanitized case studies from authorized security testing:

- Account Recovery Bypass
- Cross-Tenant Authentication
- AVIF / Next.js Security Validation

[View Security Research Portfolio](https://github.com/Iamrabbyte/security-research-portfolio)

## Approach

I focus on evidence-driven offensive security testing rather than scanner-only findings.

My workflow typically includes:

- mapping application and API attack surfaces;
- establishing baseline and negative controls;
- validating authentication and authorization boundaries;
- reproducing security-impacting behavior;
- separating confirmed impact from theoretical exploitability;
- using synthetic accounts and test data where possible;
- minimizing unnecessary access to real user information;
- restoring modified test state after validation;
- documenting remediation and revalidation results.

## Current Areas of Interest

- Broken access control
- Authentication bypass
- Account takeover paths
- JWT and session handling
- API authorization flaws
- Multi-tenant trust boundaries
- Framework-level vulnerability validation
- WebSocket and real-time application security

## Responsible Testing

All published research is based on systems I own, intentionally vulnerable environments, or systems where I have explicit authorization to assess.

Sensitive information, credentials, tokens, exact exploit inputs, real user data, and operational target details are excluded from public case studies.

---

`root@rabbyte:~# research --scope authorized`
