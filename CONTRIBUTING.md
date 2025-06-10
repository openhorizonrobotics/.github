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

### Git Commit Messages

Writing clear and consistent commit messages helps everyone understand the history and purpose of changes. When creating commits, keep the following in mind:

* **Use the present tense**
  + Describe what the commit does, not what it did.

      ( ✅ "Add feature" ❌ "Added feature" ) 


* **Write in the imperative mood**
  + Think of the message as a command.

     ( ✅ "Move cursor to.." ❌ "Moves Cursor to.." )

* **Keep the subject line concise**
  + Limit the first line (subject) to 72 characters or fewer. Use additional lines for details if needed.


* **Reference issues or pull requests**
  + Use issue references to link related issues or PRs.

    ( Example: "Fix typo in README (#42)" )



### Code Style

- Follow the language-specific style guide (e.g., PEP 8 for Python).
- Use meaningful variable and function names.
- Write comments to explain complex logic.

## Testing

- Write tests for your code.
- Ensure all tests pass before submitting a pull request.

## Documentation

- Update the README.md with details of changes to the interface, including new environment variables, exposed ports, useful file locations, and container parameters.
- Ensure that any new code is documented.

## Community

- Join our discussion forum to ask questions and engage with other contributors.
- Attend our monthly community meetings (details in the forum).

Thank you for your contributions!
