---
layout: default
---

## Blog post 1

Blog Week 08/31/2019
The inaugural class meeting for CIT 480/L was 08/24/2019. The professor gave an overview of the tools we will be learning and utilizing this semester. I am excited to develop new skills that will serve me now and in my future endeavors. I am particularly keen to learn more about Docker as PaaS and Cloud Computing in general have become standard for business. 
The first week’s class assignments were to complete Lab A and to create a blog. I first dove in to creating my blog as I thought this would be the more difficult task for this week. I selected Jekyll as my static site generator. A static site generator allows for the building of static HTML webpages using templates. They improve performance and simplify server side setup. To guide me I used the tutorial “How to Start a Jekyll Blog on GitHub Pages for Free” created by Anna Monus (https://onextrapixel.com/start-jekyll-blog-github-pages-free/). I already had a GitHub account but decided to switch my username to my actual name to make the blog match the standard I saw the professor use and to make it more readily identifiable. Next, I created a new repository for the online version of the blog. Again, when naming the new repository, I followed GitHub standards. The local copy of the site will be on my computer. I needed Jekyll, a Ruby gem, to be on my computer and installing it was the next step. I already had Ruby and RubyGems up and running on my computer, so went straight to installing Jekyll by using the command:
-	sudo gem install jekyll  
To determine if Jekyll was functioning correctly, I issued the command:
-	jekyll -v
The version number was returned so I knew that all was well. 
Next, I needed to actually create the Jekyll site. In the interest of keeping my blog streamlined and minimal, I decided to use an existing Jekyll theme that I cloned from GitHub called slate. Of note, to ensure the theme change worked I changed the the \_config.yml file, added the theme as a Gem to the Gemfile, and installed the theme using Bundler. A useful command I learned during the site creation process was:
-	jekyll serve –watch
It can be used to access the local copy of my blog on the localhost:4000 URL.
To add blog posts, you create a new file in the \_posts folder. The names of the blog posts use the following naming convention:
-	year-month-date-{slug}.md
Once I was done writing my blog posts, I pushed my new site live. 
The week was fun and a bit challenging as I had never before created a Jekyll website on GitHub. I look forward to the coming weeks tasks. 


[back](./)