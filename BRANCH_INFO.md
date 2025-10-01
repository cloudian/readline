# Branch Information

The `upstream-main` branch is updated on occasion to match
`chzyer/readline`.

The latest `cloudian-patches-*` branch should contain:

- `upstream-main`
- various cloudian fixes on top

A new `cloudian-patch-*` branch is created using the content
of the latest `cloudian-patch-*` branch which is then rebased
on top of `upstream-main` where any patch conflicts are updated
. The branch should then be pushed without any new additons.

New commits should be merged in with a PR to receive PR
gating.

The `cloudian-patch-*` branches are not currently cleaned up.

This repository does not have a `cloudian-main` due to the
preference of rebasing. The original `chzyer/readline` repo
is pretty stable also.
