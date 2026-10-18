<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
  <img alt="StackGuardian" src="assets/logo-light.svg" height="40">
</picture>

One governed path from infrastructure change to production - for humans and AI alike.

## Tirith

[Tirith](https://github.com/StackGuardian/tirith) is our open-source policy engine for the AI generated and operated IaC. It reads the plan your pipeline already produces (`terraform show -json`), checks it against your policies, and exits non-zero so a violating change never reaches `apply`. It's Apache-2.0, needs no account, and runs in the CI you already use.

- [Tirith](https://github.com/StackGuardian/tirith): CLI and policy engine
- [tirith-iac-governance-action](https://github.com/StackGuardian/tirith-iac-governance-action): Tirith as a GitHub Actions step
- [Docs](https://stackguardian.github.io/tirith/docs/getting-started-with-tirith/)

## Working with StackGuardian

| Repository | Use it to |
|---|---|
| [stackguardian-mcp](https://github.com/StackGuardian/add-sg-mcp) | Deploy Terraform, OpenTofu and Ansible with AI agents in minutes. |
| [sg-cli](https://github.com/StackGuardian/sg-cli) | Work with StackGuardian from the command line |
| [terraform-provider-stackguardian](https://github.com/StackGuardian/terraform-provider-stackguardian) | Manage StackGuardian resources with Terraform |

## Links

[Website](https://www.stackguardian.io/) · [Docs](https://docs.stackguardian.io/) · [Community Slack](https://join.slack.com/t/stackguardian-ol78820/shared_invite/zt-2ksag36j9-OjmXqQmyXudgYrV6FmesIQ)
