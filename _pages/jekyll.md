---
layout: single
permalink: /guide/
author_profile: true
title: "How to write a Jekyll article"
date: 2016-09-24 12:00:00 -0400
categories: [Miscellaneous]
tags: [Jekyll, Guide]
comments: true
header:
    overlay_image: bamboo.jpg  

    
---

# How to write a Blog Post using Kramdown 

## Blog Writing **101**

If you are reading this, you are probably interested in learning how to write a web post using [Kramdown](http://kramdown.gettalong.org/quickref.html#inline-attributes). This guide is going to teach you the beginner skills for everyday blog posts, however if you want to learn more complex concepts, there are other guide linked at the end of this article. 

To learn how to get your own website hosted by Github Pages, check out this [guide](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/). 

## Table of Contents 
In this guide, we will go through 

1. Headers + **fonts**  
2. Lists (ordered and unordered)
3. [links](https://jekyllrb.com/docs/github-pages/)
4. Photos 
5. `Code Snippits`
6. Authors, Tags, Sidebar, Miscellaneous 

## 1. Headers 
Headers can be added into the article by using `# ` before a header. Headers can have different sizes.  

e.g. 

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

    # Header 1 
    ## Header 2 
    ### Header 3 
    #### Header 4 
    ##### Header 5 
    ###### Header 6
    
## 2. Lists (ordered and unordered)

### Ordered Lists 

1. One 
    1. A
    2. B
    3. C
2. Two
3. Three

### Unordered Lists 
* Do you like 
* green eggs and ham. 
* I do not like them 
* Sam - I - am 

Within your lists, you can also add different things, such as `code blocks`, *italics* and [links](http://henryyu.me/guide/)


## 3. Links and Quotes

Jekyll has made it very easy to insert links into your blog posts. For example: here is a [link](http://henryyu.me/) that links to the homepage. 

`For example: here is a [link](http://henryyu.me/) that links to the homepage. `

Block Quotes can be inserted using the `>` key 

> I am a quote! 



~~~ ruby
def what?
  42
end
~~~


Links are the easiest to show. Here is a sample [link](https://www.google.ca) that links to Google. 
They are easy to bring `inline` to your text. 
4. How to add photos 
5. How to add code to your Jekyll Article 

There are two ways to have your code in a Kramdown blog post, the first is an `inline code snippit` 
This be done by using 
    `inline code snippit` 
    
6. Tags, authors, sidebar etc. 

Tags, Authors and Sidebars are all created in your FAML (front matter) 
They have corresponding values to each tag 



