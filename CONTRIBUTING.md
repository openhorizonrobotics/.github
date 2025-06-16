# Contributing to Open Horizon

Thank you for considering contributing to our project! 

We appreciate your time and effort! This document outlines the contribution process; whether you're reporting a bug, suggesting a feature, or submitting a pull request, we value your input and strive to make the contribution process as smooth as possible.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Asking for Help](#asking-for-help)
- [Raising Issues](#raising-issues)
  - [Bug Reports](#bug-reports)
  - [Feature Requests](#feature-requests)
- [Submitting Contributions]($submitting-contributions)
- [Style Guides](#style-guides)
- [Testing](#testing)
- [Documentation](#documentation)

## Code of Conduct

Please read and adhere to our Code of Conduct in all interactions. We expect all contributors to uphold these standards.

## Asking for Help

If you need help, feel free to reach out by opening an issue or joining our discussion forum. Provide as much detail as possible to help us assist you effectively.

## Raising Issues

### Bug Reports

Filing an issue is a great way to contribute to the project! Bug reports help us identify and fix problems faster. If you’ve run into something unexpected, we’d love to hear about it. Before opening a new issue, please consider the following:

* **Is it really a bug?**
  + Describe what you expected to happen versus what actually happened. This helps us understand the problem clearly.

    
* **Include clear steps to reproduce**
  + The more specific, the better! Walk us through how you encountered the bug so we can replicate it on our end.


* **Add relevant details**
  + Screenshots, logs, or error messages make debugging easier. If it’s related to a specific environment (e.g. OS, Python version), let us know.


* **Check for duplicates**
  + Use the search bar in the Issues tab to see if someone else has already reported it. If so, consider commenting there instead of creating a new issue.


* **Give your issue a meaningful title**
  + A clear, descriptive title helps us (and others) quickly understand what the issue is about.


### Feature Requests

Got an idea to improve the project? Awesome! We welcome feature requests, and they help shape the future of the project. Before opening a new issue, please consider the following:

* **Is this really a feature request?**
  + Clearly differentiate it from a bug report or support question to help us categorize it correctly.


* **Is there already an open issue for this?**
  + Check the existing issues first. If you find a related one, feel free to add your input there instead of opening a duplicate.


* **Provide a clear and descriptive title.**
  + A specific and concise title helps maintainers quickly understand what you're suggesting.


* **Explain the feature in detail.**
  + Describe what the feature should do, who it’s for, and how it will help. The more context, the better!


* **Outline any benefits or potential drawbacks.**
  + Help us evaluate the impact and feasibility of the request by including pros and possible cons.


* **Add any relevant information or examples.**
  + Links, screenshots, mockups, or comparisons with other tools can help convey your idea more effectively.

  
## Submitting Contributions

1. **Fork the repository**: 

    Click the "Fork" button at the top right of the repository page.


2. **Clone your fork**: 
    ```sh
    git clone https://github.com/your-username/your-repo.git
    ```


3. **Create a branch**: 
    ```sh
    git checkout -b feature/your-feature-name
    ```


4. **Make your changes**: 

    Implement your feature or fix the bug.


6. **Commit your changes**: 
    ```sh
    git commit -m "Add feature/fix: description of your changes"
    ```


7. **Push to your branch**: 
    ```sh
    git push origin feature/your-feature-name
    ```


8. **Create a Pull Request**: 

    Go to the repository on GitHub and click "New Pull Request".


## Style Guides


***We follow the [Google Style Guide](https://google.github.io/styleguide/) for all our codebases.***

Please ensure that your code adheres to these standards before submitting a pull request. This helps maintain consistency, readability, and quality across the project.

✏️ Use appropriate linters or formatters for your language (e.g., clang-format, gofmt, black, or eslint) configured to align with the Google Style Guide.

***If you're unsure about a style decision, feel free to ask or open a draft PR — we're happy to help!***

### Git Commit Messages

Writing clear and consistent commit messages helps everyone understand the history and purpose of changes. When creating commits, keep the following in mind:

* **Use the present tense**
  + Describe what the commit does, not what it did.

      ( ✅ "Add feature" ; ❌ "Added feature" ) 


* **Write in the imperative mood**
  + Think of the message as a command.

     ( ✅ "Move cursor to.." ; ❌ "Moves Cursor to.." )


* **Keep the subject line concise**
  + Limit the first line (subject) to 72 characters or fewer. Use additional lines for details if needed.


* **Reference issues or pull requests**
  + Use issue references to link related issues or PRs.

    ( Example: "Fix typo in README (#42)" )

***Please go through the [Google Code Samples](https://developers.google.com/style/code-samples) as we follow most of their guidelines on our projects***


### Code Style

Maintaining a consistent and clean codebase helps everyone collaborate better. When contributing code, please keep the following in mind:

* **Follow the relevant style guide**
  + Stick to the language-specific conventions.

     ( Example: use [PEP 8](https://peps.python.org/pep-0008/) for Python ).


* **Use clear and meaningful names**
  + Choose variable, function, and class names that clearly describe their purpose.

    ( Example: ✅ calculate_total() ; ❌ ct() )


* **Write helpful comments**
  + Add comments to clarify non-obvious or complex logic. Avoid stating the obvious, and focus on why something is done if it's not immediately clear.


* **Keep code readable**
  + Use consistent indentation, spacing, and structure to make your code easier to follow and maintain.



## Testing

* **Write meaningful tests**
  + Make sure your code includes tests that cover core functionality and edge cases. This helps maintain code quality and prevents regressions.


* **Ensure all tests pass before submitting a PR**
  + Always run the full test suite before opening a pull request. Submitting passing tests builds trust and makes it easier to review your contribution.
 
    
## Documentation

* **Document interface changes**
  + If your changes affect how users interact with the project (e.g., API endpoints, CLI commands, configuration options), make sure to clearly document them in the README.md.


* **Include details about:**

  + New environment variables
    + *Describe what each variable does and provide default values if applicable.*

  + Exposed ports
    + *List any additional ports the application listens on and why they were added.*

  + File paths and key locations
    + *Note any new or modified file locations that may be relevant to users or developers.*

  + Container parameters
    + *If your update changes Docker/container behavior, update relevant flags, volumes, or parameters in usage instructions.*


* **Ensure new code is documented**
  + Add inline comments or docstrings explaining the purpose and logic of your code. This makes it easier for others to maintain and build on your work.

## Community

* ***Get involved in discussions***
  + Join our discussion forum to ask questions, share ideas, and collaborate with fellow contributors. It's a great place to get help and stay updated on ongoing work.

* ***Attend community meetings***
  + We host monthly community calls to discuss updates, roadmap plans, and open issues. Check the forum for upcoming meeting details and how to join.



🎉 Thank you for being part of the project!

Every contribution, big or small, helps us move forward — and we appreciate your time, effort, and creativity.
