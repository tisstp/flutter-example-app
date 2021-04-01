# Git Design Pattern

Format of the commit message:
```text
<type>(<scope>): <subject> // The first line cannot be longer than 70 characters.

<body> // The second link should be wrapped at 80 characters.

<footer> // Referencing issues or Breaking changes
```

Example:
```text
fix(middleware): ensure Range headers adhere more closely to RFC 2616

Add one new dependency, use `range-parser` (Express dependency) to compute
range. It is more well-tested in the wild.

Fixes #2310, #2400
```

Type
- `build`: Build related changes (eg: npm related/ adding external dependencies)
- `chore`: A code change that external user won't see (eg: change to .gitignore file or .prettierrc file)
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation related changes
- `refactor`: A code that neither fix bug nor adds a feature. (eg: You can use this when there is semantic changes like renaming a variable/ function name)
- `perf`: A code that improves performance
- `style`: A code that is related to styling
- `test`: Adding new test or making changes to existing test

Scope
- `init`
- `runner`
- `watcher`
- `config`
- `web-server`
- `proxy`
- `pattern`
- `etc.`

References:
- [Dev.to - Git Commit Msg](https://dev.to/i5han3/git-commit-message-convention-that-you-can-follow-1709)
- [Karma - Git Commit Msg](http://karma-runner.github.io/6.2/dev/git-commit-msg.html)


## IDE Shortcuts for Faster Developments

- [Android Studio](https://medium.com/flutter-community/flutter-ide-shortcuts-for-faster-development-2ef45c51085b)
- [VS Code](https://medium.com/flutter-community/flutter-visual-studio-code-shortcuts-for-fast-and-efficient-development-7235bc6c3b7d)

