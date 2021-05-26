# cedit

A small tool to ease the editing of git history

This script will begin an interactive git rebase, and drop you into a
shell immediately after the commit you specified has been applied.

To edit a commit's content and/or message, invoke this script as:

```
$ cedit <commit-ish-to-edit>
```

Any of these examples should work:

```
$ cedit c71276fbb142e320a2fef03fd7bb35dc9890b609
$ cedit c71276f
$ cedit HEAD^^^
```

NB This script has *not* been extensively tested!
