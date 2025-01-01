# Engineering
Welcome to the Engineering section of the Sarke Company Handbook. This section provides an overview of our company's general engineering best practices and technology stack, which apply across all projects.

## Best Practices
At Sarke, we prioritize minimalist, well-documented, and easily testable code to ensure the highest quality and maintainability of our projects.

## Source Management
In order to maintain clean and organized version control, we have established a set of guidelines for committing and branching in our projects.

### Branching
Our repository follows a structured branching model to promote organized and efficient development. Here's an overview of our branch types:

- **`main`**: The release branch. Only the `develop` branch can be merged into `main`.
  We enforce strict rules to prevent direct merges from any other branch.
- **`develop`**: The active development branch. This branch may contain bugs or incomplete features.
  Automated actions are set up to push new builds to TestFlight on the App Store and the Play Store for testing.
- **`feature/...`**: Branches created for specific feature implementations.
- **`bugfix/...`**: Branches created for fixing specific bugs.
- **`bump/v1...`**: Branches created for version updates and bumps.

All `feature/...`, `bugfix/...`, and `bump/v1...` branches should be merged into `develop`, not directly into `main`.

### Commits
We follow a standardized commit message format to keep track of changes and maintain a clear history. Here are the commit guidelines:

- For new features, use: `feat(<scope>): <your-message-here>`.
- For bug fixes or small updates, use: `fix(<scope>): <your-message-here>`.
- For non-feature and non-bugfix changes, use: `chore(<scope>): <your-message-here>`.

Replace `<scope>` with the relevant part of the application you’re working on.
Each commit should address only one scope or topic to ensure clarity and precision in version control.

It's important to commit regularly and ensure that each commit represents a single, well-defined change.
This practice helps maintain an organized and traceable development history.

## Technology Stack
At Sarke, we aim to build high-performance and scalable applications. Our technology stack is carefully chosen to provide a solid foundation for achieving these goals.

We primarily use:
- **Rust** as our core programming language for backend services and system-level programming
- **TypeScript with Next.js** for web development
- **Flutter & Dart** for cross-platform mobile applications

We're committed to staying up-to-date with the latest tools and technologies in the industry while experimenting with new options that can improve our development process and project outcomes. Our team welcomes suggestions and feedback from our community. If you have any questions or ideas about our tech stack, please don't hesitate to reach out to us.
