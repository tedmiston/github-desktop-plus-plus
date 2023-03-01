# [WIP] GitHub Desktop++

[GitHub Desktop][0] is a cross-platform GUI Git client; it is minimally configurable which is a detriment to advanced users vs more powerful clients, like Tower.

The purpose of the **_GitHub Desktop++_** fork is to make GHD more useful for advanced Git users.

## Changes from upstream GitHub Desktop

- [ ] **Disable auto-staging of changed files** (https://github.com/desktop/desktop/issues/1788)
  - Auto-staging all changed files is a bizarre [and annoying][1] default for users that have used any other Git client on earth, which do not do this.

- [ ] **Allow empty commit messages**
  - This feature is useful for non-code repos and for automated commits
  - This is a native feature of git [`--allow-empty-message`][2] which GHD blocks use of
  - Other git clients allow this natively, but GitHub Desktop does not

- [ ] **Auto-stash and unstash**
  - [Automatic stashing][3] (like Tower) when required

[0]: https://github.com/desktop/desktop
[1]: https://github.com/Microsoft/vscode/issues/26185
[2]: https://git-scm.com/docs/git-commit#Documentation/git-commit.txt---allow-empty-message
[3]: https://www.git-tower.com/help/guides/working-copy/stash/mac
