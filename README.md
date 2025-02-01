Basic Automated Github Workflow Action to update version of package.json in your repository through "npm version --patch" and PR creation.

Usage:
1. Copy workflow script /.github/workflows/npm-version-patch.yml into your repository or create it via the Actions tab.
2. Update the script and set the correct branches, by default PRs will be created towards "main" branch.
3. Go to Settings -> Actions, click "Allow GitHub Actions to create and approve pull requests".
4. Run the action, the new PR should appear. You could also use any other additonal commands by adjusting the .yml file.
