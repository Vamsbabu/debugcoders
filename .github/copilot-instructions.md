# Copilot Instructions for debugcoders

## Project Overview
This project is a collection of HTML files and assets for learning and demonstrating core HTML components and form handling. The structure is organized for educational clarity, with each directory representing a topic or exercise.

## Directory Structure & Key Files
- `htmlintroduction/` — Main entry for HTML learning modules.
  - `index.html` — Introduction or landing page.
  - `corecomponents/` — Demonstrates core HTML elements.
    - `index.html` — Overview of core components.
    - `style.css` — Shared styles for core components.
    - `tasks/froms/` — Exercises and examples related to HTML forms.
      - `application.html`, `registrationpage.html`, etc. — Individual form examples.
      - `img/` — Images used in form examples.

## Patterns & Conventions
- File and folder names are descriptive of their content and purpose (e.g., `studentregistration.html` for a student registration form).
- Each HTML file is self-contained, but may reference shared CSS from its parent directory.
- Images are stored in a local `img/` folder for portability.
- No build system or external dependencies are present; all files are static and can be opened directly in a browser.

## Developer Workflow
- **Preview:** Open any `.html` file directly in a browser to view.
- **Edit:** Modify HTML or CSS files as needed; changes are reflected immediately on refresh.
- **Add New Example:** Copy an existing HTML file as a template, rename, and update content.

## Integration & Extensibility
- No JavaScript or backend integration is present.
- To add interactivity, create a new `.js` file in the relevant directory and link it from the HTML.
- To add new topics, create a new folder under `htmlintroduction/` and follow the existing structure.

## Special Notes
- This project is intended for learning and demonstration; keep examples simple and focused.
- Maintain clear separation between different types of forms and components for easy navigation.

## Example: Adding a New Form
1. Copy an existing form HTML file (e.g., `userregistration.html`).
2. Rename it (e.g., `feedbackform.html`).
3. Update the form fields and content as needed.
4. Add any new images to the `img/` folder.
5. Link to the new form from an index or navigation page.

---
For questions or improvements, update this file or the project `README.md`.
