# SHAD @ Mac News Website

Hey there! This is the GitHub project for the SHAD @ Mac News team. It features a robust headline system, news updates, a picture of the day, and other information. It was used at SHAD @ McMaster 2016 Campus, by the SHAD @ Mac News team. The site was primarily designed by Matthew Wang [(@malsf21)](https://github.com/malsf21/).

This website was built with [Jekyll](http://jekyllrb.com), [Bootstrap](http://getbootstrap.com), [Font Awesome](fontawesome.io), and other web technologies in combination with those core elements.

## Setup

Setup is pretty easy:

Want to run your own copy of this jekyll site? No problem. You'll need a few things:

* [Ruby](https://www.ruby-lang.org/en/), to install [Jekyll](https://jekyllrb.com)
* [Jekyll](https://jekyllrb.com), to build and run the website
* [Git](https://git-scm.com/), to clone this repository
* A Browser, to view the website of course!

First things first, we need to install Jekyll. We assume that you have Git and Ruby installed. If you don't, please visit the links above to install them. We also assume you're using a [Unix-based system](https://en.wikipedia.org/wiki/Unix); if you aren't, follow jekyll's alternatives instruction page.

Type in your command line:
```
gem install jekyll
```

After Jekyll completes its setup, clone the git repository:
```
git clone https://github.com/malsf21/shad-news.git
```

Then, cd into the repository:
```
cd shad-news
```

Inside the repository, all you'll need to do is "serve" the site. Type the following into your command line:
```
jekyll serve
```

After that, you should get a response that looks something like this:

```
jekyll serve
Configuration file: /var/www/html/shad-news/_config.yml
            Source: /var/www/html/shad-news
       Destination: /var/www/html/shad-news/_site
 Incremental build: disabled. Enable with --incremental
      Generating... 
                    done in 0.179 seconds.
 Auto-regeneration: enabled for '/var/www/html/shad-news'
Configuration file: /var/www/html/shad-news/_config.yml
    Server address: http://127.0.0.1:4000/shadnews/
  Server running... press ctrl-c to stop.

```
