Farabi
======

This is a modern web-based Perl IDE that runs inside your favorite browser.

To start Farabi, please type the following command:

    farabi daemon

Open http://127.0.0.1:3000/ in your favourite modern browser.


To run it on a different port, please use:

    farabi daemon --listen "http://*:3030"

Installation
============

To install this module, run the following commands:

    perl Makefile.PL
    make
    make test
    make install

Support and Documentation
=========================

After installing, you can find documentation for this module with the
perldoc command.

    perldoc Farabi

You can also look for information at:

    Project issue list:
	https://github.com/azawawi/farabi/issues

    AnnoCPAN, Annotated CPAN documentation
        http://annocpan.org/dist/Farabi

    CPAN Ratings
        http://cpanratings.perl.org/d/Farabi

    Search CPAN
        http://search.cpan.org/dist/Farabi

Copyright and License
=====================

Copyright (C) 2012-2013 Ahmad M. Zawawi

This program is free software; you can redistribute it and/or modify it
under the same terms as Perl itself.
