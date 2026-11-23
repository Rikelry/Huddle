# Contributing to Huddle

First of all, thank you for your interest in contributing to Huddle!

Huddle is an open-source Linux desktop application built with Rust. Our goal is to create reliable, accessible, and user-friendly software for the Linux community.

We welcome contributions of all kinds, including bug fixes, new features, documentation improvements, translations, and suggestions.

## Getting Started

Before contributing, make sure you have:

- A Linux distribution.
- [Rust](https://www.rust-lang.org/tools/install) installed.
- Cargo installed (included with Rust).
- Git installed.
- Any additional system dependencies required by Huddle.

### Fork and Clone

1. Fork the Huddle repository.
2. Clone your fork:

   ```bash
   git clone https://github.com/Rikelry/Huddle.git
   ```

3. Enter the project directory:

   ```bash
   cd Huddle
   ```

4. Create a new branch:

   ```bash
   git checkout -b feature/my-contribution
   ```

## Development Guidelines

When contributing to Huddle, please follow these guidelines:

- Write clean, readable, and maintainable Rust code.
- Follow standard Rust conventions and idioms.
- Prefer safe Rust whenever possible.
- Avoid unnecessary dependencies.
- Handle errors appropriately.
- Keep the application compatible with supported Linux environments.
- Consider accessibility and usability when developing UI features.
- Document complex or non-obvious code.
- Keep changes focused on a single purpose.

## Code Formatting and Linting

Before submitting your contribution, run:

```bash
cargo fmt --all -- --check
```

And:

```bash
cargo clippy --all-targets --all-features -- -D warnings
```

Address any relevant warnings or formatting issues before opening a Pull Request.

## Testing

Run the project's test suite before submitting changes:

```bash
cargo test
```

If your contribution affects the graphical interface, please test the relevant functionality manually as well.

Include information about the tests you performed in your Pull Request.

## Commit Guidelines

Use clear and descriptive commit messages.

Recommended prefixes:

- `feat:` New features.
- `fix:` Bug fixes.
- `docs:` Documentation changes.
- `refactor:` Code improvements.
- `test:` Test-related changes.
- `chore:` Maintenance tasks.

Examples:

```text
feat: add application preferences
fix: resolve window initialization issue
docs: update installation instructions
refactor: simplify configuration handling
```

## Pull Requests

Before opening a Pull Request:

1. Make sure your branch is up to date.
2. Ensure your code follows the project's guidelines.
3. Run formatting, linting, and tests.
4. Provide a clear description of your changes.
5. Include screenshots when modifying the graphical interface, if applicable.
6. Mention any known limitations or potential issues.

Pull Requests should be submitted against the repository's default development branch.

Maintainers may request changes before merging.

## Reporting Bugs

If you find a bug, please open a GitHub Issue.

Include the following information whenever possible:

- Huddle version.
- Linux distribution and version.
- Desktop environment (GNOME, KDE Plasma, XFCE, etc.).
- Steps to reproduce the issue.
- Expected behavior.
- Actual behavior.
- Relevant logs or error messages.
- Screenshots, if applicable.

Please avoid including passwords, private information, or sensitive system data in reports.

## Feature Suggestions

Feature suggestions are welcome!

When proposing a new feature, explain:

- The problem it solves.
- Why it would be useful.
- How you imagine it working.
- Any potential impact on the existing application.

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Security Issues

Please do not report security vulnerabilities through public Issues.

Read our [Security Policy](SECURITY.md) for instructions on responsible disclosure.

## Questions

For general questions or discussions, use the communication channels available in the Huddle repository.

Thank you for helping make Huddle better!

**Happy contributing!**

