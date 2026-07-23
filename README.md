# Open Source Security Contributions

This repository tracks verifiable contributions to open-source cybersecurity,
application security, AI and agent security, secure software development,
testing, CI/CD, and developer tooling.

## Contribution Principles

- Reproduce before changing
- Avoid duplicate work
- Keep patches focused
- Add regression tests
- Follow project contribution and disclosure policies
- Report sensitive vulnerabilities privately
- Respond to maintainer feedback
- Record only verifiable results

## Contributions

| Organization | Repository | Contribution | Technology | PR | Status |
| --- | --- | --- | --- | --- | --- |
| OWASP | cve-lite-cli | Use a callable type for injected fetch implementations | TypeScript, Vitest | [#886](https://github.com/OWASP/cve-lite-cli/pull/886) | Open |
| OWASP | www-project-csrfguard | Return the master token in the AJAX response header | Java, JUnit | [#400](https://github.com/OWASP/www-project-csrfguard/pull/400) | Open |
| OWASP | www-project-secure-headers | Parse millisecond timeout values correctly in the link checker | Python, CI/CD | [#312](https://github.com/OWASP/www-project-secure-headers/pull/312) | Open |
| OWASP | Agent-Security-Regression-Harness | Enforce recipient allowlists for collections and carbon-copy fields | Python, pytest | [#160](https://github.com/OWASP/Agent-Security-Regression-Harness/pull/160) | Open |
| OWASP | www-project-ai-testing-guide | Make PDF rebuild paths independent of the caller's working directory | Python, PDF tooling | [#84](https://github.com/OWASP/www-project-ai-testing-guide/pull/84) | Open |
| OWASP | www-project-top-10-for-large-language-model-applications | Replace a corrupt 2025 PDF and add render-integrity validation | Python, PDF tooling | [#861](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/pull/861) | Open |
| OWASP | www-project-agent-memory-guard | Pin workflow actions and downloaded tooling to immutable revisions | GitHub Actions, Python | [#54](https://github.com/OWASP/www-project-agent-memory-guard/pull/54) | Open |
| OWASP | www-project-ai-maturity-assessment | Restore the documented toolkit scoring scale and validate formulas | Python, Excel, PDF | [#90](https://github.com/OWASP/www-project-ai-maturity-assessment/pull/90) | Open |
| OWASP | www-project-promptme | Make Box-based challenge scenarios reproducible with local fixtures | Python, pytest, CI/CD | [#17](https://github.com/OWASP/www-project-promptme/pull/17) | Open |
| OWASP | PwnzzAI | Use CPU-only PyTorch packaging and reduce the Docker image footprint | Docker, Python, pytest | [#17](https://github.com/OWASP/PwnzzAI/pull/17) | Open |
| Independent | appsec-agent | Restrict environment variables inherited by child processes | TypeScript, Jest | [Compare](https://github.com/yangsec888/appsec-agent/compare/main...rksharma-owg:appsec-agent:codex/isolate-codex-child-environment?expand=1) | Awaiting submission |

## Focus Areas

- AI and agent security
- Application security
- Security regression testing
- Secure CI/CD
- Software supply-chain security
- Developer tooling
- Docker and reproducible builds
- TypeScript, Java, Python, and test automation

## Status Legend

- **Merged** — accepted into the upstream default branch.
- **Open** — submitted upstream and awaiting review or merge.
- **Draft** — submitted upstream but not yet ready for maintainer review.
- **Awaiting submission** — a validated branch exists, but a required
  pre-submission step is still pending.
- **Closed** — closed without being merged.
- **Superseded** — replaced by another contribution or upstream change.
