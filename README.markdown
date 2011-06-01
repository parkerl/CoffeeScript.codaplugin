CoffeeScript Coda plug-in
===================

Contains the following commands specific to the current file:

* Compile - compiles the CoffeeScript and opens the JavaScript result in a new file
* Compile and Run - compiles the CoffeeScript and opens the JavaScript result in Coda "Preview" inside <script></script> tags. Console output should be shown.
* Compile and Run with JQuery - compiles the CoffeeScript and opens the JavaScript result in Coda "Preview". Creates a skeleton page with jQuery included from the package source in the <head>. The current version is **jquery-1.6.1.min**.

  Here is a sample of the output:
  
    jQuery ->
    $('body').prepend "<p>Hot Coffee!!</p>"
  
  compiles to:
  
    <html>
    <head>
    <script src="file://///Users/XXXXX/Library/Application Support/Coda/Plug-ins/CoffeeScript.codaplugin/Contents/Resources/D045B81C-A3ED-47B1-A5E7-3C2216B695EA/Support Files/jquery-1.6.1.min.js">
    </script>
    </head>
    <body>
    <script>
    (function() {
      jQuery(function() {
        return $('body').prepend("<p>Hot Coffee!!</p>");
      });
    }).call(this);
    </script>
    </body>
    <html>
  
  

Prerequisites
-------------

- Node.js http://nodejs.org/

- CoffeeScript http://jashkenas.github.com/coffee-script/#installation



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
