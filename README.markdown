CoffeeScript Coda plug-in
===================

This provides Coda plugin support for  P. Lutus' RBeautify [http://www.arachnoid.com/ruby/rbeautify.rb.html](http://www.arachnoid.com/ruby/rbeautify.rb.html).

Contains the following commands specific to the current file:

*Compile - compiles the CoffeeScript and opens the JavaScript result in a new file
*Compile and Run - compiles the CoffeeScript and opens the JavaScript result in Coda "Preview" inside <script></script> tags. Console output should be shown.

Prerequisites
-------------

-Node.js (http://nodejs.org/)[http://nodejs.org/]

-CoffeeScript (http://jashkenas.github.com/coffee-script/#installation)[http://jashkenas.github.com/coffee-script/#installation]



Installation
------------

To install via Git:

		mkdir -p ~/Library/Application\ Support/Coda/Plug-ins
		cd ~/Library/Application\ Support/Coda/Plug-ins
		git clone git@github.com:parkerl/CoffeeScript.codaplugin.git

Then restart Coda.

Source can be viewed or forked via GitHub: [https://github.com/parkerl/CoffeeScript.codaplugin](https://github.com/parkerl/CoffeeScript.codaplugin)

Author
------

Coda plugin by [Lew Parker](http://github.com/parkerl)
