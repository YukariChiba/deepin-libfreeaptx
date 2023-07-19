% freeaptxdec(1) | User Commands
%
% "October 15 2021"

# NAME

freeaptxdec - aptX decoder utility

# SYNOPSIS

**freeaptxdec** [**options**]

# DESCRIPTION

This utility decodes aptX or aptX HD audio stream
from stdin to a raw 24 bit signed stereo on stdout

When input is damaged it tries to synchronize and recover

Non-zero return value indicates that input was damaged
and some bytes from input aptX audio stream were dropped

# OPTIONS

The program follows the usual GNU command line syntax, with long options
starting with two dashes (`-'). A summary of options is included below.

**-h**, **\-\-help**
:   Display this help

**\-\-hd**
:   Decode from aptX HD

# BUGS

The upstream BTS can be found at https://github.com/iamthehorker/libfreeaptx/issues/new.

# SEE ALSO

**freeaptxenc**(1)

# AUTHOR

Kentaro Hayashi <kenhys@xdump.org>
:   Wrote this manpage for the Debian system.

# COPYRIGHT

Copyright © 2021 Kentaro Hayashi

This manual page was written for the Debian system (and may be used by
others).

Permission is granted to copy, distribute and/or modify this document under
the terms of the GNU General Public License, Version 2 or (at your option)
any later version published by the Free Software Foundation.

On Debian systems, the complete text of the GNU General Public License
can be found in /usr/share/common-licenses/GPL.
