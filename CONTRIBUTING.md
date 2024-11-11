# Contributing to DueMate

Thank you for considering contributing to DueMate! We welcome all kinds of contributions, including bug reports, feature requests, documentation, and code improvements.

## Getting Started

1. **Fork the Repository**: Click on the "Fork" button at the top of this repository page to create your own copy of the repository.

2. **Clone Your Forked Repository**:
    ```bash
    git clone https://github.com/your-username/DueMate.git
    cd DueMate
    ```

3. **Create a Branch**: Use descriptive branch names to reflect the purpose of your changes.
    - **Feature branches**: `feature/feature-name` (e.g., `feature/bill-reminder`)
    - **Bug fix branches**: `fix/bug-description` (e.g., `fix/notification-bug`)
    - **Improvement branches**: `improve/improvement-description` (e.g., `improve/performance-optimization`)
    ```bash
    git checkout -b feature/your-feature-name
    ```

4. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Code Guidelines

- **Commit Messages**: Write clear and concise commit messages. Use the following format for commit messages:
    - `feat: Add feature description`
    - `fix: Correct bug description`
    - `docs: Update documentation`
    - `style: Format code (e.g., spaces, indentations)`
    - `refactor: Refactor code without changing functionality`
    - `test: Add or modify tests`

- **Code Style**: Follow PEP 8 guidelines for Python code. We recommend using linters to check code quality before committing.

- **Tests**: Ensure any new features or bug fixes include relevant unit tests. Run the test suite before submitting your changes:
    ```bash
    pytest
    ```

## Submitting a Pull Request

1. **Push Changes**: Push your branch to your forked repository:
    ```bash
    git push origin feature/your-feature-name
    ```

2. **Open a Pull Request**: Go to the original repository, click on the "Pull Request" tab, and create a new pull request. Select the `dev` branch as the target branch.

3. **Describe Your Changes**: Include a clear description of the problem, solution, and any additional context in the PR description.

4. **PR Review and Approval**: All PRs require at least one approval before merging. Please address any requested changes.

5. **Merge to `dev` Branch**: Once your PR is approved, it will be merged into the `dev` branch. Merging to `main` occurs after additional testing and review.

## Code of Conduct

Be respectful and constructive in your interactions. Please refer to the `CODE_OF_CONDUCT.md` file for more details.

Thank you for contributing to DueMate!
