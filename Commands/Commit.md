# git commit

The command `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called a commit.

Commits come with commit messages that are required for each commit. you add a message to commit command by using the `-m` flag followed by a message in quotes.

A commit message _can_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

For example, if we have an application we're working on where we just built the ability to pay for a service through paypal, then you might use something worded like the following:

```
git add .
git commit -m "Added Paypal payment functionality"
```

When you view the history of the git repository, you can now see where the Paypal payment functionality was added.

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)