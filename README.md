# 🚀 Git PR AI

A CLI tool that empowers developers to create GitHub Pull Requests faster and more efficiently with the help of AI.

---

**[Read the Docs](https://leochiu-a.github.io/git-pr-ai/intro)**

`git-pr-ai` is a command-line tool designed to streamline the process of creating GitHub Pull Requests from JIRA tickets. By leveraging the power of AI, it can automatically generate branch names, PR descriptions, and even assist with code reviews, allowing you to focus on what truly matters: writing high-quality code.

## ✨ Key Features

- **🤖 AI-Powered Assistance**: Utilizes powerful AI models (Claude Code or Gemini) to automatically generate PR descriptions and review code.
- **🎫 JIRA Integration**: Directly create git branches with standardized names from JIRA tickets.
- **⚙️ Simplified Workflow**: Consolidates multiple git commands into single, easy-to-remember commands.
- **🚀 Quick Start**: Get up and running with just a few simple installation and setup steps.

## 📦 Installation

```bash
pnpm add -g git-pr-ai
```

## 📋 Prerequisites

Before you begin, please ensure you have completed the following setup:

- **GitHub CLI**: [Install the GitHub CLI](https://cli.github.com/) and authenticate with `gh auth login`.
- **AI Provider**: Depending on your preference, set up access for either [Claude Code](https://console.anthropic.com/dashboard) or [Gemini CLI](https://ai.google.dev/tutorials/gemini_cli_quickstart).

## 🚀 Quick Start

1.  **Configure the tool** (optional):

    ```bash
    # Set up your preferred AI provider (Claude or Gemini)
    git pr-ai config
    ```

2.  **Create a branch from a JIRA Ticket**:

    ```bash
    # The system will automatically generate a branch name from the JIRA ticket ID (e.g., PROJ-123)
    git create-branch --jira PROJ-123
    ```

3.  **Create a Pull Request**:

    ```bash
    # Automatically detects the current branch and initiates the PR creation process
    git open-pr
    ```

4.  **Update PR Description with AI**:

    ```bash
    # Let AI generate or update the PR description based on your code changes
    git update-pr-desc
    ```

5.  **Review PR with AI**:
    ```bash
    # Let AI review your code and provide suggestions for improvement
    git pr-review
    ```

## 📚 Documentation

Want to learn more about detailed configurations and features?

Please refer to our **[full documentation](https://leochiu-a.github.io/git-pr-ai/intro)**.
