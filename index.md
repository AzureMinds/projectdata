---
layout: home
title: "Welcome to Project Data"
permalink: /
---

Welcome to my blog on all things Product Management and Data. Here you will find musings (hopefully with some slight humour) and projects (both completed and upcoming).

Currently I work as a Technical Product Manager at Risilience, a startup working to quantify and strategise climate related risks for clients. Historically, I worked on data related problems (both the sexy stuff and the plumbing) across various startups and consulting practices.

## About Me {#about}

<div class="about">
  <img class="avatar" src="assets/IMG_3319.jpg" alt="Patrick Stewart">
  <div class="bio">
    <p>Hello! I'm Patrick Stewart, a data science and machine learning enthusiast. I love exploring the intersections of data science, machine learning, and natural language processing.</p>
    <p>Currently I work as a Technical Product Manager at Risilience, a startup working to quantify and strategise climate related risks for clients.</p>
    <div class="social-links">
      <a href="/assets/Patrick_Stewart_CV_Final.pdf" aria-label="CV" title="CV">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path><polyline points="14 2 14 8 20 8"></polyline></svg>
      </a>
      <a href="https://twitter.com/Patrick74925271" aria-label="Twitter" title="Twitter" target="_blank" rel="noopener">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M23 3a10.9 10.9 0 0 1-3.14 1.53A4.48 4.48 0 0 0 12 7v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83"></path></svg>
      </a>
      <a href="https://www.linkedin.com/in/patrick-stewart-832bb276/" aria-label="LinkedIn" title="LinkedIn" target="_blank" rel="noopener">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
      </a>
      <a href="https://medium.com/@patrick.stewart" aria-label="Medium" title="Medium" target="_blank" rel="noopener">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="currentColor"><circle cx="6" cy="12" r="4"></circle><circle cx="14" cy="12" r="3"></circle><circle cx="20" cy="12" r="2"></circle></svg>
      </a>
      <a href="https://github.com/AzureMinds" aria-label="GitHub" title="GitHub" target="_blank" rel="noopener">
        <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2C6.48 2 2 6.58 2 12.26c0 4.52 2.87 8.35 6.84 9.7.5.09.68-.22.68-.49 0-.24-.01-.87-.01-1.71-2.78.62-3.37-1.37-3.37-1.37-.45-1.18-1.11-1.5-1.11-1.5-.91-.64.07-.63.07-.63 1 .07 1.53 1.05 1.53 1.05.9 1.57 2.36 1.12 2.94.86.09-.67.35-1.12.64-1.37-2.22-.26-4.56-1.14-4.56-5.07 0-1.12.39-2.03 1.03-2.75-.1-.26-.45-1.3.1-2.71 0 0 .84-.27 2.75 1.05A9.3 9.3 0 0 1 12 6.75a9.3 9.3 0 0 1 2.49.34c1.91-1.32 2.75-1.05 2.75-1.05.55 1.41.2 2.45.1 2.71.64.72 1.03 1.63 1.03 2.75 0 3.94-2.34 4.81-4.57 5.07.36.32.68.95.68 1.92 0 1.39-.01 2.5-.01 2.84 0 .27.18.59.69.49A10 10 0 0 0 22 12.26C22 6.58 17.52 2 12 2z"></path></svg>
      </a>
    </div>
  </div>
</div>

## Recent Posts

<div class="posts">
  {% for post in site.posts limit:5 %}
    <article class="post-preview">
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <div class="post-meta">
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time>
      </div>
      <div class="post-excerpt">
        {{ post.excerpt | strip_html | truncatewords: 30 }}
      </div>
      <a href="{{ post.url }}" class="read-more">Read more →</a>
    </article>
  {% endfor %}
</div>

<div class="view-all-posts">
  <a href="/blog/" class="btn">View All Posts</a>
</div>

