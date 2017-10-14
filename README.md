# jNegative
a white on black Jekyll theme

Hi - I'm Paul Mostowyj. It's pronounced *most-o-vee*, but you can call me Paul and I created the jNegative theme for Jekyll web sites. It's a theme inspired by the look and feel of the [Zen Habits](https://zenhabits.net) web site, which strips away all of the bells and whistles to leave what's essential - the content.

## jNegative Features
jNegative includes the following features:
- minimalist design
- footer navigation
- email subscription
- latest post featured on the home page
- posts archived by month
- author name and url tags
- responsive design

## jNegative Screenshot
![jNegative Screenshot](./assets/img/jnegative-screenshot.png)

## jNegative Demo
You can see and explore a live demo of the jNegative theme at [https://paulmostowyj.github.io/jnegative](https://paulmostowyj.github.io/jnegative).

## jNegative Installation
To install the jNegative theme to use on your GitHub hosted project complete the following instructions:
01. Click the 'Fork' button in the top right corner of this repository
02. Wait for this repository to be copied to your GitHub account
03. Click the 'Settings' tab, which is the last tab on the navigation bar towards the top of the screen
04. Click the 'Repository Name' text box and enter the name of the site you want to use. If you want this to be your main web site on GutHub then it needs to be named `username.github.io` replacing `username` with your user name
05. When you're done click the 'Rename' button
06. Click the 'Settings' tab again
07. Scroll down the page until you see the 'GitHub Pages' section
08. Click the 'Source' button and select  the 'master branch' option
09. Click the 'Save' button next to it

## jNegative Customisation
By default jNegative includes dummy data that describes the theme and / or links to me as the author, which can all be customised in the _config.yml.

### Site Title and Tag Line
The site title and tag_line tags are used by the theme to create the header and in the browser tab. The 2 tags are separated by a | and the title is created as a homepage link in the header.

### Site Description and Keywords
The site description and keywords are not seen anywhere in the theme because they are used in the `<head>` section of the HTML template. Both will contribute to search engine optimisation and the description will be displayed by search engines when shown as a result.

### Site Url
If you have installed the jNegative theme to your primary `username.github.io` repository then this tag can be deleted from the _config.yml because the Jekyll default setting will apply the correct url. If you have installed it anywhere else then you will need to enter the correct url in the _config.yml because this is used to set the home page link and in defining the path to all other documents used by the theme.

### Author Name and Url
This theme is designed for a single author, which is why the site author and author_url tags are used to create the post by-line. The default shows I have linked the author back to my own personal web page, which you can replace with your personal web page, back to this web site as another home page link, a social media account such as Twitter or anything else you would like to use.

### Email Subscription
At the bottom of every post is a link inviting readers to subscribe to your blog via email. The email_suscribe tag is used to create this link and you should replace it with the url to your email subscription sign-up page.

## jNegative Content
jNegative puts the focus on the content and contains default pages and posts to demonstrate its capabilities.

### Pages
jNegative supports 4 pages: home, about, archive and contact. The home page and archive page are setup and ready to use without any adjustments. You should replace the content of the about page and the contact page.

Additional pages can be added using the `.html` or the `.md` file types, but these pages will not automatically be included in the footer navigation. When creating new pages include the following front matter:
```
---
layout: page
title: your page title
--- 
```
### Posts
There are 7 example posts that you can review to see how to start creating your own blog posts. You'll notice the following patterns that you will have to follow for Jekyll to interpret correctly:

- Posts are saved as the `.md` type
- Post titles use the `yyyy-mm-dd-post-title` format
- Posts need to include the following front matter
```
---
layout: post
title: your post title
date: yyyy-mm-dd
---
```
Now you're ready to delete all of my posts and start creating your own!

## jNegative Credits
A massive thanks to:
- [GitHub](https://github.com) for the free hosting for this theme
- [Jekyll](https://jekyllrb.com) for creating and maintaining the static site generator this theme is built on
- [Zen Habits](https://zenhabits.net) for their clean design that inspired the design for this theme
- [Jonathan McGlone](http://jmcglone.com) for his [article](http://jmcglone.com/guides/github-pages/) that guided me through how to create this theme
- [Akshay Agarwal](http://akshayagarwal.me) for his [read me](https://github.com/AkshayAgarwal007/Jekyll-Mono/blob/master/README.md) that this theme's documentation is based on

## Questions
If you have questions or discover a bug then [open an issue](https://github.com/paulmostowyj/jNegative/issues/new).

## jNegative License
The jNegative theme is licensed under [MIT](https://github.com/paulmostowyj/jNegative/blob/master/LICENSE).
