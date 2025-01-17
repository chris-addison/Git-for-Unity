# Contributing to Git for Unity

:+1: :tada: :sparkling_heart: Thanks for your interest! :sparkling_heart: :tada: :+1:

The following is a set of guidelines for contributing to Git for Unity.
These are just guidelines, not rules. Use your best judgment, and
feel free to propose changes to this document in a pull request.

Note that Git for Unity is currently in preview, so everything is likely to
change over time as we learn and refine how we work with the community.

This project is a fork of GitHub for Unity, and therefore some of the information
here might not be fully up to date, and there may be links going to the wrong places.
We're cleaning things up as we go!

#### Table Of Contents

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [Code of Conduct](#code-of-conduct)
  * [The Roadmap](#the-roadmap)

[How Can I Contribute?](#how-can-i-contribute)
  * [How to Build](#how-to-build)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Up for Grabs](#up-for-grabs)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## What should I know before I get started?

### Code of Conduct

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.

### The Roadmap

This project is a fork of GitHub for Unity and is currently in preview. The API part of GitHub for Unity is a .NET Git Client library, without any dependencies on Unity itself. Only the UI part of GitHub for Unity is Unity-specific.

The same applies to this project, which is split into two packages - `com.unity.git.api` - the Git client library; and `com.unity.git.ui` - a Unity Git UI based on the GitHub for Unity UI, which examplifies how to use the Git client library.

Even though this project is currently a fork, we plan for the API part of this project to become the authoritative implementation source, and split entirely from the original GitHub for Unity implementation.

We're doing this so we can improving the integration between Git and Unity
by exposing additional version control C# APIs that Git for Unity can leverage.
Therefore, the API may change while we build this, and this project may become dependent on
more recent versions of Unity.

## How Can I Contribute?

### How to Build

This repository is LFS-enabled. To clone it, you should use a git client that supports git LFS 2.x and submodules.

Please read the [How to Build](https://raw.githubusercontent.com/Unity-Technologies/Git-for-Unity/master/docs/contributing/how-to-build.md) document for information on how to build Git for Unity.

### Reporting Bugs

This section guides you through submitting a bug report for Git for Unity.
Following these guidelines helps maintainers and the community understand your
report :pencil:, reproduce the behavior :computer: :computer:, and find related
reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report)
as you might find out that you don't need to create one. When you are creating
a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report).
Fill out [the required template](./.github/ISSUE_TEMPLATE.md), the information
it asks for helps us resolve issues faster.

#### Before Submitting A Bug Report

As this is still a fork, there are a lot of existing issues [reported upstream](https://github.com/github-for-unity/Unity/labels/bug). **Perform a [cursory search](https://github.com/github-for-unity/Unity/labels/bug) there and [here](https://github.com/Unity-Technologies/Git-for-Unity/labels/bug)**
to see if the problem has already been reported.

If it does exist, add a [reaction](https://help.github.com/articles/about-discussions-in-issues-and-pull-requests/#reacting-to-ideas-in-issues-and-pull-requests)
to the issue to indicate this is also an issue for you, and add a
comment to the existing issue if there is extra information you can contribute.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [Git issues](https://guides.github.com/features/issues/).

Simply create an issue on the [Git for Unity issue tracker](https://github.com/Unity-Technologies/Git-for-Unity/issues)
and fill out the provided [issue template](./.github/ISSUE_TEMPLATE.md).

The information we are interested in includes:

 - details about your environment - which build, which operating system
 - details about reproducing the issue - what steps to take, what happens, how
   often it happens
 - other relevant information - log files, screenshots, etc.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for
Git for Unity, including completely new features and minor improvements to
existing functionality. Following these guidelines helps maintainers and the
community understand your suggestion :pencil: and find related suggestions
:mag_right:.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion)
as you might find out that you don't need to create one. When you are creating
an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion).
Fill in [the template](./.github/ISSUE_TEMPLATE.md), including the steps
that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

As this is still a fork, there are a lot of existing issues [reported upstream](https://github.com/github-for-unity/Unity/labels/bug). **Perform a [cursory search](https://github.com/github-for-unity/Unity/labels/bug) there and [here](https://github.com/Unity-Technologies/Git-for-Unity/labels/bug)**
to see if the enhancement has already been suggested. If it has, add a
:thumbsup: to indicate your interest in it, or comment if there is additional
information you would like to add.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [Git issues](https://guides.github.com/features/issues/).

Simply create an issue on the [Git for Unity issue tracker](https://github.com/Unity-Technologies/Git-for-Unity/issues)
and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the
  suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as
  much detail as possible. This additional context helps the maintainers to
  understand the enhancement from your perspective
* **Explain why this enhancement would be useful** to Git for Unity users.
* **Include screenshots and animated GIFs** if relevant to help you demonstrate
  the steps or point out the part of Git for Unity which the suggestion is
  related to. You can use [this tool](http://www.cockos.com/licecap/) to record
  GIFs on macOS and Windows.
* **List some other applications where this enhancement exists, if applicable.**

### Up For Grabs

As the team is working towards the 2.0 release, we'll identify enhancements or
bugs that can be categorized as tasks that:

 - have low impact, or have a known workaround
 - should be fixed
 - have a narrow scope and/or easy reproduction steps
 - can be worked on independent of other tasks

These issues will be labelled as [`up-for-grabs`](https://github.com/Unity-Technologies/Git-for-Unity/labels/up-for-grabs)
in the repository. If you are interested in contributing to the project, please
comment on the issue to let the maintainers (and community) know you are
interested in picking this up.

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and
pull requests.

#### Type of Issue and Issue State

| Label name | :mag_right: | Description |
| --- | --- | --- |
| `enhancement` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/enhancement) | Feature requests. |
| `bug` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/bug)  | Confirmed bugs or reports that are very likely to be bugs. |
| `question` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/question)  | Questions more than bug reports or feature requests (e.g. how do I do X). |
| `more-information-needed` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/more-information-needed) | More information needs to be collected about these problems or feature requests (e.g. steps to reproduce). |
| `needs-reproduction` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/needs-reproduction)  | Likely bugs, but haven't been reliably reproduced. |
| `macOS` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/macOS)  | Issues specific to macOS users. |
| `Windows` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/Windows)  | Issues specific to Windows users. |
| `Linux` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/Linux)  | Issues specific to Linux users. |

#### Topics

| Label name | :mag_right: | Description |
| --- | --- | --- |
| `up-for-grabs` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/up-for-grabs)  | Issues marked as ideal for external contributors. |
| `polish` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/polish) | Issues not critical to the application but would provide a better experience if resolved. |
| `tech-debt` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/tech-debt) | Issues related to code or architecture decisions. |
| `design` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/design)  | Issues that require some design input from the maintainers as part of completing the work. |

#### Workflow

| Label name | :mag_right: | Description |
| --- | --- | --- |
| `ready-for-review` | [search](https://github.com/Unity-Technologies/Git-for-Unity/labels/ready-for-review)  | Pull Requests that are ready to be reviewed by the maintainers. |
