# Security Policy

## Supported Versions

This is a personal GitHub profile repository. Security updates are applied to:

| Component | Supported |
| --------- | --------- |
| GitHub Actions workflows | ✅ |
| Dependencies | ✅ |
| README.md content | ✅ |

## Reporting a Vulnerability

If you discover a security vulnerability in this repository, please follow these steps:

### 1. Do Not Open a Public Issue

Please do not report security vulnerabilities through public GitHub issues. This helps prevent potential exploitation before a fix can be deployed.

### 2. Report Privately

Send your security report to:

- **Email**: [duyet@duyet.net](mailto:duyet@duyet.net)
- **Subject**: `[SECURITY] Description of the vulnerability`

### 3. Include Detailed Information

Your report should include:

- **Type of vulnerability** (e.g., XSS, injection, broken authentication, etc.)
- **Location** (file path, workflow name, line number if applicable)
- **Step-by-step instructions** to reproduce the issue
- **Potential impact** of the vulnerability
- **Suggested fix** (if you have one)
- **Your GitHub username** (for attribution, optional)

### 4. What to Expect

- **Acknowledgment**: You will receive a response within 48 hours acknowledging your report
- **Updates**: We will keep you informed about the progress
- **Timeline**: We aim to release a fix within 7 days for critical vulnerabilities
- **Credit**: You will be credited for the discovery (unless you prefer to remain anonymous)

## Security Best Practices in This Repository

### GitHub Actions Security

- **Pinned versions**: All actions use specific versions (not `@master` or `@latest`)
- **Least privilege**: Workflows have minimal required permissions
- **Dependabot**: Automatically checks for vulnerable dependencies
- **Secret management**: Sensitive data uses GitHub Secrets

### Link Security

- **Automated checks**: Weekly link validation to prevent phishing
- **HTTPS only**: All external links use HTTPS when available

### Third-party Services

This profile integrates with:

- GitHub Stats (github-readme-stats.vercel.app)
- WakaTime (wakatime.com)
- Typing SVG (readme-typing-svg.demolab.com)
- GitHub Streak (streak-stats.demolab.com)
- Profile Trophy (github-profile-trophy.vercel.app)

These services are trusted and regularly monitored.

## Automated Security

### Dependabot

Dependabot is enabled and configured to:

- Check for GitHub Actions updates weekly
- Check for npm package updates weekly
- Automatically create pull requests for security patches

### Link Checker

An automated workflow runs weekly to:

- Verify all links in README.md
- Report broken or suspicious links
- Create issues for manual review

### Workflow Validation

All GitHub Actions workflows are:

- Linted using actionlint
- Validated on every pull request
- Reviewed for security best practices

## Scope

### In Scope

Security issues related to:

- GitHub Actions workflows
- Exposed secrets or tokens
- Malicious links or content injection
- XSS vulnerabilities in markdown rendering
- Supply chain attacks via dependencies

### Out of Scope

- Issues with third-party services (report to them directly)
- Theoretical vulnerabilities without practical exploit
- Social engineering attacks
- Issues related to GitHub's platform itself

## Security Updates

Security patches are released as soon as possible after verification. Update notifications are sent via:

- GitHub Security Advisories (if applicable)
- Commit messages with `[SECURITY]` prefix
- Release notes

## Recognition

Security researchers who responsibly disclose vulnerabilities will be:

- Credited in the fix commit/PR (unless they prefer anonymity)
- Added to a "Security Hall of Fame" section (if they agree)
- Given a shoutout on social media (with permission)

## Questions?

If you have questions about security but don't want to report a vulnerability:

- Open a public issue with the `security` label
- Email [duyet@duyet.net](mailto:duyet@duyet.net)
- Reach out via [LinkedIn](https://linkedin.com/in/duyet)

## Resources

- [GitHub Security Best Practices](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Dependabot Documentation](https://docs.github.com/en/code-security/dependabot)

---

Thank you for helping keep this repository secure! 🔒
