# IS218 Career Portfolio — Technical Architecture

## Architecture Overview

The career research website will use a simple static architecture.

```text
GitHub Repository
       |
       v
GitHub Pages
       |
       v
Visitor's Web Browser
       |
       v
HTML + CSS + JavaScript
       |
       v
Career Research and Portfolio Planning Content
```

Visitors will open the public website and read career research directly in their browsers.

## Technology Choices

- HTML5: Structure the website and research sections.
- CSS3: Provide professional styling and responsive layouts.
- Vanilla JavaScript: Add small interactions if necessary.
- GitHub: Store code, documentation and peer feedback.
- GitHub Pages: Host the publicly accessible website.
- GitHub Actions: Run planned automated checks.

## Alternative Technologies

### Plain HTML vs. React
React provides reusable components and state management but introduces additional dependencies and build steps.

Plain HTML, CSS and JavaScript are sufficient for this small research website.

Decision: Use plain HTML, CSS and JavaScript.

### GitHub Pages vs. Server Hosting
GitHub Pages supports static websites and integrates with GitHub repositories.

Server hosting could support dynamic applications but would add complexity and potentially cost.

Decision: Use GitHub Pages.

## Information Architecture

The research website will include:

1. Research Question and Audience
2. Employer Research: OpenAI, Gamma and Optum
3. Career Direction Comparison
4. Portfolio Design Comparison
5. Evidence, Assumptions and AI Verification
6. Research Sources and Dates Checked
7. Next Steps and Related Research Website

The future professional portfolio will be planned around Home, About, Projects, Skills and Contact sections.

## Code Structure

```text
career-portfolio/
    README.md
    index.html
    styles.css
    script.js
    docs/
        plan.md
        architecture.md
        testing.md
        research.md
```

index.html: Page content and semantic structure.

styles.css: Colors, typography, layout and responsive design.

script.js: Optional interactive behavior.

docs/: Planning, research and testing documents.

## Reusable Components and Maintainability

The website will use consistent header, navigation, section and footer styles.

Repeated employer research sections will follow a common layout.

Content, presentation and optional behavior will be separated into HTML, CSS and JavaScript.

This supports the Single Responsibility Principle without requiring unnecessary design patterns.

## Accessibility and Responsive Design

- Use semantic HTML and descriptive headings.
- Make navigation usable with a keyboard.
- Provide alternative text for meaningful images.
- Maintain readable color contrast.
- Use responsive layouts that work on phones and computers.
- Avoid unnecessary animations.

## Data, Privacy and Security

The site does not collect user information or store private records.

No backend, database or authentication system is required.

Personal career reflections and eligibility circumstances will remain in the private Canvas submission rather than the public GitHub repository.

External links will use appropriate security attributes when opening new tabs.

## Hosting and Cost Assumptions

GitHub Pages is planned for hosting the public research website.

A public GitHub repository is sufficient for this project.

No paid hosting or external API is currently required.

Deployment and public access must still be verified.

## Testing and Deployment

Planned checks include:

- HTML validation
- Navigation and external links
- Mobile responsiveness
- Keyboard accessibility
- Image alternative text
- GitHub Pages deployment
- Original employer source verification

Tests will be documented in docs/testing.md.

## Current Status

Architecture planned.

Website implementation, automated checks and deployment verification have not yet been completed.
