# ACML 2016

Code for generating the web-based interface for ACML 2016 proceedings
(to be stored in a USB stick).
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

