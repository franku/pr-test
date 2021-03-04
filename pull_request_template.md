- add short description of changed and what is the target


### Thank you for contributing to the Bareos Project!

- [ ] Your name is added to the AUTHORS file if you want

In the following links you will find documentation on our best practices. 

If you have any questions or problems, please give a comment in the PR. 

### Helpful documentation:

- [Git Workflow](https://docs.bareos.org/DeveloperGuide/gitworkflow.html)
- [Automatic Sourcecode Formatting](https://docs.bareos.org/DeveloperGuide/generaldevel.html#automatic-sourcecode-formatting)
- [Check your commit messages](https://docs.bareos.org/DeveloperGuide/gitworkflow.html#commits)


### Checklist for the _reviewer_ of the PR (will be processed by Bareos):

##### General 

- [ ] PR Name is meaningful
- [ ] Purpose of the PR is understood
- [ ] Separate commit for this PR in the CHANGELOG.md, PR number referenced is same
- [ ] Commit descriptions are understandable and well formatted

##### Source code quality

- [ ] Source code changes are understandable
- [ ] Variable and function names are meaningful
- [ ] Code comments are correct (logically and spelling)
- [ ] Required documentation changes are present and part of the PR
- [ ] `check-sources --since-merge` does not report any problems
- [ ] `git status` should not report modifications in the source tree after building and testing

##### Tests

- [ ] Decision taken that a system- or unittest is required (if not, then remove this paragraph)
- [ ] The decision towards a systemtest is reasonable compared to a unittest
- [ ] Testname matches exactly what is being tested
- [ ] Output of the test leads quickly to the origin of the fault
