# SCALA-LANG.ORG

This repository contains the _static_ source of [scala-lang.org](http://scala-lang.org). It does not contain the source of any content found under the [docs.scala-lang.org](http://docs.scala-lang.org) subdomain (instead, visit the [scala.github.com repo](http://github.com/scala/scala.github.com) for that source).

It's a static site generated by [Jekyll](https://github.com/mojombo/jekyll), and uses a whole host of open-source tools including a touch of Twitter's Bootstrap.

## Dependencies

You'll need Jekyll installed to generate and test the site. To get it, most people can install via RubyGems:

    gem install jekyll

OSX users might have to update RubyGems:

    sudo gem update --system

If in doubt, head over to the [Jekyll wiki](https://github.com/mojombo/jekyll/wiki) for installation instructions.

## Building

After cloning, cd into the `scala/scala-lang` directory and run: 

    jekyll --server

To see the generated site, just visit `http://localhost:4000`.