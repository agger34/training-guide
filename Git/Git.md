# Git

## 1. Goal

in 2-3 days, you must get technical knowledge and skills as below:

- to know what is Git
- to set up and use Git via command
- to use some Git Gui(source tree..)

## 2. Reference

- Reference:
  - https://nvie.com/posts/a-successful-git-branching-model/
  - http://git-scm.com/book/en/v2(the first 4 chapters)
  - https://backlog.com/git-tutorial/vn/intro/intro1_1.html
- Common Git Commands: https://github.com/joshnh/Git-Commands
- Git Gui: https://www.sourcetreeapp.com/
- Base:
  - local:
    - working directory
    - staging area
    - local repository
  - remote repository
  - file status lifecycle
    - untracked
    - unmodified
    - modified
    - staged

## 3. [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)

See how a minor change to your commit message style can make you a better programmer.

Format: `<type>(<scope>): <subject>`

`<scope>` is optional

### Example

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)

References:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
