# IS218 Career Portfolio — Testing Plan

## Testing Goal
Ensure that the career research website is readable, accessible, accurate, and usable on different devices.

All checks are currently planned, not completed.

## Navigation Tests
- Homepage loads correctly.
- Navigation links open the correct sections.
- GitHub repository links work.
- Family Sudoku research website link works.
- Invalid links or missing sections are identified.

## Responsive Design Tests
- Website displays correctly on desktop screens.
- Website displays correctly on mobile screens.
- Text remains readable at narrow screen widths.
- No horizontal scrolling is required.
- Navigation remains usable on small screens.

## Accessibility Tests
- Images have meaningful alternative text.
- Headings use a logical hierarchy.
- Links have descriptive names.
- Keyboard navigation works.
- Text and background have sufficient contrast.

Tools: Browser developer tools and Lighthouse.

## Research Verification Tests
- OpenAI employer description is checked against the original employer source.
- Gamma employer description is checked against the original employer source.
- Optum employer description is checked against the original employer source.
- Source review dates are recorded.
- Facts are distinguished from interpretations and assumptions.
- AI-generated claims are checked against employer documentation.

If an employer page changes or becomes unavailable, record that limitation rather than treating an old description as current.

## HTML and Code Quality
- Validate HTML with the W3C Nu Validator.
- Check for missing closing tags and duplicate element IDs.
- Use consistent HTML indentation and readable CSS.
- Check the browser console for JavaScript errors.
- Avoid unused dependencies and unnecessary frameworks.

## Planned Test Commands
After the website is implemented, optional local checks may include:

```bash
npx html-validate index.html
```

This command requires installing the html-validate package, which has not yet been configured.

A simple JavaScript-free research website may rely mainly on HTML validation, link checks, accessibility checks, and browser testing.

## Continuous Integration
GitHub Actions may be configured to run automated HTML validation and link checks on pushes and pull requests.

Fast local checks should identify formatting and markup issues before changes are committed.

## Deployment Tests
- GitHub Pages deployment succeeds.
- The public website opens.
- Research sections and sources appear correctly.
- Changes committed to the repository appear on the published site.
- Links between the career research website and Family Sudoku research website work.

## Acceptance Criteria
Testing will support the user stories in docs/plan.md, especially clear introductions, discoverable research, readable project information and accessible navigation.

## Test Results and Evidence
Use these statuses:

- Planned: Not yet run.
- Attempted: Executed but not confirmed successful.
- Observed: Actual result recorded with evidence.

Record failures and corrections in GitHub issues when appropriate.

## Current Status
All checks are planned. No website testing or automated CI checks have been performed yet.
