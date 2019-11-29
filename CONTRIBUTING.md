# Contributing

## Code

- Must be readable with meaningful naming, eg no short hand single character variable names
- Follow our [style guides](https://gds-way.cloudapps.digital/manuals/programming-languages.html#code-style-guides) for the language of the repo
- Write tests for your changes

## Words

- Follow our [content style guide](https://www.gov.uk/guidance/style-guide)
- URLs should use hyphens, not underscores

## Git workflow

- Pull requests must contain a succinct, clear summary of what the user need is driving this feature change.
- Make a feature branch
- Ensure your branch contains logical atomic commits before sending a pull request - follow our [Git styleguide](https://gds-way.cloudapps.digital/standards/git.html)
- Pull requests are automatically integration tested, so you'll get feedback on whether the tests still pass on your branch
- You can rebase your branch after feedback to pull relevant updates from the master branch. We prefer a rebase here to a merge commit as we prefer a clean and straight history on master with discrete merge commits for features

