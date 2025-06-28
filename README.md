[![Actions Status](https://github.com/Raku-L10N/NL/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/NL/actions) [![Actions Status](https://github.com/Raku-L10N/NL/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/NL/actions) [![Actions Status](https://github.com/Raku-L10N/NL/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/NL/actions)

NAME
====

L10N::NL - Dutch localization of Raku

SYNOPSIS
========

    $ dutku -e 'zeg "Hallo Wereld"'
    Hallo Wereld

```raku
use L10N::NL;
zeg "Hallo wereld";
```

DESCRIPTION
===========

The `L10N::NL` distribution contains the logic to provide a Dutch localization of the Raku Programming Language. It installs a `dutku` executable that will automatically activate the Dutch localization. And it allows one to use the Dutch localization in selected programs with a `use L10N::NL` statement.

AUTHORS
=======

Elizabeth Mattijsen <liz@raku.rocks>

COPYRIGHT AND LICENSE
=====================

Copyright 2023, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

