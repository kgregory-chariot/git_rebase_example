Example repository for Chariot Day talk

This repository contains commits for three scenarios:

* "Simple rebase" of branch from main.
* Rebase with conflicts.
* Interactive rebase.

## Rebase with conflicts

Start by checking out branch `conflicts`

Then run `git rebase main`

This should fail with a conflict. You can pick the correct content, and continue the rebase with `git rebase --continue`.

This line shouldn't cause a conflict, since it's added to the end of the previous commit
