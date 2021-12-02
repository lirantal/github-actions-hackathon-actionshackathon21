# GitHub Actions Hackathon 2021

This repository demonstrates the workflows recipe for the GitHub Actions Hackathon with Dev.to 2021


### My Workflow

My GitHub Actions hackathon application entry is about all the small things that would contribute to a better maintainer life.

Maintainers usually get a good grip on the important things, like making sure they have a workflow that run code style checkers, tests, and that publishes a package to the registry.

Busy with these, they end up forgetting about the small things that are the details, but as important, for example: having a markdown linter in place to ensure no broken documentation.

Can we reach open source maintainer nirvana?
I can't promise you that, but I can promise I will do everything I can to put us on that direction.

With that in mind, I'm suggesting a recipe of several GitHub Actions CI workflows that you can add to your open source repositories at GitHub. I've segmented them into specific areas too.

#### Markdown documentation

This recipe will introduce the following workflows:
- **Markdown Style linter** - Making sure your documentation like the `README.md` has proper 
- **Markdown Links linter** - Making sure your documentation has no broken links

#### Dependency management

- **New dependencies advisor** - Add a comment in a Pull Request informing of newly added dependencies and their package health

#### Pull Request engagement

- **PR Title update** - Do you manage multiple base branches with PRs to? If you manually updated your PR titles to include this information then now this is automated for you

- **PR Contribution fun note** - Welcome contributors to your project by adding a comment that thanks them and embeds an image of a cute animal

### Submission Category: 

- Maintainer Must-Haves

### Additional Resources / Info

The recipe makes use of the following GitHub Actions from the marketplace:

- [ruzickap/action-my-markdown-linter](https://github.com/marketplace/actions/my-markdown-linter)
- [lirantal/github-action-new-dependencies-alerts](https://github.com/marketplace/actions/new-dependencies-advisor)
- [ruzickap/action-my-markdown-link-checker](https://github.com/marketplace/actions/my-markdown-link-checker)
- [circa10a/animal-action](https://github.com/marketplace/actions/animal-action)
- [lirantal/github-action-pr-title-update-branch](https://github.com/marketplace/actions/pull-request-title-update-to-include-base-branch)
