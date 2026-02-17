# Contributing to WebNotes 2.0

First off, thank you for considering contributing to WebNotes 2.0!  
This project is intended to be beginner-friendly and a good place for students to practice open-source collaboration.

We welcome bug reports, feature ideas, documentation improvements, and code contributions.



## How to Contribute

There are several ways you can contribute:

- Report bugs
- Suggest new features
- Improve documentation
- Add tests
- Submit code changes



## Before You Start

Please:

1. Check existing **Issues** to see if your idea has already been discussed.
2. If not, open a new issue describing:
   - What you want to change
   - Why it improves the project
   - Any implementation ideas you have

This helps avoid duplicate work and ensures your contribution fits the project goals.


## Development Setup

1. Fork the repository
2. Clone your fork locally:

   ```bash
   git clone https://github.com/NAU-OSS/WebNotes2.0.git
   cd WebNotes2.0
   ```

3. Load the extension in Chrome:

   - Go to `chrome://extensions/`
   - Enable **Developer Mode**
   - Click **Load unpacked**
   - Select the `/client` folder in the project directory

4. Make sure the extension loads without errors.

## Branching Workflow

Create a new branch for your work:

```bash
git checkout -b feature/short-description
```

Examples:

- `feature/public-note-filter`
- `fix/note-saving-bug`
- `docs/readme-update`

Do **not** work directly on `main`.

## Coding Guidelines

Please follow these guidelines when submitting code:

- Use consistent formatting (2 spaces for JavaScript indentation)
- Keep functions small and focused
- Use descriptive variable names
- Add comments for non-obvious logic
- Avoid introducing large libraries unless necessary
- Test your change in Chrome before submitting

If your change affects UI behavior, verify:
- Notes still load correctly
- Saving/editing still works
- No console errors appear

## Commit Messages

Use clear, descriptive commit messages.

Good examples:

```
Fix note duplication when page reloads
Add option to toggle public notes visibility
Update README installation steps
```

Avoid messages like:

```
fix stuff
changes
update
```

## Pull Request Process

1. Push your branch to your fork
2. Open a Pull Request against the `main` branch
3. Include in your PR description:

   - What the change does
   - Why it is needed
   - How you tested it

4. If your PR fixes an issue, reference it:

   ```
   Closes #12
   ```

A maintainer will review your PR and may request small changes before merging.

## Reporting Bugs

When reporting bugs, please include:

- Browser version
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Screenshots (if helpful)

This helps us fix issues faster.

## Suggesting Features

Feature requests are welcome!  
When suggesting a feature, explain:

- The problem it solves
- Who would benefit
- A rough idea of how it could work

## Code of Conduct

By participating in this project, you agree to:

- Be respectful and constructive
- Give helpful feedback
- Focus on improving the project

We want this project to be a welcoming place for contributors of all experience levels.

## Questions?

If you're unsure about anything:

- Open an issue
- Ask in your Pull Request
- Request clarification before starting large changes

We’re happy to help 🙂

---

Thanks again for contributing to WebNotes 2.0!
