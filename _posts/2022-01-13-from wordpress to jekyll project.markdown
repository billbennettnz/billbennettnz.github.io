---
layout: post
title:  "From WordPress to Jekyll Project"
slug: "wordpress-jekyll"
date:   2022-01-12 19:55:47 +1300
categories: wordpress
---

Wordpress has moved away from its roots as a simple blog tool. There's nothing wrong with that, it's a business and it needs to stay in touch with its market. 

Yet those changes don't suit my needs. In particular, Gutenberg is a problem. 

Which is why I'm looking for an alternative way of publishing [my blog](https://billbennett.co.nz). 


### Jekyll could be the answer
Jekyll looks like a plausible candidate. This project or something like it could one day replace my Wordpress site.

Before that happens there are a number of features and services that work on Wordpress that I'd like to carry across to the new site. 

This post explores those features and what I may need to do with Jekyll. I've made it public because it could help others attempting a similar move. 

It might equally serve to let others know that moving away from Wordpress is more trouble than it is worth. 


### Must have features
*These are not necessarily in any order*

1. Ability to notify subscribers by email when there is a new post. I produce a weekly newsletter. Ideally I could send this out to a different subscriber list. 
2. So, the site needs to have a mechanism for multiple email notification feeds. 
2. A simple automated back-up mechanism. *I don't see this being a problem*.
3. Categories and tags. Ideally I'd like to have paginated category and tag index pages. *This looks trivial*.
4. A simple comments system. I'd prefer not to use a service like Disqus. It would best if there was built-in comment spam filtering. 
5. Meaningful site stats. Preferably independent of Google or other third parties. It could be possible to extract this from log files. So that means a decent log system.
6. RSS feed - *This looks trivial*.
7. Redirection - preferably like the Wordpress redirction plug-in. Ideally I'd like to export the redirections from the old site to the new site. 


### Support for Indieweb features
More to write here. The good news is there is a Jekyll section on the Indieweb wiki. 

Indieauth, Syndication links, WebSub and Web Mentions are key here. 

Indieweb share and like buttons. 


### Would like to see the following...
2. Previous and next post links. Preferably these would be organised by date, although I can this may be difficult if posts are stored in category folders.
3. A nice way to create, manage and show tables.
4. Decent site search. 
5. Automatic posting on new posts to Twitter. 
6. Related posts would be great, but is not essential.
7. Not sure if an XML sitemap is necessary. *More research needed*.
8. Ability to post stories remotely and have them publish automatically. 
9. Excerpts - *not sure if this is necessary*
10. Force permalinks to lower case characters


### Things to explore	
- Whether I can embed images and captions with *alt text* in my Markdown editor.
- Adding in the PressPatron banner that is at the top of pages on my WordPress site.
- Change theme to use only system fonts.


### Moved to done
**Breadcrumbs**  
Used the method described on this page:

https://jekyllcodex.org/without-plugin/breadcrumbs/#

**Google Search Console**  
Verifyed site on GSC. Not essential, but useful for spotting problems when the site is bigger. 

**RSS feed**  
Turns out this was built-in. 

**Permalinks**
Have set up permalinks as: 

site/category/post name

### Is there anything I missed?
Until I've got a comment system working you'll have to tell me by email ;). [bill@billbennett.co.nz](mailto:bill@billbennett.co.nz)





