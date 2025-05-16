# jujutsu-test

Can we figure out what Jujutsu is all about?

# Added in bookmark "branch"

Above was pushed with: `jj git push --remote origin --bookmark bookmark --allow-new`.

Lets try to push this too with: `jj git push --remote origin --bookmark bookmark` and it worked.

Thus:

1. you can add changes to the current "set" of changes
2. And push it and git won't complain
3. No need for `jj new` all the time

# Merging

+And a little conflict just for good measure.
+
 Or perhaps not merging... but another branch/bookmark.

... and just another one for good measure
-

-And a little conflict just for good measure.
+++++++ Contents of side #3

And a little conflict just for good measure.

Or perhaps not merging... but another branch/bookmark.

... and just another one for good measure.

... with a new changeset
