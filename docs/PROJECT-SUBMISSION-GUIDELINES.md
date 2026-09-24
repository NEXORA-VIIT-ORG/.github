# Project Submission Guidelines

## NEXORA Student Chapter – VIIT

At **NEXORA Student Chapter – VIIT**, we encourage all students to build projects, showcase their technical work, and contribute to our open-source ecosystem. This guide outlines how students can submit new projects to the organization.

---

## 1. Project Submission Lifecycle

Submitting a project to NEXORA follows a structured 9-step pathway:

```text
Project Idea
    │
    ▼
  Issue (Project Submission Template)
    │
    ▼
Development (Local / Fork / Branch)
    │
    ▼
Documentation (README, Setup, License)
    │
    ▼
Pull Request (or Repository Transfer Request)
    │
    ▼
Technical Review (technical-team assessment)
    │
    ▼
Improvements (Addressing review feedback)
    │
    ▼
  Approval
    │
    ▼
  Merge (or Repo Adoption into NEXORA-VIIT-ORG)
```

---

## 2. Step-by-Step Submission Process

### Step 1: Submit a Project Issue
- Go to the [`NEXORA-VIIT-ORG/.github`](https://github.com/NEXORA-VIIT-ORG/.github/issues) repository (or designated student projects repository).
- Click **New Issue** and select the **Project Submission** template.
- Fill out project details: Project Name, Tech Stack, Team Members, Description, Demo/Repo links, and Learning Outcomes.

### Step 2: Technical Triage & Mentor Assignment
- A member of the `technical-team` will review your submission issue.
- A **Project Lead / Mentor** (a Technical Member or designated mentor) will be assigned to assist you with repository setup, code reviews, and technical guidance.

### Step 3: Development & Documentation
- Build your project following our [DEVELOPMENT-STANDARDS.md](DEVELOPMENT-STANDARDS.md).
- Ensure your repository includes:
  - Clear `README.md` with installation and usage instructions.
  - `.gitignore` file to exclude build artifacts and secrets.
  - Clean folder structure and readable code.

### Step 4: Technical Review & Refinement
- The assigned Project Lead / Mentor reviews code structure, responsiveness, security, and documentation.
- Implement requested refinements or optimization suggestions.

### Step 5: Approval & Onboarding
- Upon final approval by a Technical Lead or designated Technical Member, your project is officially accepted into **NEXORA Student Chapter – VIIT**!

---

## 3. Repository Allocation Criteria

To keep the organization clean and easy to navigate, NEXORA uses two hosting models for student projects:

### Model A: Shared Student-Projects Repository
**Best for**:
- Small utility scripts, single-page experiments, or beginner practice projects.
- Course assignments, minor hackathon prototypes, or single-file tools.
- Group collections of mini-projects built during NEXORA workshops.

*These projects reside as subdirectories within a shared `student-projects` repository.*

### Model B: Standalone Repository in `NEXORA-VIIT-ORG`
**Best for**:
- Full-stack applications, major capstone projects, or long-term open-source utilities.
- Projects with multi-developer team contributions and active issue roadmaps.
- High-impact hackathon winners or projects intended for public deployment and student collaboration.

*The `technical-team` evaluates your project submission issue, with the Technical Lead or designated Technical Member making the final allocation decision on whether to allocate a dedicated repository under `NEXORA-VIIT-ORG`.*
