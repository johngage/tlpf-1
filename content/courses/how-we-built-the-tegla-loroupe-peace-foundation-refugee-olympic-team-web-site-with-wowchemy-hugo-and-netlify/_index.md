---
title: How To Build the Tegla Loroupe Peace Foundation Refugee Olympic Team Web
  Site with Wowchemy, Hugo, and Netlify
date: 2021-02-09T03:54:39.616Z
subtitle: Overview of Major Components,  followed by Step By Step Guide
summary: >-
  **Tegla Loroupe Peace Foundation** website is now built with content created
  with **Hugo** components assembled in **Wowchemy** templates,  content stored
  on **Github,**  content published by **Netlify,** and the ***teglapeace.org***
  domain name purchased from **Cheapnames.**


  **For an overview of all of this, see *[Learn Enough Custom Domains To Be Dangerous](https://www.learnenough.com/custom-domains-tutorial/)***


  **Wowchemy** is a set of templates for creating and publishing a *static* website specialized for academic research and research groups. *Static* just means that the complete website is built each time you finish editing it, and all the website pages, now in their final HTML form, are published on the Internet, so that your website doesn't need any backend data base, or complicated backend programs to run, as Wordpress, or Wix, or other costly services require.


  The templates are built using **Hugo** components--pages, posts, books, biographies, events, images, galleries--software programs that convert various kinds of content into HTML pages ready to publish. **Hugo** establishes the framework for the website--the directories and subdirectories that contain text, images, bibliographic entries, biographical entries, and the software programs that control their appearance--Javascript programs, configuration files, CSS files, HTML files, scripting language programs.


  Interaction with these directory structures, templates, and software components can be very high-level, dealing only with editing text and uploading images, or can go deeper, allowing the fine-tuning of individual components.  


  This discussion begins at the high level, allowing immediate editing of an existing web site, and explores the expansion and modification of the web site (and troubleshooting any errors) by a series of examples.
draft: false
---
Here is a description by George Cushen of his project to build a framework for creating a static web site in a short [outline](https://georgecushen.com/create-your-website-with-hugo/) published in December, 2020.

Here's his promise: 

George Cushen:     In this guide, you’ll learn **how to create a free website for your online portfolio, resumé, or your team/organization using just your web browser**.

Read his [outline](https://georgecushen.com/create-your-website-with-hugo/) .  In what follows, I will expand on his statements, explaining what works, what is still under development, and what requires a deeper understanding of how the components interact.  I will point out the  pathways to build that deeper understanding through online tutorials on software development and developer tools.

I have used his description to set up the recreation of **teglapeacefoundation.org** as it existed in mid-2019.  I recreated it from snapshots taken by the Webarchive Foundation. 

### Overall structure of the TLPF website

##### Where is the content?

The master copy of the content is held in the cloud, in a massive site called **Github.** Millions of developers keep their code and their content in **repositories** in **Github.**  Microsoft purchased **Github** in 2018, as a service to software developers. There are several rivals, but all use the same basic tools, named **Git,** to keep track of changing content.  These tools are called **Version Control** tools.  They allow software developers to keep track of every change in the text of what they write, with the power to revert to older versions if newer versions prove to contain mistakes. These **Git** tools allow teams of writers to work on a common text, editing together, discussing changes, and deciding what final text to adopt.

**Repositories** for personal use at **Github** are free, and for the moment, **TLPF** files are in a repository owned by me.  I will create a **TLPF** repository owned by **TLPF.**



##### How can I edit the content?  

The content is pulled from **Github** by the web publishing site named **Netlify.  Netlify** has an on-line editor, named **Netlify Content Management System,**  or **NetlifyCMS**, which allows you to edit all the text, upload images, change details of what is published for biographies, or posts, or blog entries, or events, and, generally, manage all of the site content.  This is where most of the day-to-day work will take place.  As you change the content on **NetlifyCMS**, it automatically updates the main repository at **Github**, so everything remains synchronized. 

Editing in **NetlifyCMS** is simple---what you see is what you get. There are a few simple visual commands, almost exactly like editors used for email.

Occasionally, you will want to modify something that **Netlify CMS** does not let you change. There is a separate editor at **Github** that allows you to change almost everything.  Here, however, editing is more complicated. 

First, you need to understand the arrangement of directories that contain the content. Most content is in the directory ***content.*** Text files for posts or news entries are in the directory ***content/posts.*** Text files for biographies of people are in the directory ***content/authors.*** Text files for events are in ***content/events.***

Everything is arranged in directory and file hierarchies, as in any Unix system. You must be familiar with how that works.  There are two areas to be comfortable with: the **Command LIne**, and the **Development Environment.** For an overview, see *[Learn Enough Command Line To Be Dangerous](https://www.learnenough.com/command-line-tutorial/basics).* And The full course costs money--I'll try to get us scholarships--but you can read enough to get what you need.