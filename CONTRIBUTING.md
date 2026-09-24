# Contributing Guidelines for NEXORA Student Chapter – VIIT

Thank you for your interest in contributing to **NEXORA Student Chapter – VIIT**! This organization is built by students, for students, to foster open-source collaboration, hands-on project development, and technical growth.

Whether you are fixing a typo in documentation, squashing a bug, or building a brand-new project feature, your contributions are welcome!

---

## The 13-Step NEXORA Contribution Workflow

To keep our projects organized and easy for everyone to collaborate on, please follow these 13 steps when making a contribution:

1. **Find or Create an Issue**: Check the project's **Issues** tab for existing tasks or create a new issue describing a feature request or bug report.
2. **Discuss the Task**: Comment on the issue to express your interest and clarify details with project leads or technical team members before writing code.
3. **Fork/Clone the Repository**: Clone the repository to your local machine (or fork it first if working from an external account).
4. **Create a Branch**: Create a dedicated, descriptive git branch for your task off `main` or `master`.
5. **Develop the Change**: Write clean, readable code adhering to the project's coding standards.
6. **Test Locally**: Run tests, check for console errors, and verify functionality locally.
7. **Commit Changes**: Create clear, structured git commits following our commit conventions.
8. **Push the Branch**: Push your local branch to GitHub (`git push origin <branch-name>`).
9. **Open a Pull Request**: Submit a Pull Request (PR) referencing the issue you worked on and filling out the PR template.
10. **Technical Member Reviews the PR**: A member of the `technical-team` or project mentor will review your pull request and provide feedback.
11. **Address Requested Changes**: Make any requested adjustments locally, commit them, and push to your branch to update the PR.
12. **Final Approval**: Once all requested changes are satisfied and checks pass, a Technical Lead or designated Technical Member approves the PR.
13. **Merge**: The PR is merged into the main branch, and your contribution becomes part of NEXORA!

---

## Branch Naming Conventions

Always create a new branch for each task or issue. Use one of the following prefixes followed by a concise, hyphenated description:

- `feature/<short-description>`: For new features or additions.
- `fix/<short-description>`: For bug fixes or corrections.
- `docs/<short-description>`: For documentation updates or additions.
- `project/<short-description>`: For newly submitted student projects or major modules.

### Recommended Examples:

```bash
feature/student-dashboard
fix/mobile-navbar
docs/github-guide
project/expense-tracker
```

---

## Commit Message Guidelines

Clear commit messages help maintain repository history and allow mentors to review code efficiently.

### Structure of a Good Commit Message

```text
<type>(<scope>): <short summary in imperative mood>

<optional detailed body explaining WHAT changed and WHY>
```

### Commit Types:
- `feat`: A new feature for the user or system
- `fix`: A bug fix
- `docs`: Documentation changes
- `style`: Formatting, spacing, or cleanups with no code logic changes
- `refactor`: Restructuring code without changing behavior
- `test`: Adding or updating tests
- `chore`: Maintenance, configuration, or dependency updates

### Guidelines:
- Use the **imperative mood** in the subject line (e.g., "Add student dashboard filter" instead of "Added student dashboard filter").
- Capitalize the first letter of the summary (or keep lowercase if adhering to conventional commits).
- Do not end the subject line with a period.
- Keep the subject line under 72 characters.

### Examples:

#### Good Examples:
```bash
# Feature commit
git commit -m "feat(dashboard): add project filtering by tech stack"

# Bug fix commit
git commit -m "fix(navbar): resolve hamburger menu overlap on mobile screens"

# Documentation commit
git commit -m "docs(readme): add installation steps for local backend"
```

#### Detailed Commit Example:
```text
feat(auth): implement student JWT authentication middleware

- Added token verification middleware in src/middleware/auth.js
- Integrated role check for technical-team members
- Updated login route to return refreshed access tokens
```

---

## Code Review & Peer Guidance

Code reviews at NEXORA are educational, friendly, and constructive:

- Technical team members and project mentors review all PRs.
- Feedback focuses on readability, security, standards, and helpful learning tips.
- Don't worry if changes are requested—code reviews are how we all grow as developers!

If you have any questions, reach out to your project mentor or post a comment on your Pull Request.

Happy Coding! 🚀
