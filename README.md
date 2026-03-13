<div align="center">

<img src="./assets/Github-templates.png" alt="GitHub Templates logo" width="140" />

# GitHub Templates

Professional, reusable templates for GitHub issues, pull requests, and project README files.

<!-- Optional CI/CD badges (uncomment when available) -->
<!-- ![Build Status](https://img.shields.io/github/actions/workflow/status/BREBION-Mathis/Github-templates/ci.yml?style=flat-square&logo=github) -->
<!-- ![Deployment](https://img.shields.io/github/deployments/BREBION-Mathis/Github-templates/production?style=flat-square&label=deployment) -->

</div>

---

## Why This Repository

This repository helps you bootstrap professional GitHub collaboration standards in minutes.

- Standardized issue reports for faster triage
- Clear feature requests with acceptance criteria
- Structured pull request reviews
- Ready-to-customize project README template

---

## Included Templates

| Template                     | Purpose                                                        |
| ---------------------------- | -------------------------------------------------------------- |
| `templates/ISSUE_BUG.md`     | Bug report with severity, environment, logs, and checklist     |
| `templates/ISSUE_FEATURE.md` | Feature request with problem statement and acceptance criteria |
| `templates/PR.md`            | Pull request template with testing and security sections       |
| `templates/README.md`        | Generic README starter for software projects                   |

---

## Quick Start

1. Clone this repository:

```bash
git clone https://github.com/BREBION-Mathis/Github-templates.git
cd Github-templates
```

2. Copy templates into your target project:

```bash
# From your target project root
mkdir -p .github/ISSUE_TEMPLATE

cp /path/to/Github-templates/templates/ISSUE_BUG.md .github/ISSUE_TEMPLATE/bug_report.md
cp /path/to/Github-templates/templates/ISSUE_FEATURE.md .github/ISSUE_TEMPLATE/feature_request.md
cp /path/to/Github-templates/templates/PR.md .github/pull_request_template.md
cp /path/to/Github-templates/templates/README.md README.md
```

3. Customize placeholders:

- Replace `<username>/<repo>` values in shields
- Adapt workflows, branch strategy, and contribution rules
- Keep sections that match your stack and team process

---

## Recommended Folder Layout in Your Project

```text
your-project/
  .github/
    ISSUE_TEMPLATE/
      bug_report.md
      feature_request.md
    pull_request_template.md
  README.md
```

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a branch: `feature/your-improvement`
3. Commit using clear messages
4. Open a pull request with context and examples

---

## License

Released under the MIT License. See [LICENSE](./LICENSE).
