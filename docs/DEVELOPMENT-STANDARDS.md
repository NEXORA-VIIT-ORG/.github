# Development Standards

## NEXORA Student Chapter – VIIT

To ensure software built within **NEXORA Student Chapter – VIIT** is maintainable, clean, accessible, and secure, all student projects are expected to adhere to these core development standards.

---

## 1. Code Quality & Formatting

- **Clean Folder Structure**: Organize source code logically (e.g., separating components, controllers, styles, utilities, and assets). Avoid dumping all files into the root directory.
- **Meaningful Names**: Use clear, descriptive names for variables, functions, classes, and components (e.g., `calculateTotalScore()` instead of `calc()`, `isUserAuthenticated` instead of `flag`).
- **Use Comments Wisely**: Write self-documenting code. Use inline comments to explain *why* non-obvious logic or workaround exists, rather than stating what the syntax does.
- **Consistent Code Style**: Follow standard formatting conventions for your chosen language (e.g., ESLint/Prettier for JavaScript/TypeScript, PEP 8 for Python).

---

## 2. Repository Hygiene & Documentation

- **Comprehensive README**: Every repository must contain a `README.md` explaining:
  - Project title & description.
  - Features overview.
  - Prerequisites & local setup commands.
  - Usage examples and environment variable requirements.
  - Contributor credits.
- **Proper `.gitignore`**: Always include a framework-appropriate `.gitignore` file to prevent committing generated build folders (`dist/`, `build/`, `.next/`), dependency folders (`node_modules/`, `venv/`), temporary OS files (`.DS_Store`, `Thumbs.db`), and local secrets (`.env`).
- **Avoid Unnecessary Dependencies**: Prefer native APIs or well-maintained lightweight libraries over heavy third-party packages for simple tasks.

---

## 3. Security-Conscious Development

- **Zero Hardcoded Secrets**: Never hardcode API keys, database URLs with passwords, private tokens, or credentials in source code.
- **Input Validation & Sanitization**: Always validate and sanitize user inputs on both frontend and backend to prevent common vulnerabilities (XSS, SQL Injection, Command Injection).
- **Safe Dependency Practices**: Audit project dependencies periodically (`npm audit` or equivalent) to patch known security vulnerabilities.

---

## 4. Frontend & User Interface Standards

For web, mobile, and desktop UI projects:

- **Responsive Design**: Interfaces should render gracefully across desktop, tablet, and mobile viewports.
- **Accessibility (a11y)**: Use semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<button>`, `<section>`), provide `alt` text for images, and ensure adequate color contrast ratios.
- **User Experience (UX)**: Provide feedback for user interactions (loading indicators, clear error messages, confirmation dialogs).

---

## 5. Testing & Verification

- **Local Verification**: Verify all features, routes, and UI states locally before opening a Pull Request.
- **Basic Automated Testing**: Where applicable, include basic unit or integration tests (e.g., testing core helper functions, API endpoints, or critical UI components).
- **No Console Logs in Production**: Remove temporary `console.log()` or debug print statements before submitting PRs for review.

---

## 6. Proper Attribution & Licensing

- **Attribute Resources**: Credit open-source libraries, UI assets, icons, fonts, and tutorials used in your project in the project `README.md`.
- **Open Source Licensing**: Choose an appropriate open-source license (e.g., MIT License) for chapter projects.
