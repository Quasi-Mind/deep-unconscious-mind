# Guide for Submissions

## Introduction

We welcome and appreciate your contributions! This guide is designed to help you understand the process and expectations for submitting interactions to our repository.

## Prerequisites

Before you start, make sure you have a GitHub account. If you don't have one, you can create it [here](https://github.com/join).

## Steps to Submit Your Interactions

1. **Fork the Repository:** Navigate to the [DUM repository](https://github.com/Quasi-Mind/deep-unconscious-mind) on GitHub and click the "Fork" button in the top-right corner. This creates a copy of the repository in your own account.

2. **Clone the Forked Repository:** Open a terminal window and navigate to the location where you want to clone the repository. Then, run the following command, replacing `your_username` with your GitHub username:

   ```
   git clone https://github.com/your_username/repo_name.git
   ```

3. **Navigate to the `submissions` Branch:** By default, you'll be on the `main` branch. Switch to the `submissions` branch by running:

   ```
   git checkout submissions
   ```

4. **Add Your Interactions:** Follow the interaction format specified by using [AI Conversation Formatting Tool](https://quasi-mind.github.io/ai-conversation-formatting-tool). Once you're done, save the markdown file and include it in the `/conversations` directory.

5. **Commit and Push Your Changes:** Run the following commands to commit and push your changes to GitHub:

   ```
   git add .
   git commit -m "Add interaction"
   git push origin submissions
   ```

6. **Create a Pull Request:** Navigate to your forked repository on GitHub, switch to the `submissions` branch, and click the "New pull request" button. Make sure the base repository is the original repository and the base branch is `submissions`.

Please ensure that your submissions are clear, concise, and follow these formatting guidelines. Submissions that do not adhere to these guidelines may not be accepted. Thank you for your contributions!

## Review Process

Once you've created a pull request, our team will review your submission. We may suggest some changes or improvements. Once the submission is accepted, it will be merged into the `submissions` branch and, eventually, into the `main` branch.
