# Patterns of Code As Media, Andrew Odewahn

This is a catalog of sites where code is a media object in and of its
own right. We’re not interested so much in the code itself (i.e., does
it work, how does it perform, etc), but how do we communicate **about**
code: what are the best ways to see, learn, and understand a topic.
People are learning in new ways, and we want to understand the patterns
that are emerging.

## Contributing

This book is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).  I encourage you to fork my work and make your own improvements under the terms of the license. If you have any changes you want to send back our way, please make a regular pull request via Github. If the authors like your changes, they may integrate them into the official repo and give you a credit. If you just have an issue to report, please use the regular Github issue system.


## Running the site locally

The site uses [harpjs](http://harpjs.com/) to build a site and [Atlas](https://atlas.oreilly.com/) to build the PDF, mobi, and epub.  To build the site:

* [Install harp](http://harpjs.com/docs/quick-start).  
* Clone the repo
* Run `harp server --port 4567`

When you want to build the site, clone the repo down again into another directory, create a gh-pages branch, and then run `harp compile . _new directory_`
