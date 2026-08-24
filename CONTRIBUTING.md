# Contributing to rizer001-Development

Thank you for your interest in contributing! This guide applies to all repositories under the **rizer001-Development** organization.

---

## 🚀 Getting Started

1. **Find a project** — browse our [repositories](https://github.com/rizer001-Development) and pick one that interests you.
2. **Read the project's README** — each project may have specific setup instructions.
3. **Check existing Issues and Discussions** — your idea or bug might already be tracked.

---

## 📋 How to Contribute

### 🐛 Reporting Bugs

- Open an **Issue** in the relevant repository.
- Use the **Bug Report** template if available.
- Include:
  - Steps to reproduce
  - Expected vs. actual behavior
  - Environment (OS, Java version, mod/loader version if applicable)
  - Screenshots or logs if relevant

### 💡 Suggesting Features

- Open an **Issue** or start a **Discussion** depending on scope.
- Describe the problem you're trying to solve, not just the solution.
- Explain why this feature would be useful to others.

### 🔧 Submitting Code

1. **Fork** the repository.
2. **Create a branch** from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** — keep commits focused and descriptive.
4. **Test** your changes locally before submitting.
5. **Push** to your fork and open a **Pull Request** against `main`.

---

## ✅ Pull Request Guidelines

- Use a clear, descriptive title (e.g., "Fix crash when loading empty sound file").
- Reference related Issues (e.g., "Closes #42").
- Describe **what** changed and **why**.
- Keep PRs focused — one feature or fix per PR.
- Ensure the project builds without errors before submitting.

### Code Style

| Project | Language | Style |
|---------|----------|-------|
| Java projects | Java | Follow standard Java conventions (Google Java Style or project-specific `.editorconfig`) |
| SoundPad, DevChats | Kotlin | Follow Kotlin coding conventions |
| rizer001_Website | TypeScript | Follow the project's ESLint/Prettier config |

### Commit Messages

- Use **present tense** ("Add feature" not "Added feature").
- Use **imperative mood** ("Fix bug" not "Fixes bug").
- Keep the first line under 72 characters.
- Reference issues when applicable: `Fix crash on empty input (#12)`.

---

## 🏗️ Development Setup

Each project has its own build system:

| Project | Build Tool | Command |
|---------|-----------|---------|
| Java/Kotlin (Gradle) | Gradle | `./gradlew build` |
| rizer001_Website | npm | `npm install && npm run dev` |

Make sure you have the required JDK version (usually **Java 21+**) installed.

---

## 📜 License

By contributing, you agree that your contributions will be licensed under the same **AGPLv3** license as the project you're contributing to.

---

## 💬 Questions?

- Start a [Discussion](https://github.com/rizer001-Development/Discussions/discussions) for general questions.
- Join our [Discord](https://dsc.gg/rizer001-Development) for real-time help.
- Open an Issue for project-specific questions.

---

Thank you for helping make rizer001-Development better! 🎉
