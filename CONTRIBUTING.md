# Contribution guidelines.

## Bugs, feature requests, questions

Use the project issue tracker to report issues.

Please, try to follow the supplied issue template (if one exist) when reporting an issue to make it as easy to evaluate and fix any potential issues.

## Security vulnerabilities

If you find a security vulnerability in the module, please, start with sending an email to security@personnummer.dev and allow us to evaluate and try to patch the vulnerability before announcing it public.

Any security vulnerabilities that we fix will be announced after a security patch have been made and a timespan have passed allowing users to update their installation.

## Code standard

We support many different languages and you will find the code standard for each project in the respective repository.

Pull requests not following the standard of the specific repository will not be accepted without modifications. Please use the appropriate lint or fix tool to follow the standard.

## Testing

We strive to keep our projects tested as close to 100% coverage as possible. This might not always be needed or even possible, but
any new features should be covered with tests and any changes made should allow existing tests to pass.

## Pull requests

Pull requests are greatly appreciated, but please try to be as descriptive in both the commit log and in your PR description,
this makes it a lot more easy to manage the changelog and to know if a new major version is required for a specific change.

## Commit messages

Commits should include messages with a description of the changes. You don't have to write an essay, just a line or two.

Example:

> New log tag: lolzerz.
> Added a new default tag named `lolzers` which is super good and cool.

If you work on a specific issue, please hint it in the commit message so that it is easier to follow the git log when needed.

Example:

> New log tag: lolzerz.
> Added a new default tag named `lolzers` which is super good and cool.
> Ref: #123