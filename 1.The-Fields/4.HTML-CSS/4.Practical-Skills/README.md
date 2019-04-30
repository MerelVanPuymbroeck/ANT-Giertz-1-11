# Welcome to practical skills !

Here we consider some of the more practical implications of being a web developer, 
from soft skills to additional hard coding skills you need to posess if you want to publish sites.

## Developer console

When making a website, program or app you need to have good debug tools. The browser fills this in by giving you the developer console. It features a ton of handy features like contract ratio, color selectors, live css editing, javascript breakpoints, automatic testing and so much more.

### How to open

Most browser allow you to open the console using the F12 key. If you can't get it to work, lookup the correct shortcut for your browser.

### Select element

A very important tool is the select element tool. It allows you a quick overview of the structure of your website and allows you to quickly lookup an element in your html. When you click an element, it will show you the active CSS rules and allows you to edit them.

### Check the color contrast

When you have selected an element in chrome and enter color selection mode for it's `color` property, chrome will tell you the contrast ratio. When it is too low it will show a stop sign that you can click for more informtation.

### Network tab

In the network tab you can see all the resources the browser loads, like the html page, the css file, the javascript file, images, ... it is a very handy debug tool for when something does not seem to load in.

### And much more

Be sure to explore everything, click around, lookup tutorials, because these tools make your life a lot easier and will save you a lot of time.

## Validators/linters/hinters

When you write html, css or javascript there are automatic programs that will give you hints before you even run your code. Try a few and throw some of your code in. Look at the errors/warnings it gives and try to figure out why it happens and why it is important to do it right.

## (Google) analytics

Want to know how many people are visiting? Where they are from? How long they stay on? How many there are RIGHT NOW? Then you can use services like google analytics who will tell you. You just copy and paste a short bit of code and it will perform all the magic.

## CDN/Cloudflare

When your site is under heavy load because of an attack or because you have a lot of visitors, you can use a service like cloudflare. Look up what a CDN is and why you can use it.

## SEO

What is SEO, **S**earch **E**ngine **O**ptimisation.
This is a very important concept. There are a lot of rules google uses to define whether
your website should be a top result or a `page 50 disaster link`.

Discovering these rules is a long adventure, one that keeps repeating itself. Some rules change yearly, some never.
From now on, every website we create, we will run a SEO analyzer tool on.


This [tool](https://www.seotesteronline.com/) is free, if you post the URL in here from any of the webpages you have created, it will run 
a check on that page's SEO score. As long as the score is below 75%, you'll have to keep reading what is wrong and why, fix it and rerun the tool.

An assignment will only count as **`Done`** if every page gets the minimum score of 75%.



## SEA

What is SEA **S**earch **E**ngine **A**dvertising.

Usually when companies want to make sure they get your first click, they pay for it.
Imagine you want to buy a new laptop, let's just type `buy laptop` in google, this is what you get :

![Search result for 'buy laptop'](https://i.imgur.com/sb1bQZ5.png)

You can see that the first two website that pop up have `ad` written next to the green url, 
this tells us that the main reason they are present there is because they paid for it.
The same counts for the stores that paid for their top products to be listed on the right.

Google uses an AI to determine where to stop with ads and where to start giving you the top `(unpaid)` results.
