7 GitHub pull request template examples


Here are 7 examples of pull request template we made and found on the web: 

Find more on <a
            href="https://github.com/stevemao/github-issue-templates"
            rel="noopener noreferrer"
            target="_blank">SteveLao GitHub issue templates</a> and <a href="https://github.com/devspace/awesome-github-templates" rel="noopener noreferrer" target="_blank">Awesome GitHub templates</a>



## Example 1: Simple Pull request template:
```
## What does this PR do?


## Jira ticket number?

## Checklist before merging
- [ ] If its a core feature, I have added through test.
- [ ] Do we need to implement analytics? 
- [ ] Will this be part of a product update? If yes, please write one phrase about this update

```

## Example 2: Todo list pull request template

```
# Description

Please include a summary of the change and which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

Fixes # (issue)

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

# How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Please also list any relevant details for your test configuration

- [ ] Test A
- [ ] Test B

**Test Configuration**:
* Firmware version:
* Hardware:
* Toolchain:
* SDK:

# Checklist:

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules

```

## Example 3: GitHub issue template for bugs:

```
THIS PROJECT IS IN MAINTENANCE MODE. We accept pull-requests for Bug Fixes **ONLY**. NO NEW FEATURES ACCEPTED!

<!--- Provide a general summary of your changes in the Title above -->

## Description
<!--- Describe your changes in detail -->

## Related Issue
<!--- This project only accepts pull requests related to open issues -->
<!--- If suggesting a new feature or change, please discuss it in an issue first -->
<!--- If fixing a bug, there should be an issue describing it with steps to reproduce -->
<!--- Please link to the issue here: -->

## Motivation and Context
<!--- Why is this change required? What problem does it solve? -->
<!--- If it fixes an open issue, please link to the issue here. -->

## How Has This Been Tested?
<!--- Please describe in detail how you tested your changes. -->
<!--- Include details of your testing environment, and the tests you ran to -->
<!--- see how your change affects other areas of the code, etc. -->

## Screenshots (if appropriate):

```

## Example 4: Checklist GitHub issue template

```
### All Submissions:

* [ ] Have you followed the guidelines in our Contributing document?
* [ ] Have you checked to ensure there aren't other open [Pull Requests](../../../pulls) for the same update/change?

<!-- You can erase any parts of this template not applicable to your Pull Request. -->

### New Feature Submissions:

1. [ ] Does your submission pass tests?
2. [ ] Have you lint your code locally prior to submission?

### Changes to Core Features:

* [ ] Have you added an explanation of what your changes do and why you'd like us to include them?
* [ ] Have you written new tests for your core changes, as applicable?
* [ ] Have you successfully ran tests with your changes locally?

```

## Example 5: Checklist and questions GitHub pull request template: 

```
* **Please check if the PR fulfills these requirements**
- [ ] The commit message follows our guidelines
- [ ] Tests for the changes have been added (for bug fixes / features)
- [ ] Docs have been added / updated (for bug fixes / features)


* **What kind of change does this PR introduce?** (Bug fix, feature, docs update, ...)



* **What is the current behavior?** (You can also link to an open issue here)



* **What is the new behavior (if this is a feature change)?**



* **Does this PR introduce a breaking change?** (What changes might users need to make in their application due to this PR?)



* **Other information**:
```

## Example 6: Dead simple GitHub pull request template

```
Fixes #

## Proposed Changes

  -
  -
  -
```

## Example 7: No Duplicate for JS project GitHub pull requests template:

```
## Pull Request template
Please, go through these steps before you submit a PR.

1. Make sure that your PR is not a duplicate.
2. If not, then make sure that:

    a. You have done your changes in a separate branch. Branches MUST have descriptive names that start with either the `fix/` or `feature/` prefixes. Good examples are: `fix/signin-issue` or `feature/issue-templates`.

    b. You have a descriptive commit message with a short title (first line).

    c. You have only one commit (if not, squash them into one commit).

    d. `npm test` doesn't throw any error. If it does, fix them first and amend your commit (`git commit --amend`).

3. **After** these steps, you're ready to open a pull request.

    a. Your pull request MUST NOT target the `master` branch on this repository. You probably want to target `staging` instead.

    b. Give a descriptive title to your PR.

    c. Provide a description of your changes.

    d. Put `closes #XXXX` in your comment to auto-close the issue that your PR fixes (if such).

IMPORTANT: Please review the [CONTRIBUTING.md](../CONTRIBUTING.md) file for detailed contributing guidelines.

**PLEASE REMOVE THIS TEMPLATE BEFORE SUBMITTING**

```
