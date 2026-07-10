# Contributing to BuildWithPNJ

Thank you for your interest in contributing to BuildWithPNJ. We maintain high engineering standards to ensure that all code shipped is production-ready, clean, and well-architected.

---

## 🛠️ Development Standards

- **Python**: Code must target Python 3.11+. Follow PEP 8 guidelines. Use typing hints.
- **Frontend**: Next.js 15 (App Router). Maintain clean CSS structure and avoid ad-hoc utility classes outside the design system.
- **Testing**: Every functional module should be accompanied by unit or integration tests (using `pytest` for Python or `Jest` / `Playwright` for frontend).

---

## 📝 Commit Guidelines

We enforce the **Conventional Commits** specification for all commit messages. This allows us to auto-generate changelogs and trace changes accurately.

Format:
```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

### Types:
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation updates
- `style`: Formatting, spacing, linting fixes (no code changes)
- `refactor`: Code changes that neither fix bugs nor add features
- `perf`: Performance improvements
- `test`: Adding missing tests or correcting existing tests
- `chore`: Build process, dependency updates, or auxiliary tool changes

---

## 🚀 Pull Request Workflow

1. **Fork & Branch**: Create a branch off `main` (e.g., `feat/voice-telemetry` or `fix/jwt-auth`).
2. **Implement**: Code your changes, adhering to existing system design.
3. **Document**: Update relevant README sections and inline code docstrings.
4. **Test**: Run all local test suites to verify correctness.
5. **PR Description**: Open a Pull Request referencing any related issues. Outline:
   - What changes were made.
   - Why they were made.
   - How they were verified.
6. **Code Review**: Address feedback from reviewers. Once approved and checks pass, it will be merged.

---

<p align="center">
  <font size="1" color="#475569">
    BUILDWITHPNJ // SYSTEM ENGINEERING PRINCIPLES
  </font>
</p>
