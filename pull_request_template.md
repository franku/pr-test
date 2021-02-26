### Thank you for contributing to the Bareos Project!

Please have a look at the following author-checklist: 

#### Checklist for the _author_ of the PR

- [ ] Add a small description to the CHANGELOG.md file and refer to your PR using this syntax '[PR #xyz]'
- [ ] Add your name to the AUTHORS file

### Helpful documentation:

- [Git Workflow](https://docs.bareos.org/DeveloperGuide/gitworkflow.html)
- [Automatic Sourcecode Formatting](https://docs.bareos.org/DeveloperGuide/generaldevel.html#automatic-sourcecode-formatting)
- [Check your commit messages](https://docs.bareos.org/DeveloperGuide/gitworkflow.html#commits)



#### Checklist for the _reviewer_ of the PR:

- [ ] Is the PR Name meaningful?
- [ ] Is the purpose of the PR understood?
- [ ] Are the commit comments understandable and well formatted?
- [ ] Is the source code understandable?
- [ ] Are variable and function names meaningful?
- [ ] Are comments correct (logic and spelling ?)
- [ ] Is there an entry in the ChangeLog for this PR?
- [ ] Is a documentation change required (and part of the PR)?
- [ ] does "check-sources --since-merge" report any problems? 
    
- [ ] Build and run the PR and execute the available tests and check if they are successful.
- [ ] are compiler errors or warnings added?

- [ ] if a Test is added:
- [ ]   does the testname match tell what is being tested?
- [ ]   If it is a system test: could the same be achieved as unit test?
- [ ]   Does a test failure tell what went wrong?
- [ ]   if no test is added:
- [ ]   is a test required? 
