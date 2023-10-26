# Web Scraper Python

Simple overview of use/purpose. Web scraping means extacting data from the “web”. However, web is not just an anonymous internet “out there” but a conglomerat of servers and sites, built and maintained by individuals, businesses and governments. Extracting data from there inevitably means using the resources and knowledge someone else has put into the websites.

## Description

Build a web scraper with Python and BeautifulSoup

## Getting Started

### Dependencies

* [](https://pypi.org/project/requests/), [](https://beautiful-soup-4.readthedocs.io/en/latest/)

### Installing

* [](https://zerotomastery.io/courses/learn-python/)

### Executing program

* pip3 install requests- pip3 install beutifulsoup4
* Step-by-step bullets
```Beautiful Soup 4 is published through PyPi, so if you can’t install it with the system packager, you can install it with easy_install or pip. The package name is beautifulsoup4, and the same package works on Python 2 and Python 3. Make sure you use the right version of pip or easy_install for your Python version (these may be named pip3 and easy_install3 respectively if you’re using Python 3).

$ easy_install beautifulsoup4

$ pip install beautifulsoup4

(The BeautifulSoup package is probably not what you want. That’s the previous major release, Beautiful Soup 3. Lots of software uses BS3, so it’s still available, but if you’re writing new code you should install beautifulsoup4.)

If you don’t have easy_install or pip installed, you can download the Beautiful Soup 4 source tarball and install it with setup.py.

$ python setup.py install

If all else fails, the license for Beautiful Soup allows you to package the entire library with your application. You can download the tarball, copy its bs4 directory into your application’s codebase, and use Beautiful Soup without installing it at all.

I use Python 2.7 and Python 3.2 to develop Beautiful Soup, but it should work with other recent versions.code blocks for commands
```

## Help

Any advise for common problems or issues.
```If you get the ImportError “No module named html.parser”, your problem is that you’re running the Python 3 version of the code under Python 2.

In both cases, your best bet is to completely remove the Beautiful Soup installation from your system (including any directory created when you unzipped the tarball) and try the installation again.

If you get the SyntaxError “Invalid syntax” on the line ROOT_TAG_NAME = u'[document]', you need to convert the Python 2 code to Python 3. You can do this either by installing the package:

$ python3 setup.py install

or by manually running Python’s 2to3 conversion script on the bs4 directory:

$ 2to3-3.2 -w bs4command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Billy McDavid  
ex. [@Machinebrains2](https://twitter.com/mcdavidw845)

## Version History

This document covers Beautiful Soup version 4.8.1. The examples in this documentation should work the same way in Python 2.7 and Python 3.2.
## License

This project is licensed under the satoshimasterbilly] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://zerotomastery.io/courses/learn-python/)
* [BeautifulSoup4](https://beautiful-soup-4.readthedocs.io/en/latest/#quick-start)
* [webscrapingadd-ons](https://faculty.washington.edu/otoomet/machinelearning-py/web-scraping.html)
* [hacker-news](https://news.ycombinator.com/)
  
