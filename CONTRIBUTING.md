# Contributing to TokenChicken.com

[Many people](https://github.com/dblock/tokenchicken.com/graphs/contributors) have received chickens. Well, not really. But they had fun with a chicken.

You can contribute a story by sending a photo of you and a chicken over email to [dblock+tokenchicken@dblock.org](mailto:dblock+tokenchicken@dblock.org) or by [submitting a pull request](https://github.com/dblock/tokenchicken.com/pulls) as per instructions below (easier for us, geekier for you).

In the examples below, substitute your Github username for `contributor` in URLs.

### Fork the Project

Fork the [project on Github](https://github.com/dblock/tokenchicken.com) and check out your copy.

```
git clone https://github.com/contributor/tokenchicken.com.git
cd tokenchicken.com
git remote add upstream https://github.com/dblock/tokenchicken.com.git
```

## Contribute a Chicken

### Create a Topic Branch

Make sure your fork is up-to-date and create a topic branch for your chicken.

```
git checkout master
git pull upstream master
git checkout -b my-chicken-story
```

### Create a Post

Create a .md file in [_posts](_posts) with any text editor, eg. [2018-03-20-olive-crypto-entrepreneur.md](_posts/2018/2018-03-20-olive-crypto-entrepreneur.md). Note that we name the file with a date to keep things clean. Copy the contents from another post and edit it.

```
---
layout: post
title: "Olive Allen"
date: "2018-03-20"
---
_"I got my chicken as soon as I sent the coins!"_

[oliveallen.com](https://oliveallen.com), [@IamOliveAllen](https://twitter.com/IamOliveAllen)
```

### Add a Photo of You with a Chicken

Any photo works as long as you're in it with a chicken. Place the photo in [img/posts](img/posts), eg. [img/posts/2018/2018-03-20-olive-crypto-entrepreneur.jpg](/img/posts/2018/2018-03-20-olive-crypto-entrepreneur.jpg).

### Commit Changes

Make sure git knows your name and email address:

```
git config --global user.name "Your Name"
git config --global user.email "contributor@example.com"
```

Writing good commit logs is important. A commit log should describe what changed and why.

```
git add ...
git commit -m "I received a chicken."
```

### Push

```
git push origin my-chicken-story
```

### Make a Pull Request

Go to https://github.com/contributor/tokenchicken.com and select your feature branch. Click the 'Pull Request' button and fill out the form. Pull requests are usually reviewed within a few days.

## Thank You

Please don't forget to actually send some coin or [donate the regular way here](https://www.runwithtfk.org/Profile/PublicPage/61018).

Please do know that we really appreciate and value your time and work. We love you, really.
