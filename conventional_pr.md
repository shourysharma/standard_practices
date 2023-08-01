# Conventional Pull Requests Documentation

Conventional Pull Requests (PRs) follow a consistent structure and provide valuable information to reviewers and maintainers. They help streamline the code review process and foster effective collaboration within a project. This documentation outlines the steps to write conventional pull requests:

**Step 1: Fork the Repository**
If you are not a direct contributor to the original repository, fork the repository to your GitHub account. This will create a copy of the repository where you can make changes and submit pull requests.

**Step 2: Clone the Forked Repository**
Clone the forked repository to your local machine using the following command:
```
git clone <repository-url>
```

**Step 3: Create a New Branch**
Create a new branch for your changes. The branch name should be descriptive and related to the feature or bug fix you are working on. For example:
```
git checkout -b feat/new-feature
```

**Step 4: Make Changes to the Code**
Implement the changes or additions you want to make to the codebase. Ensure that each pull request is focused on a specific task or feature.

**Step 5: Commit Your Changes**
Commit your changes using meaningful and conventional commit messages, as described in the "Conventional Commits Documentation." This is an essential step, as pull requests often reference individual commits for code review.

**Step 6: Push the Branch**
Push the branch with your changes to your forked repository on GitHub:
```
git push origin feat/new-feature
```

**Step 7: Create the Pull Request**
Navigate to the original repository on GitHub and click on the "New Pull Request" button.

**Step 8: Choose the Base Branch**
Select the base branch to which you want to merge your changes. Usually, this is the default branch of the original repository, such as `main` or `master`.

**Step 9: Choose the Compare Branch**
Choose the compare branch, which is the branch you created earlier with your changes, such as `feat/new-feature`.

**Step 10: Write the Pull Request Title**
Write a descriptive and concise title for your pull request. The title should clearly summarize the changes you are proposing.

**Step 11: Provide a Detailed Description**
In the description field, provide a comprehensive explanation of the changes introduced by the pull request. Include the following details:

- **Context**: Describe the problem you are addressing or the feature you are adding.
- **Solution**: Explain how your changes solve the problem or what functionality the new feature brings.
- **Testing**: Mention any testing you have done to verify your changes.
- **Screenshots or GIFs**: If applicable, include visual aids to help reviewers understand the changes better.

**Step 12: Mention Related Issues**
If your pull request is related to any existing GitHub issues, mention them in the description using the syntax `#issue-number`.

**Step 13: Add Reviewers and Assignees**
Assign reviewers to the pull request who will provide feedback and approve the changes. Additionally, you can assign the pull request to specific team members responsible for the changes.

**Step 14: Submit the Pull Request**
Once you have filled out all the necessary information, click on the "Create Pull Request" button to submit your changes for review.

**Step 15: Respond to Feedback**
Be responsive to feedback from reviewers and make necessary updates to the pull request based on their suggestions. Engage in discussions to address any concerns and ensure the quality of your changes.

**Step 16: Merge the Pull Request**
Once the pull request has been approved by the required reviewers and any CI/CD checks pass, the maintainers will merge the pull request into the main repository.

By following these steps and adhering to the conventions for writing pull requests, you contribute to a more organized and collaborative development process, making it easier for maintainers and reviewers to understand, assess, and incorporate your changes.