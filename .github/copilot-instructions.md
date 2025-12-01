# Copilot Instructions for My First Project

## Overview

This project is a simple web application structured to provide a clean and efficient user experience. The main components include an `index.html` file for the layout, a `styles.css` file for styling, and an `images` directory for assets.

## Architecture

- **index.html**: The entry point of the application. It links to the CSS for styling and includes any necessary scripts.
- **css/styles.css**: Contains all the styles for the application. Follow BEM (Block Element Modifier) methodology for class naming.
- **images/**: Store all image assets here. Use descriptive names for easy identification.

## Developer Workflows

- **Building**: Use a build tool like Grunt or Gulp (if configured) to automate tasks. Check for a `Gruntfile.js` or `gulpfile.js` in the root directory.
- **Testing**: Ensure to run tests using the command `npm test` if a testing framework is set up. Look for test files in a `tests` directory or similar.
- **Debugging**: Use browser developer tools to inspect elements and debug JavaScript. Console logs can be added for tracking issues.

## Project Conventions

- Follow the BEM naming convention for CSS classes.
- Use semantic HTML elements for better accessibility and SEO.
- Keep JavaScript functionality modular and organized in separate files if applicable.

## Integration Points

- Ensure that any external libraries or frameworks are included in the `index.html` file. Check for CDN links or local files in the `js` directory if present.
- For any API integrations, document the endpoints and expected responses in a separate `API.md` file if available.

## External Dependencies

- Check `package.json` for any dependencies required for the project. Run `npm install` to install them.
- Ensure to keep the `node_modules` directory out of version control by referencing `.gitignore`.

## Communication Patterns

- Use comments in the code to explain complex logic or decisions.
- Maintain a consistent coding style throughout the project for readability.

---

This document serves as a guide for AI coding agents to understand the structure and workflows of the project effectively.
