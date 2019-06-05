---
layout: post
title: Blog
subtitle: "Git subtree simple example"
date:   2019-03-30 21:55:20
---
Recently I've been uploading several older projects to GitHub. Then I stumbled into a problem.

I had shared VB.Net solutions, common DLLs which were used between different projects.

I was looking for a simple, approach to maintain a separate repo for a common solution which I could share with different solutions / repos.

I didn't find a simple method, but I figured git subtrees the easiest / best option.

Having said that, this discussion outlines my initial attempt at finding such a method, which seems to work well.

I'm making this really simple so it's easy to understand and easy for me to refer to in the future.

OK, I setup two repos, main and sub. The sub repo will be nested locally into the main folder.

Here's my repos...
```linenos
https://github.com/JulesMoorhouse/testing-subtrees-main-repo
https://github.com/JulesMoorhouse/testing-subtrees-sub-repo/tree/master
```

I put some obvious files in each.

I then opened terminal (or windows command line).

I cd'd into my documents folder.

I then created a subtrees folder.

Next, I cloned my main repo into that folder

```linenos
cd documents
mkdir subtrees
cd subtrees
git clone https://github.com/JulesMoorhouse/testing-subtrees-main-repo main
```

Ok, so notice the last parameter `main` this is the folder when I want the repo.

Next, I cd'd into the `main` folder and added / nested the `sub` repo.

```linenos
cd main
git subtree add --prefix=sub https://github.com/JulesMoorhouse/testing-subtrees-sub-repo.git master
```

Notice prefix here is the `sub` folder and the last parameter here is the branch `master`.

Ok, so let’s have a look at our folders in `subtrees`.

```linenos
Julians-MBP:subtrees jm$ ls -R
main

./main:
README.md	
main.txt	
sub

./main/sub:
README.md	s
ub.txt
```

Let’s add a new file in the `sub` folder.

```linenos
cd sub
touch sub-updated-file.txt
Git add .
git commit -m "added a new file to sub repo"
Git push
```

So, what just happened? I create a new file, staged it, commited it and pushed it.
So where did it push to?

Interesting I thought it would push to the `sub` repo, but no, it pushed to the `main` repo.

I guess that's really the way you'd want this to work!

So now let’s push this change to the `sub` repo.

```linenos
git subtree push --prefix=sub https://github.com/JulesMoorhouse/testing-subtrees-sub-repo.git master
```

Not as difficult as you think, right?

I guess now you'd setup everything, that last line is all you need going forward.

