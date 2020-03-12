# Contributors Guide

So you've decided to become a contributor to our project. Excellent!

We are always looking for new developers, so if you're new,
please check out our Getting Started guide.

But before we can start accepting your code, there are a couple of
things you should know about how we work. 

This document mostly contains guidelines and rules as to how your
code should be structured and how it can be committed without
upsetting any fellow contributors.

## How to code

Starter coding information can be found on our "[Coding info]" page,
including stuff like:

- folder explanation
- individual projects (modules) within the above folders
- simplification of data types
- debug commands
- more

[Coding info]: https://wiki.multitheftauto.com/wiki/Coding_info

## Where to code

As a new potential contributor, you will need to fork our repository and make
commits to your own "branch". Then you can send us a pull request.

Our _`master`_ branch is the main development branch containing the
latest, bleeding-edge code.

Our _other_ branches contain groundbreaking research, radical ideas and other
work-in-progress changes that are meant to be merged into `master` at
a later point in time.

## What to code

Generally, developers should try to only submit pull requests that resolve existing
[issues](https://github.com/multitheftauto/mtasa-blue/issues).

If you're looking for something to work on, take a look at:
- our ["good first issue"] label, and
- our [milestones]

["good first issue"]: https://github.com/multitheftauto/mtasa-blue/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22good+first+issue%22
[milestones]: https://github.com/multitheftauto/mtasa-blue/milestones?direction=asc&sort=due_date

**TODO: below may need to be rephrased**

Of course, if you're interested in something else, feel free to experiment
and submit it.

## Committing code

Please follow these guidelines for all your contributions:

-   Commits should be thoroughly tested when added to master. Commits
    that 'need to be fixed later' which directly affect the state of
    the mod will be reverted other than in exceptional circumstances.
-   If writing unstable or experimental code, a private branch should be
    added in your own fork. Branches should not be "personal" to each
    user. This means that a branch should be created for a new feature,
    not for a user specific playground.
-   Commit messages should always give a clear indication of the content
    of the change, without having to look at the code at all. Where
    appropriate, include the issue number in your log message and
    keep your log messages consistent, e.g. **Fix #1234: description
    and notes here**.
-   Don't forget to use [GitHub keywords](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).
-   [Follow the seven rules identified here.](http://chris.beams.io/posts/git-commit/)
-   When committing updates to previous commits, include the previous
    commit SHA (and a summarised commit message) in the new commit
    message. Doing this will help identify related commits if they are
    viewed at a later date.
-   Follow the [Style Guide](https://github.com/multitheftauto/mtasa-blue/wiki/Style-Guide)

## Reviewing code

**TODO: needs review guide, needs content from: https://github.com/thoughtbot/guides/tree/master/code-review and https://gist.github.com/mrsasha/8d511770ad9b282f3a5d0f5c8acdd10e**

Ratings and comments are open for the public to review code and provide
feedback. Please be mature and civilised when posting comments.
Developers should try to review other contributor\'s commits and provide
feedback as much as possible.

Make sure you make appropriate use of the GitHub Reactions feature to
rate commits or express agreement/disagreement to a comment. This avoids
spammy comments such as \"+1\", \"-1\", \"Nice one!\", etc.

Since you can only react to comments, not commits, feel free to create
the initial \"+1\" comment in response to a commit. However, future
reactions to a commit should be to the first response comment.

## Gaining and losing merge rights

Merge rights allow you to merge your own approved pull requests and 
review other people's pull requests.

We grant merge rights after you have proven yourself to be competent,
this is generally after 3-5 pull requests, but it's not fixed and depends
on the extent of your contributions.

The subject matter of your PRs do not matter—we are more interested in,
once granted merge rights, whether you are capable of maintaining
a high standard of code and remaining cohesive with other project collaborators.

After gaining merge rights, if your contributions are of a consistently low standard,
or you fail to stick to the rules, your permissions will be stripped and will no longer
be able to merge submitted pull requests or create your own branches.
