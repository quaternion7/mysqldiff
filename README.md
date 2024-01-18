MySQL-Diff
==========

MySQL-Diff is a suite of Perl modules and accompanying CLI script
`mysqldiff` for comparing the schemas of two MySQL/MariaDB databases.

This Fork (Quaternion)
---

This fork was made so I can merge some pull requests made by the community but didn't get merged since the contributors don't seem to be active.
Also some changes to fit my needs probably.

Prerequisites
-------------

This suite requires Perl 5.14 or higher and a MySQL compatible suite
of client utilities (mysql and mysqldump). You need at least Perl 5.14
to be able to install the current version of `Dist::Zilla`; however,
the module proper will probably make do with a lesser version.

Availability
------------

This GitHub repo contains the latest code.  The latest released
version of MySQL-Diff used to be available from

- http://adamspiers.org/computing/mysqldiff/

and from the Comprehensive Perl Archive Network (CPAN).  Visit
<http://www.perl.com/CPAN> to find a CPAN site near you.

Installation
------------

See the [`INSTALL.md`](INSTALL.md) file.

Documentation
-------------

- Homepage: http://adamspiers.org/computing/mysqldiff/
- Documentation at CPAN: http://search.cpan.org/dist/MySQL-Diff/

Support
-------

Patches should be sent as pull requests to http://github.com/aspiers/mysqldiff

Please see the [`CONTRIBUTING.md`](CONTRIBUTING.md) file for more
information.

New bug reports and feature requests
------------------------------------

https://github.com/aspiers/mysqldiff/issues

Other known bugs
----------------

See https://rt.cpan.org/Public/Dist/Display.html?Name=MySQL-Diff

License
-------

This program is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

Copyright
---------

(c) 2000-2016 Adam Spiers <mysqldiff@adamspiers.org> and other contributors (as shown
by the git history); all rights reserved.
