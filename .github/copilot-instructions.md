---
description: Coding guidelines for the week2 CS course project
---

# Project Guidelines

## Code Style

### Python Assignments
- Use function stubs with `pass` for starter code
- Include TODO comments guiding implementation
- Follow progressive complexity: basics → projects → OOP → data science

### JavaScript
- Use ES6 classes for organization
- Implement async/await with try-catch error handling
- Separate concerns into different files

### HTML/CSS
- Use semantic HTML elements
- Apply CSS custom properties for theming
- Ensure responsive design with flexbox

### Documentation
- Use emoji-enhanced markdown headers
- Structure with clear objectives, tasks, requirements
- Follow the assignment template format

## Architecture
This is a web-based portal for a high school CS course, featuring a main landing page and individual assignment pages. Assignments are progressive Python exercises stored in the `assignments/` directory. The portal dynamically loads assignment metadata from `config.json`.

Key components:
- `index.html`: Main portal with assignment listing
- `assets/js/script.js`: Portal logic (AssignmentPortal class)
- `assets/pages/assignment.html`: Template for assignment details
- `assignments/`: Python starter code and READMEs

## Build and Test
- **Python**: Run scripts with `python3 file.py` (Python 3 pre-installed)
- **JavaScript**: Lint with `eslint file.js` (eslint pre-installed)
- **HTML/CSS**: No build step; serve statically

## Conventions
- Assignment READMEs follow a consistent markdown template with objectives, tasks, and requirements
- Configuration-driven: Add new assignments by updating `config.json`
- Progressive curriculum: Each assignment builds on previous concepts

See [main README.md](README.md) for project overview and setup.