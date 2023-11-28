# Bloom-Perf.github.io


This repository hosts the official website for the Bloom Perf project.

The Bloom Perf Project is a collaborative initiative developed by a team of experienced engineers specializing in information system performance. This initiative was born from the need to share innovative and effective approaches in conducting performance tests on complex and distributed systems.


# Website management

## Minimal Mistakes template

The bloom perf site runs on Git Pages with Jekyll and the « Minimal Mistakes » theme. Here are several reasons why we have chosen the ['Minimal Mistakes' Jekyll theme](https://mmistakes.github.io/minimal-mistakes/):

  - Simplicity and Elegance: As its name suggests, 'Minimal Mistakes' offers a minimalist design that focuses on content. The [www.bloom-perf.org](https://www.bloom-perf.org) site uses default settings with the 'dark' template.
  - Easy Customization: Although minimalist, the theme allows for extensive customization. We are going to explain below how to add favicon, or implement search function, and so end...
  - Responsive Design: The theme is designed to be fully responsive, meaning it works well on all devices, from desktops to smartphones (in my opinion, it looks better on smartphone).
  - Comprehensive Documentation: 'Minimal Mistakes' comes with detailed documentation that makes setting up and customizing the theme easy (cf. [Quick Start Guide](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)), even for less experienced users (as I was before implementing this site).
  - Integrated Features: It includes numerous features such as pagination, support for comments, social media sharing widgets, and other useful elements for a modern website.
  - Free and Open Source: 'Minimal Mistakes' is available for free and its [source code](https://github.com/mmistakes/minimal-mistakes) is open, allowing adaptations and contributions from the community.

## Algolia

The site's search function is provided by [**Algolia**](https://www.algolia.com/).

The site is indexed using ```jekyll-agolia```. This plugin is obsolete and no longer maintained by Algolia, but fortunately, it still works! Have a look to the [jelyll-agolia GitHub repository](https://github.com/algolia/jekyll-algolia).

To update the site's indexing, simply execute the following command line at the root of the web site's git repository:
````bash
ALGOLIA_API_KEY='admin_api_key' bundle exec jekyll algolia
````

## SEO Tags

By default, SEO tags are not managed by Minimal Mistakes template. So, we use [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) to handle metadata SEO Tags for search engines.

Just follow instructions belows, and you're ready to go:
  - How to install Jekyll SEO Tag : [jekyll-seo-tag installation guide](https://github.com/jekyll/jekyll-seo-tag/blob/f449b1af64cbaf9080e7a3c677090cfe6e8f0021/docs/installation.md).

## favicon

Copy the file [_includes/head/custom.html](https://github.com/mmistakes/minimal-mistakes/blob/8a67ce8e41ec850f2d7c373aa47739b2abfee6f1/_includes/head/custom.html) from the 'Minimal Mistakes' github repositoy to your repository (in the same tree directories).

And use [realfavicongenerator.net](https://realfavicongenerator.net/) to create all favicon pictures and code directives.

This is the custom header file used by the bloom perf website:

````html
<!-- start custom head snippets -->

<!-- insert favicons. use https://realfavicongenerator.net/ -->

<link rel="apple-touch-icon" sizes="180x180" href="/assets/favicons/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/assets/favicons/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/assets/favicons/favicon-16x16.png">
<link rel="manifest" href="/assets/manifests/site.webmanifest">
<link rel="mask-icon" href="/assets/favicons/safari-pinned-tab.svg" color="#5bbad5">
<meta name="msapplication-TileColor" content="#da532c">
<meta name="theme-color" content="#ffffff">

<!-- end custom head snippets -->
````

And files used to implement ```favicon```:

````bash
.
├── _includes
│   └── head
│       └── custom.html
├── assets
│   ├── favicons
│   │   ├── android-chrome-192x192.png
│   │   ├── android-chrome-384x384.png
│   │   ├── apple-touch-icon.png
│   │   ├── favicon-16x16.png
│   │   ├── favicon-32x32.png
│   │   ├── favicon.ico
│   │   ├── mstile-150x150.png
│   │   └── safari-pinned-tab.svg
│   └── manifests
│       └── site.webmanifest
├── browserconfig.xml
└── favicon.ico
````

# Reminder

## How to test localy

At the root of the local web site git repository, just keying the following command:
````bash
$> bundle exec jekyll serve
````
