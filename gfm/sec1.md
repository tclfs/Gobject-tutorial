Up: [Readme.md](../Readme.md),  Next: [Section 2](sec2.md)

# Prerequisites and License

## Prerequisites

### Tutorial document

This tutorial is about GObject libraries.
It is originally used on Linux with C compiler, but now it is used more widely, on windows and macOS, with Vala, python and so on.
However, this tutorial describes only _C programs on Linux_.

If you want to try to compile the examples in the tutorial, you need:

- PC with Linux distribution like Ubuntu, Debian and so on.
- Gcc
- GLib. The version at the time this document is described is 2.74.0, but earlier version may work.
- pkg-config
- meson and ninja

Common Linux distributions has GLib, which is enough for you to compile the examples in this repository.

### Tools to make GFM, HTML and PDF files

This repository includes ruby programs.
They are used to create Markdown(GFM) files, HTML files, LaTeX files and a PDF file.

You need:

- Linux distribution like Ubuntu.
- Ruby programming language.
There are two ways to install it.
One is installing the distribution's package.
The other is using rbenv and ruby-build.
If you want to use the latest version of Ruby, you might need to use rbenv and ruby-build.
- Rake.
It is a gem, which is a library written in ruby.
Ruby package includes Rake gem so you don't need to install it separately.

## License

Copyright (C) 2021-2022  ToshioCP (Toshio Sekiya)

GObject tutorial repository contains the tutorial document and software such as converters, generators and controllers.
All of them make up the 'GObject tutorial' package.
This package is simply called 'GObject tutorial' in the following description.
'GObject tutorial' is free; you can redistribute it and/or modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.

'GObject tutorial' is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.html) for more details.


Up: [Readme.md](../Readme.md),  Next: [Section 2](sec2.md)
