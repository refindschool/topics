---
group: setup
---

Ultimate Beginner’s Guide for Those Who Want to Pursue Web Development or Design

### Introduction

This is the ultimate beginner’s guide for those who want to learn how to create amazing web experiences.

**This guide will cover:**

*   Internet fundamentals
*   The world wide web (and its components: like images, HTML, and CSS)
*   Client side versus server side
*   Helpful workflow toolsÓ
*   Where you can start learning
*   _And much more_

As you can see, this beginner’s guide focuses on the building blocks of the web.

**This guide is perfect for:**

*   People who want to learn to code, but aren’t sure exactly what it is they want to learn
*   People who want to make websites and are just starting out
*   Those interested in web development/design, but are not clear on the basics on the internet

Ultimately, this guide is ideal for those who want to pursue web development or web design.

**As you navigate throughout the guide, feel free to use the side panel on the left to jump around from topic to topic.**

And if you’re no longer a beginner, check out my [topics page](_ __table-of-contents/topics/_). Here you can learn more in-depth information about a particular web design / development topics.

### How it all works

#### **The Internet**

If you’re confused with how the internet works, [I highly recommend watching this short five minute video.](https://www.youtube.com/watch?v=7_LPdttKXPc) It is extremely informative, and explains a lot.


But basically:

We connect to the internet through our computers (AKA clients). We do this by going through Internet Service Providers (ISPs) to web servers.

Therefore, **our computers are not directly connected to the internet**, but to hardware. Hardware is just one of two main components of the internet.

Examples of computer hardware include:

*   Routers
*   Servers
*   Cell phones
*   Or 4G towers that are capable of transmitting wireless signals to connect you to the internet

![internet hardware](http://learntocodewith.me/wp-content/uploads/2014/08/hardware.png?230531)

**1\. Internet Protocol (IP) Address**

This is the second of the two main components of the internet. An **IP****address **is an identifier for each device (e.g. computer or cell phone) participating in a Transmission Control Protocol/Internet Protocol (TCP/IP) network.

In order to establish a connection with the site you visit on the internet, your computer will ask another computer for the web page. The latter will then retrieve the correction web page, and deliver it right to your IP address.

The IP address contains a unique string of numbers. Basically, it uses binary bits to create single unique address on the network, and there are currently two versions of it:

****a. IPv4: ****is the most widely used IP address which uses a 32-bit address system that looks like this –

115.227.10.95

****b. IPv6: ****uses a 128-bit address system. They are super long and contain eight groups of number separate by a colon –

FE80:0000:0000:0000:0202:B3FF:FE1E:8329

#### Want to know your IP Address? try this:

1\. Go to [Google](https://www.google.com/)

2\. Search "my IP"

3\. Your IP address will display as the search result


****Public IP Address****

Each device that connects to the internet has a unique IP address—like an ID, or social security number. Or home address.

This means that there is never more than one computer using the same IP address.

And to avoid conflict, each IP address is publicly registered in the Network Information Center (NIC). This addressing system makes it possible for the computers to identify each other, connect and exchange information.

There are **two ways** to acquire a public IP address: static and dynamic.

See the chart below for a comparison on the two.

| Public IP addresses comparison     | VStatic | Dynamic   |
| :------- | ----: | :---: |
| Changeable?| No |  Yes    |
| Who sets/assigns it?    | ISP, mostly   |  Distributed by Dynamic Host Configuration Protocol (DHCP) servers   |
| Good for…?     | Hosting web pages   |  Common internet usage  |

**Private IP address**

Private IP addresses are used for numbering the computers in a private network so that computers in that given network can communicate with one another.

This kind of interconnectivity is possible by **two network services **and is illustrated below:

![lan vs wan](http://learntocodewith.me/wp-content/uploads/2014/08/lan-vs-wan.png?230531)

**i. Local Area Network (LAN) **is the connection between computers within a small sized network. It only covers localized areas such as:

*   Homes
*   Offices
*   Schools

**ii. Wide Area Network (WAN) **is the connection between computers within a large sized network. It covers large geographic areas such as:

*   Cities
*   States
*   Nations

By default, a computer with a private IP address can only connect directly to the internet. Likewise, computers outside the local network cannot connect to a computer with a private IP.

An IP address is private if its IP number is within these IP address ranges reserved by the **Internet Assigned Numbers Authority (IANA**):

*   10.0.0.0 – 10.255.255.255 (Total addresses: 16,777,216)
*   172.16.0.0 – 172.31.255.255 (Total addresses: 1,048,576)
*   192.168.0.0 – 192.168.255.255 (Total addresses: 65,536)

These IP addresses cannot connect directly to the internet without the use of **Network Address Translation (NAT)** through a supported device like a router.

If the private network is connected to the internet via an ISP, the computer will then acquire a public IP address as well.

**2\. Domain Name**

If the IP address is like the home address of your computer, a **domain name** is like a telephone number on the internet.

_However, not everyone who has a computer has a domain name._

The website address, also known as the **Uniform Resource Locator (URL)**, is the unique address of a website that you type in your address bar and instantly access it.

![url in search bar](http://learntocodewith.me/wp-content/uploads/2014/08/url-in-search-bar.png?230531)

You can get your own website address by registering a domain name. AKA purchasing it.

My favorite place to buy domain names is [name.com](https://www.name.com/). However, there are many places where you can buy domain names.

All domain names are unique. Meaning if it is already taken, like “Microsoft.com”, you cannot register it.

<div class="clearfix sidenote">

#### What are Domain Name Servers (DNS)?

DNS is the Internet’s equivalent to a “**phone book**”.

Essentially, it is the complete database of domains and their registered IP addresses. This distributed system allows other computers to know where to go to find your website.

To learn more about DNS and how they work, go [here](http://www.actnowdomains.com/domain-name-server-definition.htm).

</div>

#### The World Wide Web or the ‘Web’

Often just called the “web”, the World Wide Web is a system of interlinked hypertext documents that are built on top of the internet. It is based on a **hypertext transfer protocol (HTTP)**, a procedure in which exchanging information is possible.

You may be wondering if exchanging information is possible, can sensitive information like credit cards or passwords entered in web forms be shared with anyone?

Luckily, this is not the case because network administrators have come up with the** hypertext transfer protocol secure (HTTPS)** to protect important and sensitive information.

Examples of websites that use HTTPS always or when users are logged into their account include:

*   Gmail
*   Facebook
*   YouTube
*   PayPal
*   Your bank’s website
*   And many more.

**_Note: _**_Whenever accessing any kind of account online where important information is stored, always check to see if the web page has the “_**_https_**_” before the rest of its link, as pictured below._

<div class="tm-tweet-clear"></div><div class="tm-click-to-tweet"><div class="tm-ctt-text">[When accessing sensitive info online, make sure the URL has ‘https’ in the beginning.](https://twitter.com/share?text=When+accessing+sensitive+info+online%2C+make+sure+the+URL+has+%E2%80%98https%E2%80%99+in+the+beginning.&via=learncodewithme&related=learncodewithme&url=http://learntocodewith.me/getting-started/)</div>

[ Click To Tweet](https://twitter.com/share?text=When+accessing+sensitive+info+online%2C+make+sure+the+URL+has+%E2%80%98https%E2%80%99+in+the+beginning.&via=learncodewithme&related=learncodewithme&url=http://learntocodewith.me/getting-started/)

</div>![https in the browser](http://learntocodewith.me/wp-content/uploads/2014/08/https-browser.png?230531)

**Note**: The internet is not the web!

The internet and the web are often used interchangeably. However, technically they are two different things and have a whole-to-part relationship.

Meaning the web is only a portion of what the internet offers. See the illustration below:

![internet vs www](http://learntocodewith.me/wp-content/uploads/2014/08/internet-vs-www.png?230531)

Next, let’s talk about some of the important elements of the web.

****1\. Web browser ****is the application program used to view web pages online.

A few examples of web browsers are:

*   Internet Explorer
*   Google Chrome
*   Firefox
*   Safari
*   And many more

In fact, you are using some kind of web browser right now to read this page :)

<span class="callout">**Do you know?** The first web browser was called WorldWideWeb, but because it was often confused with the “web” itself, it was changed to Nexus later on.</span>

**2\. Website, **or simply “site”, is a location when you visit a domain in the World Wide Web. It maintains a single page or a group of interconnected pages.

Each site has its own _homepage_ which is the first document you see when you go to a domain.

There are two most common types of websites:

**a. Web application **is any software or program that runs in a web browser. This is where interaction takes place—anyone can create accounts, store information, etc.

What makes web applications different from basic web pages is that applications have a database to store information.

Most of the sites we use day-to-day are applications. A few examples include:

*   Facebook
*   Twitter
*   Craigslist
*   LinkedIn
*   Reddit

Web applications are also defined by their many-to-many relationship.

**b. Blog **(short for weblog) is like a journal or a diary for public viewing. It is the most common type of a website.

It is written and managed by one writer or a small group of writers for various purposes and categories that include but not limited to:

*   Personal
*   Business
*   Education / Schools
*   Non-profits
*   Politics
*   Sports
*   Reviews, how-to’s and tips

A few examples of blogs include:

*   [learntocodewith.me](http://learntocodewith.me/)
*   [jobsearchtech.about.com](http://jobsearchtech.about.com/)
*   [joshowens.me](http://joshowens.me/)
*   Tech Crunch (giant news sites are like big blogs)

**Dynamic vs. Static Blogs**

Some blogs, like those using WordPress, are considered **_dynamic_**. They use database and have a backend, so technically, they are a web app.

On the other hand, some blogs like those built on Jekyll (jekyllrb.com), are **_static_** because they do not use a database to store information.

<span class="callout">**Want**** to know how many blog posts being published today?**Click here: [www.worldometers.info/blogs](http://www.worldometers.info/blogs/).</span>

Below is a comparison between typical web applications and blogs:

<table class=" table table-bordered table-striped"><tbody><tr><th>Web App</th><th>Blog</th></tr><tr><td>Anyone can sign up and create content</td><td>Only admin users can sign in and create content (usually one person or a small group)</td></tr><tr><td>**Many-to-many:** many people can create content (Tweets, Posts, etc.) and many can read them</td><td>**One-to-many:** One person or a small group (authorized by the main admin user) can write posts and many people can read them</td></tr></tbody></table>

<span class="callout">**Did you know?** According to [OneMonth.com](http://learn.onemonth.com/80-percent-of-websites-are-the-same), if 80% of websites online are blogs, then 80% of websites are the same!</span>

**3\. Web page **is a single, hypertext document of a website. (Again, like the page you are on right now! Right now you are on the /getting-started page.)

_Here is an example:_

This shows the web page (blog) in a website (learntocodewith.me). On the right upper portion are the site’s other web pages that can be accessible by clicking on them.

Each will take you to a different page, but it is still inside the same website.

![webpage example](http://learntocodewith.me/wp-content/uploads/2014/08/webpage.png?230531)

**4\. Web images **make up a good portion of the web.

These are the images we use day in and out—such as .jpg, .png, and .gif.

Of course, some websites rely more on images than others. (For instance, Flickr is basically all images, whereas Craigslist is almost none.)

**Here is a way to see how many images the current web page you are visiting has:**

*   Right mouse click
*   Select “**inspect element**”
*   Select the “**resources**” tab
*   Select the “**more**” drop down indicator
*   Select the “**images**”
*   See all the images on that given page

![all images on page](http://learntocodewith.me/wp-content/uploads/2014/08/all-images-on-page.png?230531)

The example above is using [this page](http://jobsearchtech.about.com/od/education/tp/6-Of-The-Best-Tech-Meetups-in-the-US.htm).

****5\. Hyperlinks ****are the commands embedded in a text or an image that direct you to go from one web page to another.

They are like “portals” that take you wherever they want you to go_._

You can see if something is hyperlinked when your mouse pointer changes to a pointing finger (see image below).

![hyperlink](http://learntocodewith.me/wp-content/uploads/2014/08/hyperlink.png?230531)

Another way you can oftentimes tell that something is hyperlinked is when you “**hover**” (have mouse over the word or phrase), an underline appears.

This often signifies that it is in fact a URL.

### The Client Side vs. The Server Side

Let’s now take a more in-depth on what makes up the client and server side.

![client-server](http://learntocodewith.me/wp-content/uploads/2014/08/client-server.png?230531)<address>

_([Image](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms/Sending_and_retrieving_form_data) by Mozilla Contributors is licensed under CC-BY-SA 2.5.)_

</address>

#### 1\. Understanding the Client Side

The client side is called this because it involves everything taking place on your computer, or “client”. It is also referred to as the front end. The terms can often be used interchangeably.

<div class="clearfix sidenote">

Web designers and front-end developers are the people who work primarily on the client side because they focus on the outer appearance and user experience (UX) of websites and applications.

</div>

HTML, CSS, and JavaScript all take place on the client side.

**a. HyperText Markup Language (HTML)**

HTML is crucial when building websites. I often compare HTML to “the face” of a web page. It is made up of set/s of characters and symbols to present the intended display of a web page.

Below is an example of a hyperlink written in HTML code:

`<a href = "http://en.wikipedia.org/"> Wikipedia </a>`

**HTML is not technically programming.** Programming involves logic, functions, loops, and sets of directions.

Nonetheless, HTML still plays a critical role when it comes to building web pages.

HTML defines the logical, structural parts of a web page. HTML uses tags, like the `<p>` tag, to identify paragraphs on a web page.

HTML works hand-in-hand with other parts of the client side, like CSS and JavaScript.

Typically when people first start learning about how to build websites, they start by learning HTML.

**Note**: One of my favorite places to learn [HTML is on Code School](http://learntocodewith.me/code-school-html-css). They even have some classes for free.

**b. Cascading Style Sheets (CSS)**

CSS is the the “style” of a web page. If HTML is the face, then CSS is the makeup because it defines the way a web page will appear.

It is responsible for the style and layout websites and web applications.

Below is an image showing HTML and CSS working together in the browser.

<div id="attachment_3664" style="width: 910px" class="wp-caption aligncenter">![HTML and CSS working together](http://learntocodewith.me/wp-content/uploads/2014/08/html-vs-css.jpg?230531)

[Image](http://wptribe.net/wp-content/uploads/2013/03/Firebug-%E2%80%93%C2%A0HTML-vs-CSS-window.jpg) by wptribe.net

</div>

With the latest version of CSS, CSS3, it can even do things like animation and transitions.

Below are some CodePen examples of cool things people have done with HTML and CSS alone:

*   [Animated Google Drive Logo](http://codepen.io/Dreamdealer/pen/AvBja)
*   [An iPhone](http://codepen.io/fbrz/pen/vlrnd) (no images were used!)
*   [An on and off button](http://codepen.io/maturo/pen/dxAhE)
*   [Awesome loaders](http://codepen.io/TaniaLD/pen/oKxep)

As you can see, you can achieve a lot with CSS alone as far as styling, appearance and effects go.

Once upon a time, you needed JavaScript to do any kind of web animations. Now, it’s possible with just CSS.

Browse [CodePen](http://codepen.io/tag/css%20only/) to see more samples of CSS in action. Or you can learn more about [CSS](http://learntocodewith.me/getting-started/topics/css/) here.

**c. JavaScript (JS)**

JavaScript is responsible for the behavior of an application. It can also add interactivity to a web page by:

*   Manipulating elements directly
*   Manipulating the HTML and CSS structures

JS is unique because it is one of the few programming languages that can run both on the client and on the server.

Right now, in this section, we’re focusing on the JS that can run in the client. This means that it runs the scripts on your computer after you have loaded the web pages.

JavaScript on the client side helps us create things with interaction/animation. For instance, [like making a quiz](https://laurencebradford.github.io/wp-quiz/). While CSS has a lot of features and capabilities, JS allows you to take your web pages to another level.

**Here is a CodePen example of HTML, CSS and JS **[**working together on the front end**](http://codepen.io/dats-wassup/pen/FsGtu)**.**

This code example is getting the current time on our computer and displaying it, with styling/animation effects.

Looking at the CodePen, try this:

1.  **Remove the JS** code from this pen.<ul>*   You still see a simple triangle, but the time is missing.
	</ul>

	![codepen - js removed](http://learntocodewith.me/wp-content/uploads/2014/08/codepen-js-removed.png?230531)
3.  **Remove the CSS.** (Note: here on CodePen they are using a preprocessor called Stylus, that gets compiled into CSS when it comes to your browser. Just think of it as normal CSS here.) What happens?<ul>*   The time is still appearing…but all the styles are gone!
	</ul>

	![codepen - css removed](http://learntocodewith.me/wp-content/uploads/2014/08/codepen-css-removed.png?230531)
5.  **Remove the HTML**. What happens?<ul>*   The screen is just black. Everything disappears.
	*   The reason why the screen is black is because the CSS defined the body to be black.
	</ul>

	![codepen - html removed](http://learntocodewith.me/wp-content/uploads/2014/08/codepen-html-removed.png?230531)

**To sum up the client side and how it works:** the image below illustrates how each of the three components work together on the front end.

![client side js + html +css](http://learntocodewith.me/wp-content/uploads/2014/08/client-side.png?230531)

#### 2\. Looking at the Server Side

The server side is also known as the backend. The two terms can be used interchangeably.

The backend is where scripts are run and databases are stored. Without the backend, websites would not be functional.

The server then “serves” this information to the client, or your computer.

![server side](http://learntocodewith.me/wp-content/uploads/2014/08/server-side.png?230531)

The illustration above shows how a web server works.

*   When the client (your computer) visits a domain, it requests to access information in the web server.
*   The request is being submitted to the PHP interpreter for processing (PHP is being used in this example, but it could be another language).
*   Server responds by sending the content in HTML for viewing on your web browser.

<div class="clearfix sidenote">

#### Front end vs. Backend Developers

Those that work on the server side are often called [**backend developers**](http://jobsearchtech.about.com/od/Web-Development/fl/The-Skills-You-Need-to-be-a-Backend-Developer.htm)**.** Those who deal with the client side, appropriately called [**front end developers**](http://learntocodewith.me/web-dev/front-end-developer-skills).

The main difference is that backend developers are responsible for making websites/applications functional, whereas front end developers more concerned with appearance.

</div>

Terms associated with server side include:

**a. Database**

A database stores information for your web application. It is a structured system that efficiently accesses, organizes, retrieves, and manages collected information.

There are two main kinds of of databases: **relational** and **non-relational** (or NoSQL).

<table class=" table table-bordered table-striped"><tbody><tr><th>Relational</th><th>Non-relational</th></tr><tr><td>Represents data as tables and rows</td><td>Represents data as collections</td></tr><tr><td>Ability to contain multiple operations</td><td>Single operation</td></tr><tr><td>Requires you to define your tables and columns before you can store anything</td><td>Drop in documents</td></tr><tr><td>Highly structured and rigidly-defined data formats</td><td>Flexible, optimized and varied record format</td></tr></tbody></table>

 **Relational : ** data organized into tables, using rows and columns. Using a foreign key, tables can be linked to other tables.

**Non-relational :** data is organized in means other than tabular relations. Also referred to as NoSQL. These databases are often used in big data and real-time web applications. Instead of tables, NoSQL databases like [MongoDB use arrays](http://blog.mongolab.com/2013/04/thinking-about-arrays-in-mongodb/) to store information.

Examples of popular databases are:

*   ****MySQL: **** most common relational database, used with WordPress websites
*   **MongoDB: ** NoSQL database that is growing in popularity
*   **PostgreSQL** : enterprise level, open source object-relational database system

**b. Web Server**

Web servers are computer systems that deliver content or services to end users over the internet.

According to [Technopedia](http://www.techopedia.com/definition/4928/web-server),

> “A Web server is also known as an Internet server. It consists of a physical server, server operating system (OS) and software used to facilitate HTTP communication.”

Examples of web servers include:

*   Apache
*   nginx
*   IIS (Microsoft)
*   GWS (Google)

The most popular web servers are Apache and IIS, both making over 30% of the market share, according to [netcraft.com](http://news.netcraft.com/archives/2015/03/19/march-2015-web-server-survey.html).

**c. Programming language**

Programming languages are a coded and constructed language. They are used to communicate commands with machines like computers that only understand binary.

We use programming languages to tell computers what to do. _It’s like a set of instructions._ A special program called an interpreter converts these instructions so that the computer can understand.

PHP, ruby, and python are all popular programming languages for the web. Of course, there are programming languages for a variety of purposes.

Below are some programming languages that are often used on the server side, or backend.

1.  **PHP **is a server-side scripting language. It is used on the backend of the popular [WordPress](http://learntocodewith.me/getting-started/topics/wordpress/) CMS. There are also PHP frameworks like [Laravel](http://laravel.com/) which can be used for building web applications.
2.  **Ruby** is a popular programming language that is often used with the [Rails](http://rubyonrails.org/) framework to build out web applications. Using these two together is called Ruby on Rails, or RoR.
3.  **Python** is another common programming language. When it comes to building web applications, it is often used with the [Django](https://www.djangoproject.com/) framework. Oftentimes beginners learn Ruby on Rails or Python and Django. [Check out a comparison of the two here.](https://www.coursereport.com/resources/ruby-on-rails-vs-python-and-django-which-should-a-beginner-learn)<div class="opt-in-form signup"><form method="post" accept-charset="UTF-8" action="https://www.aweber.com/scripts/addlead.pl"><input type="hidden" name="listname" value="awlist3555445"><input type="hidden" name="redirect" value="http://learntocodewith.me/exclusive-content/"><input type="hidden" name="meta_redirect_onlist" value="http://learntocodewith.me/wp-content/uploads/2014/08/my-favorite-python-resources.pdf"><input type="hidden" name="meta_message" value="1"><input type="hidden" name="meta_required" value="email">

5.  **JavaScript** on the server side is used with [node.js](https://nodejs.org/). There are also different frameworks now available for building fullstack web applications, like [Meteor.js](https://www.meteor.com/).
6.  **C#** is a combination of C++ and Visual Basic; designed to work with Microsoft’s [.Net framework](https://msdn.microsoft.com/en-us/library/z1zx9t92.aspx).

<table class=" table table-bordered table-striped"><tbody><tr><th>Client vs. Server Comparison</th><th>Client-side (front end)</th><th>Server-side (backend)</th></tr><tr><td rowspan="5">USES</td><td>Make interactive web pages</td><td>Process user input</td></tr><tr><td>Display pages</td><td>Helps stuff happen dynamically on the web page</td></tr><tr><td>Interact with temporary storage, and local storage</td><td>Structure web applications</td></tr><tr><td>Send requests to the server, and retrieve data from it.</td><td>Interact with permanent storage (SQL, scripting files)</td></tr><tr><td>Provide a remote service for client-side applications, such as software registration, content delivery, or remote multi-player gaming.</td><td></td></tr><tr><td rowspan="4">LANGUAGES</td><td>JavaScript (primarily)</td><td>PHP</td></tr><tr><td>HTML*</td><td>Ruby</td></tr><tr><td>CSS*</td><td>Python</td></tr><tr><td>Any language running on a client device that interacts with a remote service is a client-side language.</td><td>Nearly any language (JavaScript, C++, C#, Java). These were not designed specifically for the task, but are now often used for application-level web services.</td></tr></tbody></table>

*HTML and CSS* aren’t really “programming languages”, per se. They are markup syntax by which the client renders the page for the user.

### Helpful Workflow Tools

#### 1\. Content Management System (CMS)

A CMS is a computer software that is used to create, modify, upload, and manage content displayed on a website.

CMS’s have been designed to make a collaborative and user-friendly environment for non-technical users to add, edit, and [manage a website](https://plone.org/documentation/faq/what-is-a-cms). However, it is also a great choice for technical people because it makes adding and managing content easier.

**What are the **[**basic features and benefits of using a CMS**](http://redflag.ie/resources/content-management-system-features-and-benefits/)** on your website?**

1. Allows you to manage and organize your website pages and posts
  * Text content management
  * Upload and post images and videos
2.  Straightforward installation of templates and themes
3.  Offers plugins as website add-ons, which can give your site additional functionality and features
4.  Many CMS’s provide basic [search engine optimization](http://learntocodewith.me/posts/learn-seo/) (SEO): used for helping your site rank on search engines like Google
5.  Some CMS’s have built-in web traffic analytics that track and report website/page/post traffic

These are just some of the features CMS’s may offer.

Many also have helpful ways of allowing you to update large quantities of information at once, for instance a bunch of blog posts.


A few examples of the [widely used CMS](http://skillcrush.com/2012/05/01/cms/)’s include:

*   [**WordPress (WP)**](http://learntocodewith.me/getting-started/topics/wordpress/)**:** best pick for beginners who want to blog; most popular CMS in the world with more than 60 million websites built using WordPress
*   [**Magento**](http://learntocodewith.me/getting-started/topics/magento/)**: **most common e-commerce CMS
*   [**Joomla**](https://www.joomla.org/): good for e-commerce websites but requires some understanding in coding
*   [**Drupal**](https://www.drupal.org/): open source CMS and one of the most powerful
*   [**Tumblr**](http://learntocodewithme.tumblr.com/)** and **[**Blogger**](https://www.blogger.com/): focused on blog style formats—good for uploading images, videos, text, etc.


#### The difference between WordPress.com and WordPress.org

Oftentimes beginners get confused over the difference between WordPress.com and WordPress.org.

Simply put, WordPress.com is hosted on WordPress’s servers. Unless you upgrade your account, your domain will have a **.wordpresss.com** at the end. On the other hand, WordPress.org is open-source and allows for more control. But you must have your own domain name and server to use it.

When I talk about WordPress, 99% of the time I am referring to WordPress.org.


#### 2\. Text Editors and IDEs

**a. Text editors** are software programs you can download on your computer, where you can edit your programming files.

Most text editors allow you to edit a range of different types of files—.html, .css, .js, and so on.

There are a many [text editors](http://lifehacker.com/five-best-text-editors-1564907215). Here are a few popular ones:

*   **[BBEdit](http://www.barebones.com/products/bbedit/)**: leading HTML and text editor for Mac users. It has a 30-day free trial, but then the price would be $49.99.
*   **[TextMate](https://macromates.com/)**: general-purpose text editor for Mac OS X users that you can download for free. However, the upgraded version TextMate 1.x costs from about $835 for 30 users to about $2,783 for unlimited users.
*   **[Sublime Text](https://www.sublimetext.com/):** cross-platform text and source code editor plus plugins you can add. You can get a free trial but the license costs $70.
*   **[Atom](https://atom.io/):** free text editor developed by GitHub for OS X, Linux, and Windows users.
*   **[Notepad ++](http://notepad-plus-plus.org/):** free text editor but donations are accepted :-)

I use [Atom](https://atom.io/) and have been since I first got started. However, all text editors basically do the same thing: it’s just a matter of preference.

You can learn [more about text editors here](http://learntocodewith.me/programming/basics/text-editors/).

****b. Integrated Development Environments (IDE)**** are similar to text editors, but with more features.

According to [Technopedia](http://www.techopedia.com/definition/26860/integrated-development-environment-ide),

> “Most common features, such as debugging, version control and data structure browsing, help a developer quickly execute actions without switching to other applications. Thus, it helps maximize productivity by providing similar user interfaces (UI) for related components and reduces the time taken to learn the language.”

IDEs can also have automation and compiling tools.

Many IDEs are language-specific: meaning the IDE will have full support to help you identify if there are syntax errors, missing brackets, and more.

IDEs can be pricier than Text Editors. Others are free. For instance, [NetBeans](https://netbeans.org/).

There are also some IDEs just for mobile development, like [Andriod Studio](https://developer.android.com/tools/studio/index.html).

Examples of common IDEs include:

*   **[PyCharm](https://www.jetbrains.com/pycharm/)**: Made by Jetbrains, Python specific. Can get a new personal license for $99.
*   **[Visual Studio](https://www.visualstudio.com/):** Made by Microsoft. It costs $299 but the full price for Visual Studio 2013 Professional (i.e. non-upgrade) is $499.
*   **[Rubymine](https://www.jetbrains.com/ruby/):** Ruby on Rails IDE. Also made by Jetbrains. Personal license is $99.
*   **[PhpStorm](https://www.jetbrains.com/phpstorm/):** Also made by Jetbrains , also $99 for personal license.
*   **[Webstorm](https://www.jetbrains.com/webstorm/):** JavaScript IDE that is also made by Jetbrains. A personal license is only $49.

Learn more about [IDEs and other helpful workflow tools here](http://learntocodewith.me/posts/inside-developers-tool-kit/).

#### 3\. Command Line Interface (CLI)

The CLI is a user interface to a computer’s operating system which provides a textual input-output communication between a user and a computer.

It is an application that you can use to interact with the computer by typing in commands.

It can also be known as:

* **Command-line user interface**
* **Command language interpreter**
* **Terminal **on a Mac
* **Command Prompt** on Windows/MS-DOS
* **The Shell** (Unix and Linux notably)


The [command line](http://learntocodewith.me/getting-started/topics/command-line/) is very important to learn, or at least become familiar with. This is especially true if you want to do web development rather than design.

**Why use the CLI?** It gives you greater access to the internals of your computer: there is only so much you can do from your desktop.

For example, check out [this video where a young girl “hacks”](https://www.youtube.com/watch?v=W76o_iG7Y7g&feature=youtu.be) into her father’s computer from her own computer. She does this through the shell, and closes one of open his programs. **This is something that could only be done through the command line.**

Although a web designer would not necessarily need to use the command line, it definitely could come in handy. (And act as a resume-booster.) Here are some [command line quick tips for designers](http://webdesign.tutsplus.com/articles/a-designers-introduction-to-the-command-line--webdesign-6358).

**How to locate your computer’s command line interface:**

1.  To open the Command Prompt on a Windows/MS-DOS:*   Go to the **Start Menu**
	*   Type “cmd” in the **Search programs and files** box
	*   Press **Enter**
2.  [To open CLI on a Mac](http://learntocodewith.me/command-line/open-command-line/):*   Open your **Finder** (available in the Dock)
	*   Select **Applications**
	*   Choose **Utilities**
	*   Double click the **Terminal**

Remember: the CLI cannot interpret _any_ command you type. There are specific text commands (depending on your operating system) you must type in order for the computer to know what to do.

**Also, you cannot use your mouse in the CLI.** Meaning you cannot click around—it is keyboard-use only.

To make things easier, here is a cheat sheet for some commands that are [regularly used in the Unix command line](http://learntocodewith.me/command-line/unix-command-cheat-sheet/) (AKA Mac users).

<div class="clearfix sidenote">

#### Sidenote: What is a Graphical User Interface (GUI)?

You will see the term “GUI” mentioned many time in intro courses or books.

Basically, most people use the GUI for most tasks on the computer. We can use our mouse, click, there are images, icons, etc. In GUI, the keyword is **graphical**.

The commands line differs from a GUI. **It is not graphical**. It is text commands only.

</div>

#### 4\. Git and Github

**Git** is a form of version or revision control system that runs in command line interface.

**How does Git work?**

*   **Tracking**: it makes a permanent record who made which change.
*   **Merging:** this is useful in a team environment; everyone can work independently on each file and merge files anytime while also saving copies of their older versions.
*   **Resolving a conflict**: if the same files have been worked on, it gives an option to choose which portion to use.
*   **Reverting**: since there are records of older versions of the work, you can revert back to previous versions. Keep in mind, though, _that you can only revert entire files_. You cannot cherry pick parts of previous versions to revert, you have to overwrite the entire file.

**Important terms and functions of Git: **

*   ****Version Control**: **the purpose of Git. It keeps versions of files you’re working on. However, you must use commands in your CLI to “commit”. It does not automatically save versions for you.
*   **Repository**: AKA “repo”, is the directory (whether a folder on your computer, storage space on Github or another online host)  where you keep your files.
*   **Commit**: it’s a checkpoint where you are taking a “snapshot” of the project. You can later go back, inspect the snapshot, and possibly restore it to the previous version.
*   **Branch**: when multiple users work on a project, they _branch_ out from the original version. This is ideal for building out new features. And when it’s done, allows them to merge that branch back with the master version.

**Some common Git commands:**

*   **git init [project-name]**: initializes a git repository in your given directory
*   **git commit**: commits changes to be made
*   **git push [alias] [branch]**:  attempts to make your new branches and data to a remote repository
*   **git pull**: fetches a repository and tries to merge into the current branch

**Github** is similar to a social networking site…but for coders. You can follow others and their work. Moreover, you can “push” your own code, and “pull” or clone other’s repositories.

**Why use Github?**

Github allows you to show your projects online, or contribute to others. Or use others to build your own future projects. This is a staple of [open source](http://opensource.org/), which is defined as:

> “Open source software is software that can be freely used, changed, and shared (in modified or unmodified form) by anyone.”

Moreover, you can work and collaborate with others, like friends or colleagues.

In addition to that, Github offers you the following:

1.  Store your files/projects
2.  Easy collaboration of your version-controlled projects
3.  A visual interface for navigating and managing your repos
4.  Other users can have access and build off your repos

Github is also popular amongst hiring managers and recruiters who may look at your Github to see your code. In this way, it is almost like LinkedIn or an online portfolio of your code samples.

**Public versus Private Repositories **

Github has two different kinds of plans: free and paid.

The only difference in the two is that the paid plan has private repositories.

Public repositories can be viewed by anyone, whereas private repositories can only be access by the owner and collaborators who have been given access.

**What does this mean?** If you are using a free plan, with a public repository, the whole world can see it. **So do not put sensitive information up! **Such as passwords, personal info, photos, etc. Basically, anything you do not want others seeing.

Also if you are working on something you don’t want people to see—like a new web app or feature that is not released yet—use a private repository.

**Hosting Static Sites on Github**

Github is a perfect tool for testing websites before launching. Or for other small projects.

However, you can only host static assets (HTML, CSS, Images and JS), and not a WordPress site, Ruby on Rails (RoR) application or similar on Github Pages.

Keep in mind it’s free to host static sites on Github. But you will be using their servers…meaning it could be slow. So, it’s not ideal for a business site.

Learn more about getting your site online by [using Github Pages here](http://learntocodewith.me/tutorials/github-pages/).

**Using Github with the GUI**

Even though you **should** learn the command line, it is possible to use Github without it.

With  Github, you can either access it via CLI or through a GUI software program you can install.

*   [**Github for Mac**](https://mac.github.com/)
*   [**Github for Windows**](https://windows.github.com/) (except for Windows XP)

This is a useful tool for beginners, or others who do not like to use the CLI. Even better, this GUI software is free to download. _I do not use them,_ but many people do.

#### 5\. File Transfer Protocol (FTP)

FTPs are a way to get your website files online by allowing you to transmit files onto internet between computers and your web server.

FTP accounts allow you to access your website’s files through a protocol called FTP.

![how a FTP works](http://learntocodewith.me/wp-content/uploads/2014/08/ftp.png?230531)

There are various FTP options to choose from:

*   [**Cyberduck**](https://cyberduck.io/?l=en): I use Cyberduck as my FTP, which is free and available on Mac and Windows (as of version 4.0).
*   [**FileZilla**](https://filezilla-project.org/): a popular option which is also free and available on both Windows and Mac machines.
*   [**CoreFTP**](http://www.coreftp.com/): A free FTP for Windows machines.

Some premium text editors that have FTPs built right in, such as [BBEdit](http://www.barebones.com/products/bbedit/benefitscommand.html#top), [Aptana](http://www.aptana.com/), and [PSPad](http://www.pspad.com/en/pspad.htm)

There are other ways to get your site online, of course.

But especially for beginners, FTPs are easy because they are GUI’s. Meaning it is easy to drag and drop files to make updates on your website.

Below is an example of a WordPress theme folder on the CyberDuck FTP.

![WP theme on CyberDuck FTP](http://learntocodewith.me/wp-content/uploads/2014/08/WP-theme-on-CyberDuck-FTP.png?230531)

With CyberDuck, FileZilla or any comparable FTP there is no need to use the command line.

Configuring your FTP with the appropriate credentials can be done through your host. You can add users to access your site via FTP, giving a unique password.

For instance, on my host [Bluehost](http://learntocodewith.me/bluehost-hosting), they have a whole area dedicated to FTPs.

Here you can create new credentials, for new users. And for different sites on your account (so, if you have more than one website on your hosting provider, like I do).

![bluehost ftp](http://learntocodewith.me/wp-content/uploads/2014/08/bluehost-ftp.png?230531)

Again, there are multiple ways to get your websites or web applications online. FTPs are great for basic websites or WordPress sites. When it comes to more advanced applications—people typically don’t use FTPs.

**However, for beginners, FTPs are a great way to get your site online. **

### Where to Start Learning

Below are a few online learning platforms and related that I recommend for beginners. (All of which I have used personally.)

[**Team Treehouse**](http://learntocodewith.me/2-weeks-free-treehouse)**:** Treehouse has a large online course library with variety of options. However, courses mostly relating to web development and design. Treehouse has two pricing plans: the basic and pro plan. The pro plan gives you access to more courses and workshops for a higher price. [Click here to get your first two weeks on Treehouse absolutely free](http://learntocodewith.me/2-weeks-free-treehouse).

[**Code School**](http://learntocodewith.me/code-school)**:** Code School is quite similar to Team Treehouse, but with less course options. However, they have a stronger emphasis on web development topics in my opinion—especially JavaScript. They also offer different level courses starting from beginner to more advanced. There is only one monthly price. it is monthly. [Continue here to get your first month at Code School for only $9](http://learntocodewith.me/9-bucks-code-school).

[**One Month**](http://learntocodewith.me/one-month)**:** One Month has a range of courses that focus on development and digital marketing primarily. The platform is called “One Month” because all courses are designed to take 30 days. (However, you can go at your own pace.) Unlike other learning platforms listed here, you pay by the course on One Months. Overall, they have great student support where you can ask your questions directly to a human being. Read my [review of One Month Rails here](http://learntocodewith.me/reviews/one-month-rails/).

[**Lynda**](http://learntocodewith.me/lynda-one-week)**:** Lynda.com is a massive online library with thousands of courses on a variety of topics from design to development. They even have classes on negotiating or starting your own business. Here, you pay by the month. There are two price tiers: basic and premium. Both have the same courses—but the premium membership gives you special access to files from the courses. [Click here to get your first week free on Lynda.com.](http://learntocodewith.me/lynda-one-week)

[**CodeMentor:**](https://www.codementor.io/r/9H5Z7PV4E2) This is not an online learning platform, but rather a platform to get one-on-one programming help from experts. It’s one of my go-to places whenever I am _really_ stuck. You can choose which mentor to work with, all of which set their own price for a 15 minute increment. Read more about my first experience [using CodeMentor here](http://learntocodewith.me/reviews/codementor/) or use this [special link to get $25 in credit](https://www.codementor.io/r/9H5Z7PV4E2) towards your first session.

### Conclusion: Stop Waiting, Start Learning

When it comes to learning something new, it’s best to take action. You can read about “what” to learn all you want. But learning happens when you get your hands hands dirty.

To do a quick recap, above we talked about:

*   How the internet works
*   The difference between the client side and server side
*   Helpful workflow tools that will make your learning experience better
*   And places to start learning

What are you waiting for? **It’s time to take action and start teaching yourself how to code. **

Trust me—acquiring these highly valuable [digital skills will change your life](http://skillcrush.com/2015/01/28/laurence-bradford-10-reasons/). (Just like it has for me.) But it won’t be always be easy. And sometimes it gets really, really frustrating.

However, if I can do it, _you can, too. _

Lastly:

I know how tough it can be to learn alone. But you don’t have to :)

Sign up for the mailing list below, stay in touch, and join the LTCWM community.
