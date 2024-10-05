---
layout: post
title:  "Building a personal website using Jekyll"
date:   2024-09-04 16:14:10 +0100
categories: [blog, personal]
tags: [jekyll]
---

So, after much procrastination, I have finally put together a personal website (of sorts) to keep better track of blog posts, personal projects and general ramblings. In the interest of clarity and for those of you interested, this post will hopefully illustrate how I put this together as well as touching on the key components. Note: If you are reading this on Medium then the links for my website and associated Github page are https://azureminds.github.io/ and https://github.com/AzureMinds/azureminds.github.io .

<img src="assets/andrew-neel-ute2XAFQU2I-unsplash.jpg" alt="My Picture" width="300px"> 

Firstly, you may have noticed this site is hosted using Github pages. Github pages offers a way to host a static website (like yours truly) without paying for/setting up hosting. On top of this, given my lack of web development expertise and impatience on getting something together, I have built this website using Jekyll which is compatible with Github Pages. 

Jekyll is a Ruby package that transforms plain text files and written in markdown or other markup languages like HTML and processes it to create a static website. While some people think that the themes are what makes jekyll so attractive, I think in the chatgpt era where themes are quite easy to make, what makes Jekyll standout is it's ability to offer easy content management. By this I mean all content I write is in markdown, which is converted to static HTML, with no database type queries resulting in fast loading times. However, to summarise it's perfect for people who don't want to reinvent the wheel, building a website similar to this. For those of you looking to get started with Jekyll, I would recommend this https://jekyllrb.com/docs/installation/ if you are looking to install and setup Jekyll for the first time.

Ok, so now you understand Jekyll and Github pages, I am going to outline to you how this website is setout (and yes it may change).

The _config.yml file notes the configuration settings and options for my site. If you inspect the file, you will see I've included basic plugins, title, personal details, and usernames that could be useful. You can import Jekyll themes, which is often highly desirable

The index.md file typically serves as the main homepage of a jekyll site. When it comes to styling markdown files, I could bore you to death with the optimum approach to this but instead if interested then this link https://docs.gruntwork.io/guides/style/markdown-style-guide/ should help.

In Jekyll, layouts are fundamental to structuring your website. They are stored in the _layouts directory and are written in HTML with embedded Liquid templating tags. The website is structured by three HTML layout formats, default, post and home.

The default.html layout serves as the foundation for all pages on the site. The setup is fairly standard with the exception of javascript functionality and CSS for a light and dark mode toggle. The home.html brings in the default layouts as well as the content for the home page and the content for the most recent five blog posts. Meanwhile post.html defines the layout for an individual blog post in Jekyll. 


