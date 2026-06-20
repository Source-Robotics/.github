# Contributing Guidelines

*Pull requests, bug reports, and all other forms of contribution are welcome and highly encouraged!* :octocat:  

## How You Can Contribute to Source Robotics

There are three main ways to support our projects:  

1. **Contribute your expertise**  
   - Share ideas and feedback on [Discord](https://discord.gg/prjUvjmGpZ) or the [forum](https://forum.source-robotics.com/).  
   - Help improve hardware designs, firmware, documentation, or software.

2. **Purchase our products**  
   - Support ongoing development by visiting our [store](https://source-robotics.com/).

3. **Donate**  
   - [Patreon](https://www.patreon.com/c/PCrnjak)  
   - [PayPal](https://www.paypal.com/paypalme/PCrnjak?locale.x=en_US)  
   - [GitHub Sponsors](https://github.com/sponsors/PCrnjak)  

---

## Reporting Bugs

If you’ve found a bug, please open an issue on GitHub with:  
- A clear **title**  
- A **description** of the problem  
- Optional: **screenshots** or logs to illustrate the issue  

Before creating an issue, please check if it has already been reported.

---

## Code Quality Standards

Before submitting a patch, ensure your code meets these standards:

### One Feature or Fix Per Pull Request
- Keep PRs **focused and scoped** — one feature or bug fix per PR.
- Avoid mixing unrelated changes (refactoring + new feature = two PRs).
- Smaller PRs are easier to review, test, and merge.

### Clean Code Practices
- Follow the **existing code style** in the repository.
- Write **readable, self-documenting code** with clear variable and function names.
- Remove debug prints, commented-out code, and unnecessary changes.
- Add **comments only where the "why" isn’t obvious** — the code should speak for itself.
- Keep functions and methods **focused and reasonably sized**.

### Commit Message Style
Write clear, descriptive commit messages that follow this format:

```
Short summary (50 characters or less)

Longer explanation if needed. Explain the problem you’re solving
and why this approach was chosen. Keep it concise but informative.
```

**Examples:**
- ✅ `Fix motor calibration offset calculation`
- ✅ `Add WiFi reconnection retry logic`
- ✅ `Update documentation for build process`
- ❌ `Fix bug` (too vague)
- ❌ `Random changes` (not descriptive)

### Testing & Documentation
- **Test your changes** — verify the fix works or the feature behaves as expected.
- **Update documentation** if you’re adding new features or changing behavior.
- **Include relevant details** in your PR description (what was tested, how to verify).

---

## Submitting Patches

> [!CAUTION]
> Please do not push to main branch of the github repos!
>

### Workflow

#### 1. Fork and Clone
Start by forking the repository to your GitHub account. Click the **Fork** button in the top-right corner, then clone your fork locally:

```bash
git clone https://github.com/{your_username}/repo-name.git
cd repo-name
git remote add upstream https://github.com/source-robotics/repo-name.git
```

This creates two remotes: `origin` (your fork) and `upstream` (the official repo).

#### 2. Create a Development Branch
Create a feature branch based on the latest main:

```bash
git pull upstream main
git checkout -b {feature-name}
```

Use descriptive branch names (e.g., `fix-motor-calibration`, `add-wifi-support`).

#### 3. Make Changes and Commit
- Make your changes and test them thoroughly.
- Keep commits **clean and atomic** — one commit per logical change.
- Write clear commit messages explaining the **why**, not just the what.
- Avoid mixing unrelated changes in a single PR (one feature or fix per PR).

#### 4. Push and Create a Pull Request
Push your branch to your fork:

```bash
git push -u origin {feature-name}
```

Then open a pull request on GitHub with:
- A clear **title** describing the change
- A **description** that explains:
  - The problem you’re solving
  - How your changes fix it
  - Any testing you’ve done
- Link related **issues** if applicable

#### 5. Address Feedback
- Respond to review comments from maintainers.
- Make requested changes on the same branch and push again.
- The PR updates automatically with your new commits.

---

---

## Not Sure Where to Start?

- Look for GitHub issues labeled **"help wanted"**.  
- Join the conversation on [Discord](https://discord.gg/prjUvjmGpZ) or the [forum](https://forum.source-robotics.com/).
- TODO Check the **project roadmap** for upcoming features.
- COMING SOON - bounties!
---

## Final Note

We warmly welcome all proposals to improve Source Robotics.  
Join the discussion, share your ideas, and help us make robotics more accessible for everyone!
