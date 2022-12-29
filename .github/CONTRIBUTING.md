# Contributing Rules

- The development will be done **in English**.
- Commit messages **must** follow [Conventional Commits specifications](https://www.conventionalcommits.org/en/v1.0.0/#specification).
- Branches **must** follow the [Git Flow pattern](https://github.com/petervanderdoes/gitflow-avh).
- Versioning must follow the [Semantic Versioning specifications](https://semver.org/).
- Every contribution **must** be accompanied by a test suite that tests the new feature or simulates the bug to be fixed.
- All code **must** follow its language's styling conventions.

# Starting

This guide assumes you have Git Flow installed on your system. The `main` branch is **always** the production branch, and the `develop` branch is **always** the development branch.

To create a feature/bugfix branch, use the command:

```sh
git flow feature start <feature-name>
# or
git flow bugfix start <bugfix-name>
```

Git Flow will automatically create and checkout the branch, make the changes in your favorite code editor. When you're done with the changes, commit and use the following command to publish the feature on GitHub:

```sh
git flow feature publish <feature-name>
# or
git flow bugfix publish <bugfix-name>
```
The branch should automatically be published on GitHub. Wait a supervisor to review your code and merge or request changes if necessary.
