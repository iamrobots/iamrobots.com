---
title: "Init Commit"
date: 2022-09-18T10:41:21-07:00
tags:
  - tasks
description: "I am not a writer but lets write something today."
draft: true
---

First commit.

I am not a writer but lets write something today.

# So what's the point of this?

I originally created iamrobots.com because I wanted some practical knowledge developing something while I looked for a job after college. I didn't really have a direction on what to learn nor the kinds of jobs I wanted so I created this site.

My original about page said

> "This site is my personal testing ground for web technologies..."

and this is true today. I think this site is a place where I can go to when I just need to make and deploy something. Maybe I just feel like shelling into a linux server so I can do some apt commands. Or maybe I need a vpn to watch movies in a foreign country. iamrobots is just that. A site where I can just do something.

So in the name of boredom and experimentation lets do something. I haven't been spending enough time actually deploying personal projects recently. So lets upgrade iamrobots and learn some stuff on the way.

## Why Hugo?

I appreciate its simplicity. I'm finding when choosing tools its best to choose something that is simple, is well documented, and has a large active user base. These attributes make it so that you spend your time accomplishing your objectives instead of fighting your tools or parsing documentation.

> Lesson: When creating applications or APIs keep them simple, well documented, and foster an active user base.

## Why DigitalOcean?

Simplicity and familiarity. This site has been hosted on DigitalOcean since its inception. I've tried using other hosting providers but I always keep coming back to DigitalOcean. DigitalOcean like Hugo has a simple user interface, a significant library of documentation and a large user base.

> Lesson: Avoid complexity as much as possible until you can't anymore.

## Tasks

- Update site from using Droplet to using the free DigitalOcean App Platform. [How To Build and Deploy a Hugo Site to DigitalOcean App Platform](https://www.digitalocean.com/community/tutorials/how-to-build-and-deploy-a-hugo-site-to-digitalocean-app-platform)
- Implement custom layout for Hugo site. [Hugo Templates](https://gohugo.io/templates/)

### Commands that I may want to remember

```sh
hugo new site iamrobots.com #creates new site
hugo new about/index.md #creates new page
hugo new theme iamrobots #creates new theme
```
