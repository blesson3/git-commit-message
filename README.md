# Git commit message

How to write a good git commit message that people can read and tools can parse.

## Canonical source

The canonical source of Jekyll HTML5 Youtube is hosted on [https://git.knowbl.co/dev/git-commit-message/](https://git.knowbl.co/dev/git-commit-message/).

## Commit verbs

Knowbl uses a git commit message convention that helps us read fast and also is parsable by toolchains.

We agree on a short list of leading active verbs:

* Add = Create a capability e.g. feature, test, dependency.
* Cut = Remove a capability e.g. feature, test, dependency.
* Fix = Fix an issue e.g. bug, typo, accident, misstatement.
* Bump = Increase the version of something e.g. dependency.
* Make = Change the build process, or tooling, or infra.
* Start = Begin doing something; e.g. create a feature flag.
* Stop = End doing something; e.g. remove a feature flag.
* Refactor = A code change that MUST be just a refactoring.
* Reformat = Refactor of formatting, e.g. omit whitespace.
* Optimise = Refactor of performance, e.g. speed up code.
* Document = Refactor of documentation, e.g. help files.

## The seven rules

* Separate subject from body with a blank line
* Limit the subject line to 50 characters
* Capitalise the subject line
* Do not end the subject line with a period
* Use the imperative mood in the subject line
* Wrap the body at 72 characters
* Use the body to explain what and why vs. how

## Reasoning

We primarily care that our team communicates effectively with our shared understanding. 

We secondarily like these verbs above because they're easy to read, easy to type, and clear in many cultures.

If you and your team prefer other words, that's fine too; use what works for you.


## Rejecting

We do reject some kinds of git commit message formats. For example, we reject messages that start with a leading tag, or flag, or abbreviation, or link, or tracking number, such as any of these styles:

* [bug] ...
* (release) ...
* jira://...
* docs: ...

We do reject the typical commit style of projets such as Angular, Commitizen defaults, etc., because these use a leading tag that is sometimes a word, sometimes an abbreviation, sometimes a plural noun, etc. (such as "feat" for feature, "docs" for document, "perf" for improving performance, etc.)
