# Mind Professionals Style Guide
This markdown document includes the style guide for the Mind Professionals codebases

We follow the same TypeScript standard as google

https://google.github.io/styleguide/tsguide.html

## Git Branching Strategy / Flow
We use a bespoke branching strategy at Mind Professionals to ensure that we have true Continuous Integration and Development.

We have 3 permanent branches as follows:
* `main`: This will be major releases
* `bleeding`: This will be minor releases (may still contain bugs)
* `nightly`: This is updated once a day per developer

### How does this strategy work?
Every day we commit several times to issue-scoped branches. Create a branch for every issue (or two issues sometimes if they're closely related). At the end of the day we commit all of these to the `nightly` branch.

Once a new feature or collection of bug fixes is ready, we will push to the `bleeding` branch. This is cutting-edge features that are still unstable.

Finally, once we've gotten `bleeding` to a stable state, we will be able to merge it with `main`. If all checks pass, we increase the major version and we are ready to deploy / ship whatever is in the `main` branch.
