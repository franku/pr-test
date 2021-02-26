### Thank you for contributing to the Bareos Project!

- [ ] Please add your name to the AUTHORS file if you want

In the following links you will find documentation on our best practices. If you have any questions or problems, please comment in the PR. 

### Helpful documentation:

- [Git Workflow](https://docs.bareos.org/DeveloperGuide/gitworkflow.html)
- [Automatic Sourcecode Formatting](https://docs.bareos.org/DeveloperGuide/generaldevel.html#automatic-sourcecode-formatting)
- [Check your commit messages](https://docs.bareos.org/DeveloperGuide/gitworkflow.html#commits)


#### Checklist for the _reviewer_ of the PR (will be processed by Bareos):

##### General 

- [ ] PR Name is meaningful
- [ ] Purpose of the PR is understood
- [ ] Separate commit for this PR in the CHANGELOG.md
- [ ] Commit descriptions are understandable and well formatted

##### Source code quality

- [ ] Source code changes are understandable
- [ ] Variable and function names are meaningful
- [ ] Code comments are correct (logically and spelling)
- [ ] Required documentation changes are present and part of the PR
- [ ] "check-sources --since-merge" does not report any problems
    
- [ ] if a Test is added:
- [ ]   does the testname match tell what is being tested?
- [ ]   If it is a system test: could the same be achieved as unit test?
- [ ]   Does a test failure tell what went wrong?
- [ ]   if no test is added:
- [ ]   is a test required? 
