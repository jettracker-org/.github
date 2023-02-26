# Contributing to JetTracker.org

We love your input! 🚀 We want to make contributing to this project as easy and transparent as possible. As a result, all of our repositories, except the Web Application[^1], are publicly available. You can, therefore, easily contribute to the cause by:

- Report bugs.
- Creating pull requests. 
- Submitting fixes.
- Proposing new features.
- Becoming a maintainer.
- [Ask or answer questions](https://github.com/jettracker-org/community).
- [Discussing the current state of the project](https://discord.com/invite/EhVPmRK7P4).

If you are interested in helping or want to know more about us, please hop into our [discord server](https://discord.gg/EhVPmRK7P4) 🧙💬.

[^1]: Private for now, but like all other of our repositories is licensed under an MIT license.

## We Use [Github Flow](https://guides.github.com/introduction/flow/index.html), So All Code Changes Happen Through Pull Requests

Pull requests are the best way to propose changes to the codebase (we use [Github Flow](https://docs.github.com/en/get-started/quickstart/github-flow)). We actively welcome your pull requests:

1. Fork the repo and create your branch from `master`.
2. Add tests if you've added code that should be tested.
3. If you have changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Build the node package using the `npm run build` and `npm run package` commands.
7. Make sure your code is [formatted](#Use-a-Consistent-Coding-Style).
8. Issue that pull request!

## Any contributions you make will be under the Licence found in the respective repository

In short, when you submit code changes, your submissions are understood to be under the same license covering the repository. Feel free to contact the maintainers if that is a concern.

## Report bugs using Github's issues

We use GitHub issues to track public bugs. Report a bug by opening a new issue in the repository that contains the bug; it's that easy!

## Write bug reports with detail, background, and sample code

[This is an example](http://stackoverflow.com/q/12488905/180626) of a good bug report. Here is [another example from Craig Hockenberry](http://www.openradar.me/11905408), an app developer greatly respected in the coding community.

**Great Bug Reports** tend to have:

-   A quick summary and/or background.
-   Steps to reproduce:
    -   Be specific!
    -   Give a sample code if you can. [the stackoverflow question above](http://stackoverflow.com/q/12488905/180626) includes sample code that _anyone_ with a base R setup can run to reproduce what I was seeing.
-   What you expected would happen
-   What actually happens.
-   Notes (possibly including why you think this might be happening or stuff you tried that didn't work).

People _love_ thorough bug reports. I'm not even kidding.

## Use a Consistent Coding Style

We use linters, test libraries and formatters to keep our codebase bug free and clean. More information about his can be found in the `CONTRIBUTING.md` file of the individual repositories. To summarize:
Javascript/Typescript code is currently linted using [Eslint](https://eslint.org/), tested using [Jest](https://jestjs.io/), and formatted using [prettier](https://prettier.io/).
Python code is currently linted using  [flake8](https://flake8.pycqa.org/en/latest/), tested using [Pytest](https://docs.pytest.org/en/latest/) and formatted using [Black](https://github.com/psf/black).
Feel free to create a discussion post on [https://github.com/orgs/jettracker-org/discussions](https://github.com/orgs/jettracker-org/discussions/new?category=ideas) if you think you have better alternatives.

## References

This document was adapted from the open-source contribution guidelines for [Facebook's Draft](https://github.com/facebook/draft-js/blob/a9316a723f9e918afde44dea68b5f9f39b7d9b00/CONTRIBUTING.md).
