# Bloom-Perf.github.io


This repository hosts the official website for the Bloom Perf project.

The Bloom Perf Project is a collaborative initiative developed by a team of experienced engineers specializing in information system performance. This initiative was born from the need to share innovative and effective approaches in conducting performance tests on complex and distributed systems.


# Website management

## Algolia

The site's search function is provided by [**Algolia**](https://www.algolia.com/).

The site is indexed using ```jekyll-agolia```. This plugin is obsolete and no longer maintained by Algolia, but fortunately, it still works! Have a look to the [jelyll-agolia GitHub repository](https://github.com/algolia/jekyll-algolia).

To update the site's indexing, simply execute the following command line at the root of the web site's git repository:
````bash
ALGOLIA_API_KEY='admin_api_key' bundle exec jekyll algolia
````

## SEO Tags

By default, SEO tags are not managed by Minimal Mistakes template. So, we use [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) to handle metadata SEO Tags for Google search engines.

Just follow instructions belows, and you're ready to go:
  - How to install Jekyll SEO Tag : [jekyll-seo-tag installation guide](https://github.com/jekyll/jekyll-seo-tag/blob/f449b1af64cbaf9080e7a3c677090cfe6e8f0021/docs/installation.md).
