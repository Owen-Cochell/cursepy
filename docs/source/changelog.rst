=========
Changelog
=========

1.3.1
=====

Bug Fixes
---------

* We now properly quote the path section of any URLs given to the URLProtocol

1.3.0
======

This update fixes some major bugs,
and corrects an issue with searching.

Features Added
--------------

* Added the 'set_page()' and 'bump_page()' methods to the SearchParam class, which makes traversing pages easy
* Added the 'Bukkit Plugins' category to the MinecraftWrapper
* The MinecraftWrapper is now imported in the init file, so users can import the class like so:

.. code-block:: python

    from cursepy import MinecraftWrapper

(This will be the case for any new wrappers added)

Bug Fixes
---------

* Fixed an issue in the code and docs where the index is treated as the page of results to retrieve, which is incorrect
* We now download addon files correctly
* We now load reduced dependency info when ForgeSVC handlers are used to retrieve all files for a particular addon
* Fixed the 'iter_search()' method to correctly stop iteration
* Fixed some random typos in the documentation

1.2.0
=====

Features Added
--------------

* We now keep track of dependency info in the new CurseDependency class
* Users can retrieve the file ID as well as the addon ID of the dependency
* Users can retrieve optional and/or required dependencies

1.1.3
=====

Bug Fixes
---------

* Fix search filtering issue

1.1.2
=====

Bug Fixes
---------

* Fix dictionary calling issue

1.1.1
=====

Bug Fixes
---------

* Fixed an issue with sub-modules not being included in distribution files

1.1.0
=====

This update simply adds some basic protocol objects.

Features Added 
--------------

* Added 'TCPProtocol'
* Added 'UDProtocol'

1.0.0
=====

Initial Commit