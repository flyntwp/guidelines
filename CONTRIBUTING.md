# Contributing to Flynt

Thank you for taking the time to contribute! We'd love for you to contribute to our source code and make Flynt even better! Here are the guidelines we'd like you to follow:

- [Code of Conduct](#code-of-conduct)
- [Submission Guidelines](#submission-guidelines)
    - [Issues and Bugs](#issues-and-bugs)
    - [Feature Requests](#feature-requests)
    - [Pull Requests](#pull-requests)
- [Coding Rules](#coding-rules)
    - [Commit Messages](#commit-messages)
    - [PHP](#php)
    - [JavaScript](#javascript)
    - [Templates and Styles](#templates-and-styles)

## Code of Conduct
Help us keep Flynt open and inclusive. Please read and follow our [Code of Conduct](https://github.com/flyntwp/guidelines/blog/master/CODE_OF_CONDUCT.md).

## Submission Guidelines
We use GitHub issues for each Flynt repository to keep track of all incoming queries (feature requests, bug reports, and questions). Please use the most relevant repository for submitting your issue:

- [Flynt Theme Issues](https://github.com/flyntwp/flynt-starter-theme/issues)
- [Flynt Core Issues](https://github.com/flyntwp/flynt-core/issues)
- [Flynt Docs Issues](https://github.com/flyntwp/flynt-docs/issues)
- [Flynt CLI Issues](https://github.com/flyntwp/flynt-cli/issues)
- [Flynt Generator Issues](https://github.com/flyntwp/generator-flynt/issues)
- [Flynt Docker Issues](https://github.com/flyntwp/docker-flynt-build/issues)
- [ACF Field Composer Issues](https://github.com/flyntwp/acf-field-group-composer/issues)

### Issues and Bugs
Before you submit your issue please search GitHub issues first, maybe your question was already answered.

If your issue appears to be a bug, and hasn't been reported, open a new issue. Help us to maximize the effort we can spend fixing issues and adding new features, by not reporting duplicate issues. Providing the following information will increase the chances of your issue being dealt with quickly:

- **Overview of the Issue** - if an error is being thrown a non-minified stack trace helps.
- **Motivation for or Use Case** - explain why this is a bug for you.
- **Flynt Version(s)** - is it a regression?
- **Browsers and Operating System** - is this a problem with all browsers or only specific ones?
- **Reproduce the Error** - provide a live example, or an unambiguous set of steps.
- **Related Issues** - has a similar issue been reported before?
- **Suggest a Fix** - if you can't fix the bug yourself, perhaps you can point to what might be causing the problem (line of code or commit).

## Feature Requests
You can request a new feature by submitting an issue to the [relevant GitHub Repository](#submission-guidelines). If you would like to implement a new feature then consider what kind of change it is:

- **Major Changes** should be discussed first [in an issue](#issues-and-bugs) so that we can better coordinate our efforts, prevent duplication of work, and help you to craft the change so that it is successfully accepted into the project.
- **Small Changes** can be crafted and submitted to the [relevant GitHub repository](#submission-guidelines) as a Pull Request.


## Pull Requests
Before you submit a pull request please adhere to the following guidelines:

- Search the [relevant GitHub repository](#submission-guidelines) for an open or closed pull request that relates to your submission. You don't want to duplicate effort.

- Make your changes in a new git branch. **If you are submitting a change for the [Flynt Start Theme](https://github.com/flyntwp/flynt-starter-theme), branch from the `develop` branch, not `master`.**

```
git checkout -b myFixBranch master
```

- Follow our [Coding Rules](#coding-rules).

- Commit your changes using a descriptive commit message that follows our [commit message conventions](#commit-messages)

- Build and test your changes locally to ensure that everything works.

- Push your branch to GitHub:

```
git push origin myFixBranch
```

- In GitHub, send a pull request to the `master` branch. **If you are submitting a pull request to the [Flynt Start Theme](https://github.com/flyntwp/flynt-starter-theme), send your pull request to the `develop` branch, not `master`.**

- If the pull request gets too out-dated, we may ask you to rebase and force push to update the pull request:

```
git rebase master -i
git push origin myFixBranch -f
```

_WARNING: Squashing or reverting commits and force-pushing thereafter may remove GitHub comments on code that were previously made by you or others in your commits. Avoid any form of rebasing unless necessary._

That's it! Thank you for your contribution!

## Coding Rules
### Commit Messages

We follow the [AngularJS git commit guidelines](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#-git-commit-guidelines) for all Flynt repositories. This leads to more readable and consistent messages that are easy to follow when looking through the project history. Please adhere to these guidelines.

The commit message formatting can be added using a typical git workflow or through the use of the CLI wizard [Commitizen](https://github.com/commitizen/cz-cli).

### PHP
When writing PHP, follow the [PSR-2 coding style guide](http://www.php-fig.org/psr/psr-2/#overview).

### JavaScript
When writing JavaScript, follow the [Standard JS](https://standardjs.com/#the-rules) style guide.

### Templates and Styles
When writing view templates or style files, please always:

- Use 2 spaces to indent your code.
- Follow the [MaintainableCSS](https://maintainablecss.com/) approach to CSS.
- Keep the [Flynt best practices](https://docs.flyntwp.com/guide/best-practices) in mind.
