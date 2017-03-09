---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---


Meteor, to me, is a new framework. Like all frameworks, getting used to and mastering them takes a lot of time, all the more so if one is also dealing with the frantic minded-ness of also dealing with a language they haven't used for a few years. Getting used to the language and preferred style while learning the framework is a feet that is not only difficult, but also comes with a few technical challenges.

# Meteor of Problems

## Started at Installation

Unfortunately problems began for me at installation where it became visible only after I started trying to interact with MongoDB that's associated with Meteor. The problem that popped up threw an exception whenever I attempted to do anything with Mongo. The error's description displayed a filename that was associated with Meteor's framework, which at first made me think that there was something wrong with my installation, or, perhaps, that my <i>meteor npm install</i> failed for some reason. With that misconception, I was sent on a spiral of trials and errors of creating new meteor apps, reinstalling/manually updating meteor, reinstalling nodejs, and so on.

The fix, was actually much less about the installation of or lack of updated apps. It was actually much simpler and I frankly do not know why this fixes anything. At first, the defualt .js file association was with Windows, and switching that default association to IntelliJ fixed the problem. I want to assume that if I had changed the association to anything but Windows the execution would have worked flawlessly because it was trying to open the file as a text file rather than a .js file, but I cannot be too sure about it.

## Harddrive Problems

This is much less a Meteor problem than it is a personal laptop issue, but I first became aware of how <i>terrible</i> my laptop was actually holding up because of Meteor. I was able to install everything fine for my desktop computer I have at home despite it being roughly the same age as my laptop; a few years old, just with a lot less abuse and more maintenance. In any case, I've known for a while that my laptop's harddrive was getting slower to the point where it'd only do reads and writes at a few MB/s before reaching 100% disk use and begin stressing out with the fans. I figured that would be fine, considering programming doesn't require that much use unless I'm about to compile a huge project.<br>And guess what meteor is (so far)? A <i>small</i> project in the context of what I wrote, but a <i>huge</i> project because of the framework that builds everything. The result of this oversight was the unfortunate discovery that it would take me about 15 minutes to make a meteor project. In the mean time, it'd also render my laptop fairly unstable, even though physically it has good specs (i7-4810MQ, 16gb RAM, and a dedicated graphics card though that's not too relevant here). On the attempt to defrag- my first defrag in the 3 or 4 years that I've had this laptop- to hopefully mend my issues, I've encountered only more problems. The first, being that it would not defrag my laptop. It took almost zero seconds for a process that should take a while.

My solution was simple: go on Amazon, get a laptop using priority shipping, and pray it doesn't get delayed by Tuesday. And that's what I've done. This laptop has an SSD, a good processor though not as good as my old one, and again, a dedicated graphics card that has no relevance here (or yet).