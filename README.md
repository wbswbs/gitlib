Git lib for Gitonomy
====================

[![Build Status](https://secure.travis-ci.org/gitonomy/gitlib.png)](https://travis-ci.org/gitonomy/gitlib)

This branch was forked from the original repository, to fix the Problems
with the Symfony Process Versions.  

The Branch ist dev-wbs

To load it with composer add

  "repositories": [
      {
        "type": "git",
        "url": "https://github.com/wbswbs/gitlib/"
      }
    ],
    
and require
    
    "gitonomy/gitlib":"dev-dev-wbs",


This library provides methods to access Git repository from PHP.

It makes shell calls, which makes it less performant than any solution.

Anyway, it's convenient and don't need to build anything to use it. That's how we love it.

*Documentation*: http://gitonomy.com/doc/gitlib/master/
