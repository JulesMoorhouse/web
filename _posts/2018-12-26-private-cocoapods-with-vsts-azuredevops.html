---
layout: post
title: Blog
subtitle: "Private Pod (Cocoapods) with VSTS / AzureDevOps"
date:   2018-12-26 10:50:39
---

This is the first version of some instructions on how to create your own private Cocoapod and private specs repo using tfs / git.
In the future I hope to add screenshots

**Private spec repo**

From tfs create a repo / branch and a README.md
And add some text.
```
# my-specs
```

With terminal create a pod spec folder and setup git.

```
mkdir /Users/myuser/Code_ObjC/podspec
git init
git remote add origin https://myrepo.visualstudio.com/Pods/_git/my-specs
git fetch
```

You should have the README.md file from tfs locally.

Now run this command to add the your pod spec repo to your local cocoa pods setup.

```
pod repo add my-specs https://myrepo.visualstudio.com/Pods/_git/my-specs
```

You can confirm this by …

```
cd ~/.cocoapods/repos/my-specs
pod repo lint .
```

Now your pod spec repo is all setup to use in in any of your local projects by adding your specs repo to your pod file. This basically means you now have your own directory of pods.

**Creating your own private development pod**

As before create a new repo / branch e.g. (Don't add any files)

```
https://myrepo.visualstudio.com/Pods/_git/my-ui-code
```

Create a local folder for your private pods, in the next step a sub folder for your private will be created for you.

```
/Users/myuser/Code_ObjC/podsprivate
```

Now run the helper to create your development pod.

```
pod lib create my-ui-code
```

Follow the prompts making sure you add a demo project.
Notice that this process has also sets up local git for you.
This will create and open up an Xcode project ready for you to add your new functionality.

Firstly look for the ReadMe.m or ReadMe.swift file and add your files and remove said file.

Now the next several steps can be done in a different order if desired.

Now add your podspec contents and remember to add your git repo urls.

Now go to the .podspec location in terminal and run… this will validate your podspec.

```
pod lib lint 
```

Next add your development pod to your repo

```
git add .
git commit -m “Initial Commit”
git remote add origin https://myrepo.visualstudio.com/Pods/_git/my-ui-code
git push -u origin master
```

Next create a tag

```
git tag 0.1.0
git push origin 0.1.0
```

So now you have your private pod all safely under version control

You can now push your pod to your private spec repo using the following command

```
pod repo push my-specs my-ui-code.podspec
```

If you head over to your your my-specs repo you will see your repo has been pushed :)

