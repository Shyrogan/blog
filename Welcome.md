---
title: Welcome to my blog!
description: Why? What? How does it works?
date: 29/03/2023
---

# Welcome

Welcome to my blog, this is my first time writing a blog post.  
This place will allow me to express my thoughts, experiences and projects to everyone. I know this will peak the
interest of many people but the goal is to have a trace of what I've done and what I work on.  

## About this blog

This blog was one of the project ideas I had for a while: write blog using SolidJS that fetches data from GitHub on
a repository used to store articles. That's a lot of words right..? Let's quickly understand what's going on
when you navigate on this blog.  

When you open the main page, your browser will fetch the data about my [blog repository](https://github.com/Shyrogan/blog).  
*(You can check out what's the response of GitHub's API [here](https://api.github.com/repos/Shyrogan/blog/contents/))*.  

After that, the content of every `.md` file is also fetched and the metadata about each article is parsed using [yaml-front-matter](https://www.npmjs.com/package/yaml-front-matter).  

When you click on some article, we only fetch the content of that specific article and display it using [marked](https://marked.js.org/).

## SolidJS is great

I have recently started working with SolidJS and I absolutely love it. It's fast, intuitive and provides you with almost everything you need.
My only regret is that I didn't manage to find a library to animate some of the components of my UI.  
I also used it for the application that will manage [ENSCM](https://www.enscm.fr/fr/) VR projects.  

If you are used to React, you will absolutely love SolidJS.

## Conclusion

I hope I'll be able to fill and pursue this project soon.  


Cya soon!
