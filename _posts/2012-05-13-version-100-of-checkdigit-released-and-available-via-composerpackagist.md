---
layout: post
title: "Version 1.0.0 of checkdigit released and available via composer/packagist"
description: "Version 1.0.0 of checkdigit released and available via composer/packagist"
category: Tech
tags: [php, checkdigit]
---
{% include JB/setup %}

I have just pushed version 1.0 of my new checkdigit library to github 
and submitted it to packagist/composer so that it's nice and easy to
install.

You can view the package and it's install instructions over on [packagist][Packagist]
or alternately you can browse the source and do a git checkout on [github][GitHub].

Currently it supports validating the checkdigits on Australian Business Numbers
as well as Credit Card numbers using the Luhn algorithm.

It should be pretty well tested and you can monitor the build status on [travis][Travis]
to see how it's going for new releases.

If you notice anything I have nubbed up in my use of packagist please do let me
know, alternately if there's a checkdigit format that you really want covered please
drop me a line and I would be happy to look into it.

Matt

[Packagist]: http://packagist.org/packages/afoozle/checkdigit
[GitHub]: https://github.com/afoozle/checkdigit
[Travis]: http://travis-ci.org/#!/afoozle/checkdigit
