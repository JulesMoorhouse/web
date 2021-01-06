---
layout: post
title: Blog
subtitle: "Git subtree simple example"
date:   2019-03-30 21:55:20
---

### The current situation

### The problem

### How we got here

### The solution

### Sources


----
----

2021-01-01 Mindmap iOS Database Device / Multiuser Sync

https://docs.google.com/drawings/d/1UrvJPIXSZMalpp7k101i7FN9YbgqH15BDATPrIjwtbk/edit

----

What is my desired use case of NSPersistentCloudKitContainer ?

I’d like to be able to persist / share data similar to the Notes apps between different iCloud users.

Data shared between specific users shouldn’t be stored as public data, it should have some extra level of security, not available in the private context.

In my use case, I’d like to share budget data between users who may not be using the same icloud account or family options. This could be boy / girl friend or even business partners.

The NSPersistentCloudKitContainer provides excellent features in the public / private context but not in share / sync. Providing this functionality on top of NSPersistentCloudKitContainer mean circumventing a lot of the feature the api provides, which is counter productive.

----
----
Original DTS draft

----


### Title (Give a short title specific to your issue.) :-
CloudKit + CoreData: Now how do I take advantage of CloudKit user-to-user sharing without losing CoreData + CloudKit synchronization?

### Description (Describe your issue in detail.) :-
I’m looking for an approach which will enable me to create an app using CoreData and Cloudkit, to share records user to user and allow data to be synchronized. An example of this would be the Apple Notes app.

I’ve been researching this issue and have found NSPersistentCloudKitContainer that will allow me to create an app with CoreData and CloudKit. However CKDatabaseScopeShared is not supported with NSPersistentCloudKitContainer.

Here’s a forum post which highlights the issue.
https://developer.apple.com/forums/thread/649630?login=true&page=1#621748022

Obviously I couldn’t use a public container to store data used user to user. Likewise, a Private container will be inaccessible.

###Configuration (Describe your hardware and software configuration) :-
iOS 13+

###Steps to Reproduce (Describe the steps to reproduce your issues.) :-
N/A

