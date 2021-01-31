# Overview
Content warnings (and trigger warnings) are used to alert people of potentially distressing content so that they can appropriately prepare or disengage themselves.

## Purpose
By implementing the content-warnings meta tag, website publishers can mark their own webpages with content warnings to make the internet more inclusive and safe.

## Handling
In terms of handling these content warnings, functionality could be built into a browser (or browser extension) to display relevant content warnings before rendering the page’s contents to the user. Search engines, social media platforms, and other locations ripe with outgoing links could also implement content warnings for outgoing content based on this meta tag.

## Implementation
<meta> tags always belong inside the <head> element of HTML documents. For the content-warnings <meta> tag, the value of the name attribute is "content-warnings," and the value of the content attribute is a comma-separated list of relevant content warning(s). Implementation is similar to the meta keywords tag, which is nowadays irrelevant in terms of SEO.

See [example.html](example.html) for an example implementation.

## License: [Creative Commons Zero v1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)
