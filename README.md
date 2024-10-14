Privado ID Documentation is the documentation hub providing extensive documentation, community resources, and guides for enthusiasts and developers interested in learning about or building solutions using Privado ID.

## Disclaimer

OPID is a fork from Privado Id with the aim to make identities available in the Optimism blockchain. In this repo we took Privado Id documentation and adapted it for use in Optimism with OPID. So feel free to jump back and forth with Privado Id resources. Here some links that may be useful:

- 

## Contribute to Op ID Documentation

After running the docs locally on your machine, use a code editor to apply your changes before submitting 
your PR. Note that you must have a GitHub account and an understanding of Markdown syntax.

1. Create a new branch for your changes.
   
    ```
    git checkout -b [new_branch_name]
    ```

2. Commit your changes. 
   In the commit message, please reference the issue it resolves. 
   For help, see [GitHub Docs: Linking a pull request to an issue using a keyword](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).

    ```
    git commit -m "brief description of changes"
    ```

3. Push to your forked repository.
   
    ```
    git push
    ```

4. Submit a PR against the `main` branch of the `wakeup-labs/opid-docs` repo.
   
5. Add a title to your PR with appropriate labels.
   > For example, if you want to suggest edits to the "Develop" page, name your PR: *update: develop.md*.
   
6. Add a description to your PR. Please reference the issue it resolves. 
   > For help, see [GitHub Docs: Linking a pull request to an issue using a keyword](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).
   
7. Write a brief description of the changes you have made. If possible, include screenshots and references.

## Submit an Issue

- Create a [new issue](https://github.com/wakeup-labs/opid-docs/issues) to report a bug, request a feature, or suggest changes.

- Comment on the issue if you want to be assigned to it so [our team can assign the issue to you](https://github.blog/2019-06-25-assign-issues-to-issue-commenters/).

- If you do not have a specific contribution in mind, you can also browse current issues.

- Issues that additionally have the `good first issue` label are considered ideal for first-timers.

### Image Maintenance

To enhance the flexibility of centering and sizing images within our markdown files, we often utilize HTML. However, this approach complicates image maintenance. We provide two scripts to facilitate the management of images in our projects.

#### Finding Unused Images

This utility script assists in identifying static images that are no longer referenced within our documentation. To leverage this script, execute the following command from the project's root directory:

```bash
node scripts/find-unused-images.js
```

#### Identifying Broken Image Links

This script is designed to locate references to images within our documentation that lack corresponding files in the static folder. To use this script, run the following command from the project's root directory:

```bash
node scripts/find-broken-image-links.js
```

