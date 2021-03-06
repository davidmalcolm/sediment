.. Copyright 2011 David Malcolm <dmalcolm@redhat.com>
   Copyright 2011 Red Hat, Inc.
   Copyright 2013 Red Hat, Inc.

   This is free software: you can redistribute it and/or modify it
   under the terms of the GNU General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful, but
   WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
   General Public License for more details.

   You should have received a copy of the GNU General Public License
   along with this program.  If not, see
   <http://www.gnu.org/licenses/>.

.. gcc-python-plugin documentation master file, created by
   sphinx-quickstart on Wed Jun  1 15:53:48 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Sediment Function Reordering Tool
=================================

.. toctree::
   :maxdepth: 2


This set of documents describe the Sediment function reordering tools.
These tools allow the functions to be ordered while building the
executable to reduce instruction TLB and page misses.
Details about the implmentation and experimental results are in the
:doc:`Sediment Principles of Operation manual </pop>`.

Man pages
=========
* :doc:`perf2gv </perf2gv>`
* :doc:`gv2link </gv2link>`
* :doc:`gen_profile_merge </gen_profile_merge>`

Sediment is a work-in-progress; the things may well change.


Sediment is Free Software, licensed under the GPLv3 (or later).


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

