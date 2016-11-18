# ACML 2016 (Proceedings on USB stick)

Code for generating the web-based interface for ACML 2016 proceedings
(to be stored on a USB stick).
Uses [Nikola](https://getnikola.com/) static site generator.

Website/code is released under [CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).


## Nikola

This folder contains the source used to generate a static site using Nikola.

Installation and documentation at https://getnikola.com/

Configuration file for the site is `conf.py`.

When deploying the site, it is output into another directory, which is
defined in the deployment command parameter:

* `DEPLOY_COMMANDS`

To build the site:
```
    nikola build
```

To see it::
```
    nikola serve -b
```

To check all available commands:
```
    nikola help
```

## Content

The articles of the proceedings and program (in PDF format) go in the 
following directory (the articles themselves are not part of the repository):
```
files/pdfs
```

These PDFs are reference from the following page:
```
pages/root/index.rst
```

