# Contributing to Petitionary

Thank you for considering contributing to Petitionary! This document outlines the guidelines for contributing to this project.

## Project Context

Petitionary is a civic engagement platform that empowers citizens to generate and submit AI-powered petitions to government representatives on important issues like environmental protection, food safety, and public health. The platform aims to shift power to the public by increasing transparency and creating accountability for unresponsive officials.

Given the civic and democratic nature of this platform, contributors should understand that:

1. Changes to the codebase directly impact citizens' ability to engage with their representatives
2. The platform must maintain high standards of reliability, accessibility, and security
3. Our work serves a greater public good and democratic engagement

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md) to maintain a respectful and inclusive environment.

## How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Run tests if applicable
5. Commit your changes (`git commit -am 'Add new feature'`)
6. Push to your branch (`git push origin feature/improvement`)
7. Create a Pull Request

## Pull Request Guidelines

- Ensure your code follows the project's coding standards
- Include relevant tests for new features
- Update documentation as needed
- Describe your changes in detail in the PR description
- Consider the security implications of your changes
- All PRs require review from the core team before merging

## Security and Platform Integrity

Given Petitionary's role in facilitating democratic engagement:

- Security vulnerabilities must be treated with the highest priority
- All AI-related code changes require additional scrutiny to prevent misuse
- Data handling must follow best practices to protect user privacy
- Code that could enable spam, harassment, or manipulation will be rejected
- Changes to petition generation, representative matching, or submission systems must include appropriate safeguards

## Reliability Standards

Petitionary must be accessible and reliable for all users:

- Changes should not degrade performance for users on slower connections
- Mobile responsiveness is essential for broad accessibility 
- New features should include error handling and graceful degradation
- Backend changes must consider scalability and stability
- Test thoroughly to avoid disruptions to the petition process

## Reporting Issues

- Use the issue tracker to report bugs
- Describe the bug in detail
- Include steps to reproduce
- Specify your environment (OS, version, etc.)
- For security issues, please report them privately to the maintainers

## Questions?

Feel free to open an issue for any questions about contributing.

Thank you for helping improve Petitionary!