# Goal-s
Goal 1 &amp; 2 of July
1. Goals

Allow repository users to digitally sign committed changes, so that:

  - Others can verify the authenticity of a commit;

  - Hacked modification and (optionally) deletions of historical
    revisions can be detected.


2. Features

2.1 Client-side signing of committed changesets

If changeset signing is enabled, the client sends a signed hash of the
changes to the server as part of the commit. This signature is stored
in a new revprop, svn:signature.
this release is for july 2020
