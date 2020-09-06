# New Project

This is a brand new repository that has been created.

## Out of the Box Features

1. **Issue Templates** - Default created issue templates
    1. _Bug Report_ - Create a bug report issue
    2. _Feature Request_ - Create feature request/enhancement
    3. _Dev Ops Request_ - Create a new development operations request, this can be sever management, user access item, workflow automation enhancement, or a report of issues going on with cloud infrastructure
2. **Workflow**
    1. _Auto Assign Issue to Project_ - Using the GitHub secret: `AUTOMATE_ISSUES_PULL_REQUESTS` any issues and any pull requests created on the development branch will automatically be added to the project configured using the: `GITHUB_URL_TO_PROJECT` placeholder.
    2. _Auto Assign_ - Using [Auto Assign](https://github.com/apps/auto-assign) (must be added to your organization or GitHub user) this repos default behavior is for it to assign the creator of a pull request to the author of the pull request
