# Up or Down?

A super-simple sample Android application that uses
http://downforeveryoneorjustme.com to test whether or not a website is
online.

This app is written in Mirah using the Pindah build tool. It
demonstrates the following:

* Basic Mirah syntax for use with Pindah
* How to use blocks and Android callbacks with Mirah
* How to leverage third-party Java libraries in Mirah (jsoup)
* How to handle exceptions in Mirah
* How to deal with Mirah scoping weirdness (this = self)

## Homework Ideas

* Add a ProgressDialog and make the site test an AsyncTask
* Record a log of website test history to a ListView
* Allow users to browse test history through a separate activity
* Store test history in a local Sqlite database (ListAdapter)

## Credits

Copyright (c) 2011 Nick Plante. See LICENSE.txt for further details.
