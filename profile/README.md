## Hi there 👋
Welcome to the MoneyCabin Github org! To ensure smooth collaboration and maintain code quality, please follow these guidelines when contributing.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# GitHub Guidelines



## Repository Naming

- **General Format**:
  - Use lowercase letters only.
  - Separate words with hyphens (`-`), not underscores (`_`) or spaces.
  - Keep the name concise and descriptive.

- **Examples**:
  - For a project related to user authentication: `user-authentication-service`
  - For a front-end application: `project-frontend`
  - For a back-end API: `project-backend-api`

- **Naming Conventions**:
  - **Public Repositories**: Clearly indicate the purpose of the repo (e.g., `project-website`, `mobile-app-backend`).
  - **Private/Internal Repositories**: Use names that indicate the function or area (e.g., `internal-tools`, `devops-scripts`).

## Branching Strategy

- **Main Branch (`main` or `master`)**: The main branch should always be in a deployable state. All production-ready code is merged here.
- **Development Branch (`develop`)**: This branch contains the latest development code and is used for testing and integration.
- **Feature Branches (`feature/your-feature`)**: Create a new branch for each feature or bugfix. Name the branch descriptively (e.g., `feature/user-authentication`).
- **Hotfix Branches (`hotfix/your-hotfix`)**: Used for urgent fixes that need to be made directly to the main branch.
- **Release Branches (`release/your-release`)**: Used to prepare for a new production release. No new features should be added here—only bug fixes and final adjustments.

## Commit Messages

- **Format**: Use the following format for commit messages:
- **Tags**: Use tags like `[Feature]`, `[Bugfix]`, `[Refactor]`, `[Docs]`, `[Test]`, etc.
- **Example**:
  ```
  [Feature] Add user login functionality

  Implemented login API and integrated with the frontend. Added unit tests for the login service.
  ```

- **Best Practices**:
- Use imperative, present tense (e.g., "Add feature" not "Added feature").
- Keep the first line under 50 characters.
- Use the body to explain the "why" behind the changes, not just the "what."

## Pull Requests

- **Creating PRs**:
- PRs should be made from a feature branch to the `develop` branch.
- Provide a clear and concise title and description of what your PR does.
- Reference relevant issues (e.g., `Closes #issue-number`).

- **Review Process**:
- Assign at least one reviewer to your PR.
- All PRs require at least one approval before merging.
- If changes are requested, address them promptly and update your PR.

- **Merging**:
- Squash and merge is preferred to maintain a clean commit history.
- Delete the branch after merging to keep the repository tidy.

## Code Reviews

- **Review Criteria**:
- Code must be readable, maintainable, and adhere to the project’s style guide.
- Ensure the code is well-tested and documentation is updated.
- Look for potential bugs, security vulnerabilities, and performance issues.

- **Providing Feedback**:
- Be constructive and specific in your feedback.
- Praise good work as well as pointing out issues.
- Avoid personal criticism—focus on the code, not the coder.

## Issue Tracking

- **Creating Issues**:
- Clearly describe the bug, feature request, or enhancement.
- Assign labels (e.g., `bug`, `enhancement`, `question`) to categorize the issue.
- If applicable, assign the issue to yourself or someone else.

- **Closing Issues**:
- Reference the issue in your commit message or PR description (e.g., `Closes #issue-number`).
- Only close issues once the related work is merged into the `main` branch.

## Code Style and Formatting

- **Style Guide**:
- Follow the project’s coding conventions (e.g., naming conventions, indentation).
- Use [Prettier](https://prettier.io/) for code formatting (ensure your editor is configured to format on save).

- **Linting**:
- Run linters before committing to ensure code adheres to the style guide.
- Fix any linting errors before submitting your code.

## Documentation

- **Code Documentation**:
- Comment complex code and include docstrings where applicable.
- Keep inline comments concise and to the point.

- **Project Documentation**:
- Update the `README.md` and any other relevant documentation whenever there are significant changes.
- Ensure setup instructions are clear and up to date.

## Testing

- **Unit Tests**:
- Write unit tests for new features and bug fixes.
- Ensure tests cover various edge cases and possible failure points.

- **Integration Tests**:
- Write integration tests for critical workflows.

- **Running Tests**:
- Run all tests locally before pushing changes.
- Ensure the CI/CD pipeline passes all tests before merging.

## Versioning

- **Semantic Versioning**:
- Follow [Semantic Versioning](https://semver.org/) (e.g., `v1.0.0`).
- Increment:
  - **Major** version for incompatible API changes,
  - **Minor** version for adding functionality in a backward-compatible manner,
  - **Patch** version for backward-compatible bug fixes.

## Security

- **Sensitive Data**:
- Never commit sensitive information (e.g., passwords, API keys).
- Use environment variables for configuration that contains sensitive data.

- **Dependencies**:
- Regularly check for and update dependencies to avoid security vulnerabilities.
- Run dependency audits (e.g., `npm audit`, `yarn audit`).

## License

- **License Information**:
- This project is licensed under the [LICENSE] file in the root directory of this repository.
- Ensure all contributions comply with the terms of the project’s license.

## Contact

- **Questions/Support**:
- For questions or support, please contact [Your Name] or create a new issue.
- For urgent issues, use the project's communication channel (e.g., Slack, Discord).


