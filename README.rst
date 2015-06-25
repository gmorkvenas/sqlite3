=====
About
=====

This is a snaphost of sqlite 3.8.8.3 from http://sqlite.org together with cmake
build script.
Added text in branch.
Another text

Build on Linux
==============

::

	$ mkdir -p build && cd build && cmake .. && make


Build on Windows
================

::

	mkdir build
	cd build
	cmake ..
	msbuild.exe sqlite3.sln /property:Configuration=Release
