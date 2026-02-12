# Contributing to Mirava

Thank you for your interest in contributing to **Mirava**! 🎉  
We welcome contributions — whether they’re bug fixes, documentation improvements, mirror additions, or new features that benefit the community.

This document outlines our recommended process and expectations for submitting contributions.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Ways to Contribute](#ways-to-contribute)
- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Adding or Updating Mirrors](#adding-or-updating-mirrors)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Reporting Issues](#reporting-issues)
- [Style Guidelines](#style-guidelines)
- [License](#license)

---

## Code of Conduct

We expect all contributors to follow the project’s **Code of Conduct**.  
Please review the `CODE_OF_CONDUCT.md` before participating.

Be respectful, constructive, and collaborative.

---

## Ways to Contribute

There are many ways to contribute:

- 🐛 Reporting bugs
- 💡 Suggesting improvements
- 🛠 Adding features
- 📚 Improving documentation
- 📦 Adding or updating mirror entries

Every contribution matters.

---

## Getting Started

1. **Fork** the repository on GitHub.
2. **Clone** your fork locally:

```bash
git clone https://github.com/YOUR_USERNAME/Mirava.git
```

3. Navigate into the project folder.
4. Create a new branch for your work:

```bash
git checkout -b feature/your-feature-name
```

5. Make your improvements or additions.

---

## Development Workflow

- Keep commits small and focused.
- Write clear, descriptive commit messages.
- Follow the existing structure and formatting style.
- Test your changes before submitting.

Example commit message format:

```text
feat: add npm mirror validation script
fix: correct mirror URL formatting
docs: improve README setup section
```

---

## Adding or Updating Mirrors

Mirava maintains a curated list of package mirrors.

When contributing a new mirror:

1. Ensure it is stable and publicly accessible.
2. Add its details to `mirrors_list.yaml`.
3. If needed, update or add scripts under the `scripts/` directory.
4. Verify accessibility (ideally without VPN).
5. Provide a short description of the mirror’s purpose and supported packages.

Make sure formatting stays consistent with existing entries.

---

## Pull Request Guidelines

When your changes are ready:

1. Push your branch:

```bash
git push origin feature/your-feature-name
```

2. Open a **Pull Request** against the `main` branch.
3. Include in your PR description:
   - What you changed
   - Why the change is needed
   - Any related issue numbers

Be responsive to feedback. Maintainers may request revisions before merging.

---

## Reporting Issues

If you find a bug, please open a GitHub issue and include:

- A clear title
- Steps to reproduce
- Expected behavior
- Actual behavior
- Logs or screenshots (if applicable)

Detailed reports help us fix problems faster.

---

## Style Guidelines

- Follow existing YAML and code formatting.
- Avoid unnecessary reformatting of unrelated files.
- Keep documentation concise and clear.
- Use meaningful branch names:
  
```text
feature/add-npm-mirror
fix/yaml-validation
docs/update-readme
```

---

## License

By contributing to Mirava, you agree that your contributions will be licensed under the same license as the project.

---

Thank you for helping improve Mirava 🚀  
Your contributions make the ecosystem stronger.
