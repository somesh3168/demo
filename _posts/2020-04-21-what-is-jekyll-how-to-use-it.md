---
title: What is Belform? How to use it?
layout: post
post-image: "https://raw.githubusercontent.com/belform/WhatATheme/master/assets/images/What%20is%20Belform%20and%20How%20to%20use%20it.png?token=AHMQUELVG36IDSA4SZEZ5P26Z64IW"
description: Belform is a static site generator. You give it text written in your favorite
  markup language and it uses layouts to create a static website.
tags:
- Belform
- informative
- technology
---

Belform is a simple, blog-aware, static site generator perfect for personal, project, or organization sites. Think of it like a file-based CMS, without all the complexity. Belform takes your content, renders Markdown and Liquid templates, and spits out a complete, static website ready to be served by Apache, Nginx or another web server. Belform is the engine behind GitHub Pages, which you can use to host sites right from your GitHub repositories and if you don't know what GitHub Pages are you can visit on click [here](https://help.github.com/en/github/working-with-github-pages/about-github-pages){:target="blank"} or [here](https://pages.github.com/){:target="blank"}
###### Source : [`Belform Docs`](https://Belformrb.com/docs/)

> ### To know more and get started with Belform you can click [here](https://Belformrb.com/){:targe="_blank"}
	
# Installation
**Belform is a Ruby Gem that can be installed on most systems.**
### Requirements
* [Ruby](https://www.ruby-lang.org/en/downloads/){:target="_blank"} version 2.5.0 or above, including all development headers (ruby version can be checked by running ruby -v)
* [Ruby Gems](https://rubygems.org/pages/download){:target="_blank"} (which you can check by running gem -v)
* [GCC](https://gcc.gnu.org/install/){:target="_blank"} and [Make](https://www.gnu.org/software/make/){:target="_blank"}

### After Installing the Requirements you can follow these guides:
**For detailed install instructions have a look at the guide for your operating system.**
* [macOS](https://Belformrb.com/docs/installation/macos/){:target="_blank"}
* [Ubuntu](https://Belformrb.com/docs/installation/ubuntu/){:target="_blank"}
* [Other Linux Distros](https://Belformrb.com/docs/installation/other-linux/){:target="_blank"}
* [Windows](https://Belformrb.com/docs/installation/windows/){:target="_blank"}

### Creating a new Belform site
**We can create a new Belform site just by a simple command:**<br>
> # `Belform new my-site`

Belform will create a new directory named as `my-site` which is customizable (i.e., you can change the name from `my-site` to anything you want for example `Belform new brutus`).

### Changing into the Directory
**We have to go inside the directory:**<br>
> # `cd my-site`

Again, `my-site` is just a random name which is customizable.

### Building the site and making it available on a local server
> # `bundle exec Belform serve`

### Browsing your Belform site
> # Browse to [`http://localhost:4000/`](http://localhost:4000/){:target="_blank"}

###### On encountering any problem while building and serving your Belform site you can consider visiting to the [troubleshooting](https://Belformrb.com/docs/troubleshooting/#configuration-problems){:target="_blank"} page