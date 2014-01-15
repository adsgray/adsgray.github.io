---
layout: post
title: Using git-crypt for Jekyll drafts
allsummary: github hack
githubrepo: [adsgray.github.io]
---

The "source code" for this blog is hosted publicly on github.
There are some posts-in-progress in the **\_drafts** folder and I'd prefer that they
not see the light of day until they are complete. On the other hand I'd like
to store them on github along with the rest of the repository.

I'm trying out [git-crypt](https://github.com/AGWA/git-crypt) to encrypt the files in the **\_drafts** directory so that
I can store them in the repository and edit them freely but not disclose their
contents until they are ready. 

That's why the files are named *draft1-abc*, *draft2-xyz*, etc.  Naming the
files after the blog post's eventual title would leak too much information.
To post one I'll mv it from **\_drafts/draftN.md** to
**\_posts/YYYY-MM-DD-real-title.md**. 



