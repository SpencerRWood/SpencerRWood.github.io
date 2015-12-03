---
layout: post
title: Hello World!
---

Hello! My name is Spencer Wood and my overall goal for this website is to provide information for the non-technical marketer explained in non-technical terms and how these tools and applications can be used in a very real way. While in undergrad my background included two degrees, one in Marketing and the other in Interactive Media Studies. My Marketing degree allowed me to have exposure to traditional marketing principles including consumer behavior, market research, sales, and various others in creativity and problem solving skills. This, as a standalone major, has numerous applications in itself, but, with the disruption that has been created by the Internet, the field of marketing is continually transitioning to a profession focused on merging technical skill with tradional marketing practices. This is where my classes involving digital anayltics, social media marketing, web developement and design, various introductions to programming, and usability have complimented my traditional marketing curriculum and provided a skillset to allow me to confidently enter the fast paced and involving marketing industry. 

For my first post, I will explain how I developed this website and provide resources for you to be able to create your own. First of all, this website was created with [Jekyll](https://jekyllrb.com/) hosted through [Github](https://github.com/) and is considered a [static webpage](https://en.wikipedia.org/wiki/Static_web_page) which means that you don't have to mess with a database programming language such as PHP. Other advantages of hosting your website on Github with Jekyll Now includes:

-Fast, responsive, and overall light design.
-Total customizability versus other taditional content management systems such as Wordpress.
-Easily integrate analytics and comments via plugins.
-Add your own custom domain.
-And most importanly, completely free to use with a Github account!

##Setting Up Your Personalized Website

When setting up your website, I do not recommend following the guide put out by the original Jekyll creators, as this requires an intimate knowledge of your system's terminal program, which can over complicate the process and discourage users. So if you have not already done so, you'll have to create a Github account, afterwards read and follow [Smashing Magazine's guide](http://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/#1-fork-a-starting-point) for forking and setting up your website through [Jekyll Now](http://www.jekyllnow.com/about/) written by Barry Clark who created this streamlined work around to using terminal. 

##Creating a Landing Page

Now that you have your site up and running, you might want to create a landing page that users access before your blog. Any HTML file that you create and drop into your Github repository with the designation of index.html will automatically be the first page users go to when they type in your website URL. This will require some working knowledge of both HTML and CSS, and while not necessary, will add a more personalized touch to your website and give you the future opportunity to conduct A/B testing to improve conversion rates of goals. Before we get to ahead of ourselves, if you aren't familiar with HTML or CSS there are tons of great courses from [Codecademy](www.codecademy.com) that will help you understand this fairly simple mark up language.

If you feel comfortable with your HTML and CSS skills, I recommend checking out [Usability Hour's guide](http://usabilityhour.com/landing-page-design/) to developing a landing page for the purpose of increasing conversion rates. This will also be a great introduction for good website design practices you'll be able to implement on your website.

##Understanding Google Anayltics

Within Smashing Magazine's guide there was a step that showed you how to easily integrate [Google Analytics](www.google.com/analytics) tracking to your website. For data-driven marketers, this is a crucial step. This will allow you to understand user traffic and behavior within your website along with demographic information, whether conversion goals are being met, and among various other statistical information important for making informed decisions about your site. For example, if you are experiencing a high bounce rate, the percentage of users who only click one page on your site, then you may want to adjust your landing page or content to better match user expectations of your website. There are hundreds of practical applications that can be syntehsized through analytical data such as this, I recommend becoming Google Analytics IQ certified, you can read up more on the processs [here](https://support.google.com/partners/answer/6089738?hl=en).

##Adding Additional Plugins

One of the benefits previously mentioned about using Jekyll is that it is versatile in the form of plugins. Default plugins introduced through using Jekyll Now include Google Analytics and Disqus comments. You can also add additional plugins that will add more functionality to your website. For example, I have added a plugin that will input a tagline after every blog post that says, "If you liked this post, you can share it with your followers or follow me on Twitter!" which, when clicked, will allow the user to share to his or her followers different blog posts, or send them to the author's Twitter page. This saves me time from writing out and linking this with every post and helps expand my social media prescence. If you would like to integrate this on your own site a guide can be found [here](http://joshualande.com/jekyll-github-pages-poole/), just be sure to scroll down to the section that discusses plugins. Finally, if you would like more access to dozens of more plugins, check them out [here](http://jekyllrb.com/docs/plugins/#converters-1) from the Jekyll website.

##Integrating a Contact Form

One of the advantages of designing a traditional dynamic blog website with a database programming language is that you can store user entered contact information from forms integrated into your site. Since our website is a static webpage, which means we do not possess these database capabilities, we need to create a work around for this. The easiest solution I found for this is from the guys at [Formspring.io](www.formspring.io). This will create an HTML workaround that when users enter their name, email address, and their message it will be sent directly to your inbox for you to respond. A great guide for understanding and implementing this solution comes [Sebastien Saunier](http://sebastien.saunier.me/blog/2014/04/15/you-do-not-need-a-database-for-your-contact-form.html) and a more in depth guide about from [Webdesign.tutsplus.com](http://webdesign.tutsplus.com/tutorials/quick-tip-add-a-formspree-form-to-your-static-sites--cms-23870)

##Formatting your Blog Posts

When wiritng blog posts you may be unfamilliar with how Jekyll processes information in your markdown blog posts. Here is a [guide from Barry Clark] that gives an easy introduction of how to properly format your posts so they are ready for the web.

##Conclusion

By following this guide, you should have a basic functioning website that you can host at almost no cost, depending on if you are using your own registered domain. This post will serve as documentation as I continually update and rework my website. If anything is unclear or you run into an issue, please leave a comment below and I will address it as soon as possible!
