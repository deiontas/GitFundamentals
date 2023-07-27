# Git Remote 

When working with git, a  **remote**  is any git repository the is not on the machine you're working on. The counterpart to this is **local**, or the machine that is being developed on.

Take Github for example. While git is the technology that allows you to create local respositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or you can share it with others.

**Note**: While repositories (local and remote) are related and track the same project, they can have different states if changes are not shared.

### Adding a remote
A remote can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local name, meaning its your lable and does not impact the actual remote whatsoever.

### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources
- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---
[Back to home](../README.md)