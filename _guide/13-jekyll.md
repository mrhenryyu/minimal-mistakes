---
layout: single
author_profile: true
permalink: /guide/website/3
title: "How to write a Jekyll article"

header:
    overlay_image: /images/guide/lake.jpg

    
---


# How to write a Blog Post using Kramdown 

## Blog Writing **101**

If you are reading this, you are probably interested in learning how to write a web post using [Kramdown](http://kramdown.gettalong.org/quickref.html#inline-attributes). This guide is going to teach you the beginner skills for everyday blog posts, however if you want to learn more complex concepts, there are other guide linked at the *end of this article*{: style="color: red"}. 


To learn how to get your own website hosted by Github Pages, check out this [guide](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/). 

## Table of Contents 
In this guide, we will go through 

1. Headers + **fonts**  
2. Lists (ordered and unordered)
3. [links](https://jekyllrb.com/docs/github-pages/)
4. Photos 
5. `Code Snippits`


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

~~~
1. One 
    1. A
    2. B
    3. C
2. Two
3. Three
~~~

### Unordered Lists 
* Do you like 
* green eggs and ham. 
* I do not like them 
* Sam - I - am 

~~~
* Do you like 
* green eggs and ham. 
* I do not like them 
* Sam - I - am 
~~~

Within your lists, you can also add different things, such as `code blocks`, *italics* and [links](http://henryyu.me/guide/)


## 3. Links and Quotes

Jekyll has made it very easy to insert links into your blog posts. For example: here is a [link](http://henryyu.me/) that links to the homepage. 

`For example: here is a [link](http://henryyu.me/) that links to the homepage. `

Block Quotes can be inserted using the `>` key 

> I am a quote! 

## 4. Photos 

Photos can be added using `![image](/images/image.jpg)` 

For example, 

![image](/images/Henry.jpg)

![image-left](/images/Henry.jpg){: .align-left} 
You can also orient your images however you like, for example, it can align to the left or right of your text. The The rest of this text is to fill up the rest of the space or else your the code will continue to wrap the text until the end of the image. Do not use this with code blocks, as the code block will go over the image. `Code snippits are okay` as well as other inline text markups. **For more image tricks, you can read this** [guide](https://mmistakes.github.io/minimal-mistakes/docs/utility-classes/).

~~~ ruby
    ![image](/images/Henry.jpg)
    ![image-left](/images/Henry.jpg){: .align-left} 
~~~

## 5. Code Blocks and Snippits 

Code snippits and code blocks are easy ways display code or highlight an important point on your website. 

#### Code Snippit

~~~ ruby 
    `This is a code snippit`
~~~

#### This is a code block

~~~ ruby
    ~~~ ruby 
        `This is a code snippit`
    ~~~
~~~
    

Thank you for reading this article. Please **comment** if you have any questions or suggests for future guides. At some point in the future, I will be covering more advanced topics such as **side-bars, table of contents, text colors and site customization**. 
