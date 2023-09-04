# Contributing

Thank you for considering contributing to TypeHero. As an open sourced project
we only exist by contributions from users like you.

To contribute you will first need to fork the repo. To get the repository up and
running, please look at [LOCAL.md](/LOCAL.MD) for setup instructions.

## I Want to Contribute

### Adding internationalization languages

To Add languages, you will need to go to the `locales` folder.

If the language you want to add is not there, you will need to create a new po file and compile it into a mo file after the translation is complete.

Create po:
`msginit -i base.pot -o en_US.po -l en_US`

Compile po to mo:
`msgfmt en_US.po -o locales/en_US/LC_MESSAGES/base.mo`

#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Find out whether your idea fits with the scope and aims of the project. It's
  up to you to make a strong case to convince the project's developers of the
  merits of this feature. Keep in mind that we want features that will be useful
  to the majority of our users and not just a small subset.

### Your First Code Contribution

1. Choose an issue from the [GitHub issues](/issues), ask a member of the team
   to assign the issue to you.
2. Fork the repository
3. Create a branch on your fork. You should either add in the GitHub issue
   number to the branch name, e.g. `382_adds-in-new-thing` or ensure that the
   issue is referenced in the Pull Request or commit message.
4. We do not enforce a commit style like
   [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), but
   you are welcome to use one so long as the summary line accurately describes
   the overall purpose of the work and the ticket is referenced either in the PR
   or the body of the commit message. See [Commits](#commits) for example
   commits.
5. When ready, put up a PR that links from your fork.

