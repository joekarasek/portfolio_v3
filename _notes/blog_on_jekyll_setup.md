# What I’m trying to do:

* Create a jekyll project, a blog-aware static site generator

# Notes:

* What is Jekyll?
  * Jekyll is a "simple, blog-aware, static site generator perfect for personal project or organization sites."
  * File-base CMS (You put in simple markdown files, Jekyll turns them into a complete website)
  * Jekyll is the engine behind [https://github.com/jekyll/jekyll](https://pages.github.com/)


* Setting up jekyll
  * Installation is super simple, but there are a few system requirements...
    * [Ruby](https://www.ruby-lang.org/en/downloads/) (including development headers, v1.9.3 or above for Jekyll 2 and v2 or above for Jekyll 3)
    * [RubyGems](https://rubygems.org/pages/download)
    * Linux, Unix, or Mac OS X
    * [NodeJS](https://nodejs.org/), or another JavaScript runtime (Jekyll 2 and earlier, for CoffeeScript support).
    * [Python 2.7](https://www.python.org/downloads/)(for Jekyll 2 and earlier)
    * If you're on a windows machine, [heres some documentation for setting up your system](https://jekyllrb.com/docs/windows/#installation)


  * Install jekyll with the following command:

        ~ $ gem install jekyll


  * I got a permission issue the first time I attempted this, I got around it by using the sudo command.

        ~ $ sudo gem install jekyll

  * Finally to create a jekyll project, use the following command:

        ~ $ gem install jekyll
        ~ $ jekyll new myblog
        ~ $ cd myblog
        ~/myblog $ jekyll serve
        # => Now browse to http://localhost:4000

  * This will set you up with the basic template for a jekyll site
    * Find more information on installation at [Jekyll Installation](https://jekyllrb.com/docs/installation/)
    * Note: You can also clone the jekyll repo from github, but this will give you the latest, development version of the software that may be unstable. Using gem to install is safer.

# Resources

[Jekyll on Github](https://github.com/jekyll/jekyll)

[Jekyll Installation](https://jekyllrb.com/docs/installation/)
