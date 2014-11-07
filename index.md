---
layout: default
permalink: /
---

## **A Tech Primer**

### **Example Questions That I'll Answer**

Is Java comparable to Ruby, or Ruby on Rails?

How is Ruby different from Rails?

Do I need JavaScript, PHP or AJAX if I'm using Rails or Java?

Do I use Javascript, PHP and AJAX with Rails or Java, or are they alternatives?

How does Meteor.js fit in?

How does Node.js fit in? And Express.js?

If I learn Meteor.js or Rails, do I still need to know HTML & CSS?

Is Java for frontend?

Is JavaScript for frontend?

What is the best language to learn?

What is the best framework to learn?

What should I learn if I want to build webapps?

What should I learn if I want to build mobile web apps?

### **The Landscape**

Firstly, let me put some things into categories:

Programming Languages

  * Java
  * Ruby
  * JavaScript
  * PHP

Web Development Frameworks

  * Ruby on Rails (or just 'Rails')
  * Meteor.js
  * Express.js

Markup Languages

  * HTML
  * CSS

Think of the difference between a programming language and a markup language like so:

  * A markup language is more similar to description. A markup language may say that this is a header, that this should be the color blue, and that this should be a numbered list. It doesn't do things like: when I click this header, do something. For that, we would use a programming language.
  * A programming language can use logic to respond to actions.

Now, I'm going to explain by example.

Example #1: Reddit.com

  * We can say a few things about reddit.
  * It has a page that is designed in a certain way, with pictures and links in certain places
  * It has user accounts and comments
  * We could build a non-interactive version of reddit with just HTML and CSS. HTML defines what items the page has - i.e. that there are X number of links, and that we have images, etc, and then CSS defines where things are placed on the page and what they look like.
  * This page could look like reddit, but it wouldn't be interactive like reddit is.
  * It would be a static website - and not an interactive web application.
  * We could add a few "front-end" interactive features, like making the color of the upvote arrow change after we clicked it, using JavaScript. JavaScript is a programming language, and is commonly used to make visually interactive "front-end" features like this.
  * If we wanted to make this into a fully interactive web application, we could use pure Ruby, or JavaScript, or PHP, etc, to build what's called the 'backend'. If we were just using a programming language, without the help of a web development framework, we would have to write things to handle how user accounts work, to handle how our web server sends different pages to the user, etc. It turns out that many of these are common tasks that most web applications require.
  * Thus, we have web frameworks. Web frameworks build on top of a specific programming language, and handle much of the common pieces of building a web application. They might handle things like making it easy to split the page up into multiple pieces (e.g. the header bar of reddit might be the same on any page, so we write it separately, and we write the links in separately and include them in the page, so that we don't have to write 1000s of versions of the website - instead we create the small pieces and then piece them together).
  * For example, we could use the ruby on rails web framework to write our reddit application. This would mean that we are using both ruby, and ruby on rails. Ruby is the programming language that ruby on rails is written in. Ruby on rails was created when a company built a web application using ruby, before rails existed. They saw how many things other web developers would have to build themselves in exactly the same way, so they took out the parts that weren't unique to their application and made it available as ruby on rails.

Is Java comparable to Ruby, or Ruby on Rails?

  * Java is comparable to Ruby. They are both programming languages.

How is Ruby different from Rails?

  * Rails is a framework that is written in the ruby programming language.

Do I need JavaScript, PHP or AJAX if I'm using Rails or Java?

  * If you want to make the frontend interactive, you will still need JavaScript even if you are using Rails, or if you are using some Java web framework and Java.
  * AJAX is a technique for using JavaScript, so that we can make changes to the page without having to reload the webpage. For example, sites that have never ending scrolls are a good example of using AJAX. So yes, we may want to use AJAX in addition to Rails.
  * PHP is an alternative to using Rails & Ruby. We can write a web application in pure PHP, or we can use a PHP web application framework like Symfony or Zend.

Do I use Javascript, PHP and AJAX with Rails or Java, or are they alternatives?

  * Rails, Java, PHP and JavaScript are alternatives
  * JavaScript may be used in addition to Rails or Java or PHP, because it is the standard language for adding in front-end interactivity as mentioned in the reddit example
  * AJAX is a technique for using JavaScript

How does Meteor.js fit in?

  * Meteor.js is a JavaScript web framework.
  * If you use Meteor instead of Rails, then that would mean that you will write your web application using primarily JavaScript, rather than Ruby.
  * However, you would still need to write HTML and CSS for the actual content of the website - it would just be the "back-end features" that your choice of Meteor or Rails impacts

How does Node.js fit in? And Express.js?

  * Node.js is a JavaScript web server. Express.js is a JavaScript web framework that uses the Node.js web server.
  * Meteor.js also utilizes aspects of Node.js for it's server
  * Ruby on Rails can be used with multiple different servers - though you don't need to change any settings, as it comes with one that works by default. However, you might want to! I usually use the Puma web server with Rails - though for small web applications it doesn't make much of a difference.

If I learn Meteor.js or Rails, do I still need to know HTML & CSS?

  * Yep!

Is Java for frontend?

  * No - frontend is HTML, CSS, and JavaScript

Is JavaScript for frontend?

  * Yes - for front-end interactivity
  * JavaScript is also a general purpose programming language, and with things like Express.js or Meteor.js can be used for the backend of web applications too

What is the best language to learn?

What is the best framework to learn?

What should I learn if I want to build webapps?

What should I learn if I want to build mobile web apps?

### **What should I learn?**

Want to build websites like Reddit?

  * Learn HTML, CSS, and a programming language and web framework
  * The best way to learn is to pick a really small project to do (e.g. a personal homepage), and then start trying to build it, and Google search every problem you encounter
  * Repeat with more ambitious projects each time
  * I do not suggest bothering with studying HTML and CSS in the beginning - honestly, just dive right in and build things. Copy HTML and CSS from other websites, even if you don't understand it. If you keep building projects, more and more will make sense over time.

What programming language and framework should I learn?

  * For beginners, I would suggest Meteor.js and JavaScript (remember, you'll also need to know basic HTML/CSS)
  * Other popular alternatives would be: Python & Django, or even more popular, Ruby and Ruby on Rails. PHP, or Java, or other languages are losing out over time to frameworks like Rails and Meteor, so I'd suggest those - *however* you can absolutely still build a web application in PHP! I just wouldn't want to ;-)

Want to build apps like Uber?

  * Learn Objective-C or Swift for iOS apps or Java for Android apps
  * Alternatively, use one of the many tools that allow you to write iOS/Android apps in other languages. For example, [RubyMotion](http://www.rubymotion.com/) for ruby.

Want to build simple websites like atechprimer.com?

  * Learn HTML and CSS
  * The steps you could take to build this site:
    * Download [Jekyll](http://jekyllrb.com/)
      * This may require first setting up ruby - which you can Google :-)
    * Run jekyll new techprimer
    * Modify the default CSS slightly, change the fonts and some colors and such
    * Modify the default HTML templates slightly
    * Modify the Jekyll site config, to set the site title, description, and things like that
    * Set up a git repo and push the repo to github (Google how to do that)
    * Buy a domain on Namecheap.com
    * Set up a custom domain on github pages (Google how to do that)
    * Done!
