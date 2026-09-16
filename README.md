# Secure GitHub Actions

Reusable workflow examples for security scanning with least-privilege workflow permissions.

## Included workflows

- **CodeQL** for code and dependency analysis.
- **Dependency review** for pull requests, blocking newly introduced vulnerable dependencies.
- **Trivy** for filesystem, secret, and infrastructure-as-code scanning.
- **Dependabot** to keep GitHub Actions and npm dependencies updated.

## Adopt safely

Copy the workflow that matches your repository and tailor languages, paths, and required checks. Start every workflow with the smallest `permissions` block it needs. Pin third-party actions to full commit SHAs in production repositories and keep those pins updated with Dependabot.

Security scanners produce signals, not a replacement for review: investigate findings, set branch protection rules, and use protected environments for deployment credentials.
