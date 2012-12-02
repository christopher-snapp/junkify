JUNKIFY
========

:Author: Christopher A. Snapp <snappca@gmail.com>
:Version: 12.12
:Copyright: GPLv3

**junkify** highly randomized file and directory generator

.. contents::

Synopsis
--------

**junkify** [**-h**] [**--help**] [**-d** *max_subdirectories*] [**-f** *number_files*] [**-l** *min_name_length*] [**-L** *max_name_length*] [**-s** *max_siblings*] [**-w** *writers*]


Description
-----------
junkify creates a directory structure containing highly randomized content in
files of varying sizes.

The original use case for this script was for prepopulating large storage
containers for initial acceptance testing of metadata performance.


Options
-------
    **-d**
      maximum number of sub-directories

    **-f**
      number of files to generate

    **-h, --help**
      display this help and exit

    **-l**
      minimum number of characters within a file or directory name

    **-L**
      maximum number of characters within a file or directory name

    **-s**
      maximum number of sibling directories

    **-w**
      number of concurrent writers

    **-v**
      display version information and exit


Copyright
---------
Copyright (C) 2012, Christopher A. Snapp <snappca@gmail.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
