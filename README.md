# doorsinpoetryandhistory

Basic static website for the book, "Burning the May Tree: The Sacrifice of Jim Morrison".

## Develop

Note: A modernizr script has been added to show webp on supporting browsers, and fall back to
other older image types where not supported.  The script checks browser support for webp
(basic, lossless, etc) and based on that, sets a css class on the top-level html tag.
Html "picture" tags are used instead image tags. If adding a webp image, check compression
settings; currently this site using 50%.
