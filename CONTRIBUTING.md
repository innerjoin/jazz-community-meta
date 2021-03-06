# Taking part in the Jazz Community

We are a community effort, and everybody is most welcome to participate! You do not have to be listed on the Jazz Community page to be considered a member. Be it filing bugs, formulating enhancements, creating pull requests, or any other means of contribution, we encourage contributions from everyone. We are looking forward to collaborating with all fellow jazz users.

This document is a loose guideline showing ways for you to contribute.

## Table of Contents
-   [Git](#git)
    -   [Tutorial](#tutorial)
    -   [Pro Git](#pro-git)
    -   [Pull requests](#pull-requests)
    -   [Commit messages](#commit-messages)
-   [Suggesting enhancements](#suggesting-enhancements)
-   [Reporting bugs](#reporting-bugs)
-   [Submitting pull requests](#submitting-pull-requests)
-   [Including your project](#including-your-project)
-   [Becoming a member](#becoming-a-member)
-   [Getting in touch](#getting-in-touch)
-   [Improving this document](#improving-this-document)

## Git

If you are unfamiliar with git, the internet is filled with with a wealth of excellent resources. Use whatever you need to become comfortable, these are only some suggestions to get you started. As an absolute first step, any contribution requires you to [join GitHub by creating your own account](https://github.com/join).

### Tutorial
Github provides an excellent interactive tutorial to get you ramped up on the basics: [Github interactive tutorial](https://try.github.io/levels/1/challenges/1)

### Pro Git
If you want to dive deep and learn the intricacies of git, the [Pro Git](https://git-scm.com/book/en/v2) book is a fantastic read. It includes chapters on how to [get started](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) and covers [the basics](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository), continues with [branching](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) and even includes a [chapter specifically on GitHub](https://git-scm.com/book/en/v2/GitHub-Account-Setup-and-Configuration).

### Pull requests
Pull requests are the canonical way of contributing to projects on github. If you have never created a pull request, or want to make sure that you are going about contributing the right way, check out this [step-by-step guide](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940).

### Commit messages
Commit messages are a central element of contributing to git projects. They provide a history of your work, and well written commit messages are a central resource of well curated git projects. [This blog post](https://chris.beams.io/posts/git-commit/) summarizes what is generally considered good practice for formulating great commit messages.

## Suggesting enhancements
Our goal is to improve the Jazz platform together with you, and we need your ideas and input to keep on improving. Opening issues to discuss enhancements is a great way to encourage improvement as a community. Open an issue where you feel it fits best. To get the most out of your enhancements, we have some suggestions on what you can include in your issue.

- **Use a descriptive title** summarizing the core improvement you suggest
- **Describe the workflow** that you wish to add
- **Add a use case diagram** if you feel that is a good way to present your idea
- **Include screenshots or mockups** if you have UI enhancements
- **Mention other tools** that provide features similar to what you would like to see in the project

Do whatever you think is necessary to best present your enhancement.

## Reporting bugs
Choose the repository that you think the bug belongs to most, and create an issue there. It is easiest to create a separate issue for every bug that you encounter.

The following is not a mandatory list of information, but a recommendation of what can make sense to include in your issue. Include what you think is crucial to best demonstrate your problem, and help your fellow community members in finding a solution.

- **Use a descriptive title** that describes the essence of your problem
- **Include clear steps to reproduce the problem.** Include as much information as possible.
- **Provide information about your system**, the version you are experiencing problems with, the environment you are using, your operating system etc.
- **Explain where and how your experienced behavior differs from what you expected**
- **Include screenshots** to provide more information and context
- **Add as much context as possible** in any way you see fit and necessary.

## Submitting pull requests
If you are unsure about *how* to create a pull request, [this guide](https://codeburst.io/a-step-by-step-guide-to-making-your-first-github-contribution-5302260a2940) should get you on track.

We welcome any contributions that improve the quality of our projects. Be it pull requests for spelling and grammar mistakes or entire enhancements. When creating a pull request, check the project's `README.md` and `CONTRIBUTIONS.md` files for possible additional information on what is required to commit code or other changes, such as including unit tests or conforming to the style of the project. The following are suggestions of what can be included in a good pull request.

- **Use a descriptive title** to present your work
- **Make sure all your changes are included** and that you did not leave out any changes that you wish to contribute.
- **Describe your changes in detail** to show your peers exactly what you have contributed
- **Include issues in your description** if your changes refer to bugs, enhancements or other types of issues
- **Conform to the style of the project**, such as keeping the same indentation level and brace style

Information on how to develop on a project and how to create builds are usually included in the projects README. If the supplied information is insufficient for you to get started, do not hesitate to create an issue and ask for help. We want to keep the barrier to entry as low as possible.

## Including your project
Our preliminary goal was to establish the _jazz-community_ organization as the preferred way to get access to published Jazz extensions. There are already a few extensions milling around the web, but most of them are either only _source code_ or just a _compiled artifact_.
Therefore, we would gladly welcome other projects into the _jazz-community_. There are multiple ways to include your project:

### Move a repository to _jazz-community_
If you already have an awesome repository that would be well suited for the _jazz-community_ organization, we can take the necessary steps to move your repository into the _jazz-community_ organization together. To ensure a certain amount of quality and consistency across the entire organization, we assume the following to be met:
- The project is actively maintained and you will continue to actively maintain the repository in the near future
- The `CONTRIBUTING.md` file of your repository must derive from this contribution guide. Hence, your repository should apply these guidelines today or you should be willing to follow them from now onward
- Your project has an appropriate `LICENSE` and `README.md` file
- You have applied common software engineering practices to ensure readability and maintainability of the source code
- Continuous Integration is available where possible. The build is automated on [Travis CI](https://travis-ci.org/jazz-community) and the releases are pushed back to the GitHub _Releases_ page if a build contains a new git tag (e.g. v1.2.0).

Please get in touch with one of our [Org Admins](https://github.com/orgs/jazz-community/teams/org-admin/members) to discuss the details.

### Mention a repository
If you prefer to keep your repository as part of your user profile or within your companies GitHub organization, we can still mention your project as part of our _[Other useful Repositories](https://github.com/jazz-community/welcome#other-useful-repositories)_ list. If you want to be mentioned there, just send us a Pull Request with your additions to the list.

## Becoming a member
All _jazz-community_ projects are public, so you can contribute to any repository through pull requests. Every repository has an owning team associated which will drive the project, merge pull requests, and manage releases. If you want to become a _core member_ of a project, open an issue within that repository and express your wish. To ensure the quality of our projects, you may have to fulfill one of the following requirements:
- You have proven your skills by contributing high quality pull requests within that repository in the past
- You are endorsed by an existing core member to join
- You have proven your skills in another open source project and you agree with the project vision of the existing members

If your project is about to be moved to the _jazz-community_ organization, you will remain _core member_ of that repository.

## Getting in touch
The only way to get in touch with us at the moment is to open an _Issue_ in one of the repositories. We do not have any chat room like Slack or Gitter for informal exchange as of now, so you can open an _Issue_ if you have a question even if it not necessarily is a potential issue.

## Improving this document
This contribution guideline is subject to the conditions that are described here. If you have suggestions for improvement, open an issue or create a pull request!
