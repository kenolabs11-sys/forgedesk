# Contributing to ForgeDesk

Thanks for taking the time to contribute! ForgeDesk is a deterministic build orchestrator, and we care a lot about reproducibility, safety, and clear bug reports.

## Where to post what (Important)

### ✅ Bugs / Crashes / Build failures
Open an **Issue** using:
- **Bug report** template

### ✅ Feature requests / Improvements
Open an **Issue** using:
- **Feature request** template

### ✅ Questions / Usage help
Use **Discussions → Q&A**

### ✅ General ideas / workflow suggestions
Use **Discussions → Ideas**

### ✅ Feedback on UX / behavior
Use **Discussions → Feedback**

---

## Before you open an Issue

Please check:
- Existing Issues (duplicates)
- README (basic usage)
- Discussions (if it's a question)

---

## Bug Reports (What we need)

A good bug report includes:

1. **ForgeDesk version** (e.g. `0.1.0-preview`)
2. **Operating System** (Windows 10/11, build number if possible)
3. **Pipeline** (Python / .NET / Unknown)
4. **Expected behavior**
5. **Actual behavior**
6. **Steps to reproduce**
7. **Diagnostics ZIP file name** (if available)

### Diagnostics ZIP Safety
- Please **do not include secrets** (API keys, passwords, private tokens).
- If a log contains sensitive paths or usernames, you may redact them.

---

## Feature Requests (What we need)

- What problem are you solving?
- What is your desired workflow?
- Any alternatives you tried?
- Optional: screenshots or mockups

---

## Pull Requests (If/When PRs are enabled)

> At the moment ForgeDesk may accept PRs selectively. If PRs are not accepted yet, please open an Issue/Discussion first.

### Quality rules
- Keep changes focused (one feature/fix per PR)
- Add tests if relevant
- Avoid breaking deterministic behavior
- Prefer manifest-first logic; avoid silent installs/updaters

### Commit messages
Use short, clear messages:
- `fix: ...`
- `feat: ...`
- `docs: ...`
- `refactor: ...`

---

## License

By contributing, you agree that your contributions will be licensed under the repository license.
