# Intro to HTML and CSS

## Requirements

We'll need two things for this lesson. A good text editor and Google Chrome. We're going to standardize the use of Google Chrome for this particular lesson thanks to something called [vendor prefixes](http://css-tricks.com/how-to-deal-with-vendor-prefixes/). However, if Google Chrome isn't your favorite browser, feel free to ask a mentor how you can make your project run in Firefox or other modern browsers.

### Windows

Download and install **Notepad++**

* [http://download.tuxfamily.org/notepadplus/6.1.3/npp.6.1.3.Installer.exe](http://download.tuxfamily.org/notepadplus/6.1.3/npp.6.1.3.Installer.exe)

Download and install **Google Chrome**
* [http://google.com/chrome](http://google.com/chrome)

### Mac OSX

Download and open **Text Wrangler**

* [http://ash.barebones.com/TextWrangler_4.0.1.dmg](http://ash.barebones.com/TextWrangler_4.0.1.dmg)

Download and open **Google Chrome**

* [http://google.com/chrome](http://google.com/chrome)

## What is HTML and CSS?

HTML (Hyper Text Markup Language) and CSS (Cascading Style Sheets) work together to create every webpage you see on the Internet. 

That may sound intimidating at first so let's start out with a real life example. We're going to pretend that I, *a human being*, am a website.

A website is made up of many things. There are tables, forms, navigation bars, paragraphs, headings, and more. 

I'm also made up of many things. I'm wearing a shirt, a pair of shoes, a belt, a pair of pants, maybe even a shirt on top of my shirt. If I were an HTML document, these would be all of my "elements". However, you may notice that my clothes look very different than your own. I probably wear a different size, different colors, different shapes, and maybe they even have different features.  With CSS, we can describe how all of the elements on my "page" should look.

```html
<div class="shirt"> 
John's Shirt
</div>
```

```css
.shirt {
	color: #000000;
	collar-type: button-down;
	pattern: solid;
	size: small;
	button-spacing: 3in;
}
```

The CSS describes all of the things that makes my shirt unique. Just as my shirt probably doesn't look like the one that you are wearing, my website probably doesn't look like your website. 

We all know that you can't code a T-Shirt so let's take a look at what a real website looks like. 

## Using Chrome Developer Tools

