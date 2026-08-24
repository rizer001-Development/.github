# 🏗️ .github

Organization-wide configuration and community health files for **[rizer001-Development](https://github.com/rizer001-Development)**.

---

## 📌 What is this repository?

This repository contains files that apply across the entire **rizer001-Development** organization:

- **Community health files** — Contributing guidelines, Security policy, Code of Conduct
- **Issue & PR templates** — Standardized forms for bug reports, feature requests, and pull requests
- **Organization profile** — The public README displayed on our [organization page](https://github.com/rizer001-Development)

These files are automatically referenced by GitHub across all repositories in the organization.

---

## 📂 Repository Structure

```
.github/
├── README.md                    # This file
├── LICENSE                      # License for this repository
├── CONTRIBUTING.md              # Contribution guidelines for all projects
├── SECURITY.md                  # Vulnerability reporting policy
├── CODE_OF_CONDUCT.md           # Community standards (Contributor Covenant 2.1)
├── PULL_REQUEST_TEMPLATE.md     # PR template for all repositories
├── ISSUE_TEMPLATE/
│   ├── bug_report.yml           # Structured bug report form
│   ├── feature_request.yml      # Structured feature request form
│   └── config.yml               # Disables blank issues, links to Discussions/Discord
└── profile/
    └── README.md                # Organization profile (shown on org page)
```

---

## 🔄 How it works

GitHub automatically looks for these files in the `.github` repository as a **fallback**:

| File | Effect |
|------|--------|
| `CONTRIBUTING.md` | Linked when someone opens their first PR in any org repo |
| `SECURITY.md` | Shown in the Security tab of every org repo |
| `CODE_OF_CONDUCT.md` | Linked when creating Issues/PRs |
| `ISSUE_TEMPLATE/` | Available in every org repo's "New Issue" page |
| `PULL_REQUEST_TEMPLATE.md` | Auto-attached to every new PR |
| `profile/README.md` | Displayed on the [organization homepage](https://github.com/rizer001-Development) |

Individual repositories can override any of these by adding their own version of the file.

---

## 📝 Contributing

If you want to improve these templates or guidelines:

1. Fork this repository
2. Edit the relevant file
3. Open a Pull Request with a clear description of the change

---

## 📄 License

This repository is licensed under **AGPL-3.0**, consistent with all projects in the organization.
