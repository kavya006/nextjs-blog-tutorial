---
title: Two forms of Pre-Rendering in Next.js 
date: '2021-07-28'
---

Next.js offers two kinds of pre-rendering techniques: 

- **Static Generation**: Generates the html during the *build* time and is *reused* for every *request*.
- **Server side rendering**: Generates the html on the server instead of the client side per each *request*. 

Also Next.js lets us chose which kind of pre-rendering you want to use per component. You can create a hybrid web page with both static generation and server side rendering for a few pages in your app. 
