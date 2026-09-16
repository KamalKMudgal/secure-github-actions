# Workflow hardening checklist

- Set the minimum `permissions` at workflow and job scope.
- Do not expose secrets to pull-request workflows from forks.
- Use immutable action commit-SHA pins for third-party actions.
- Keep pins current through Dependabot.
- Require reviews and passing security checks before merge.
- Prefer OpenID Connect and short-lived cloud credentials over long-lived repository secrets.
- Use protected environments for deployments.
