# Welcome to the Streamline Foundation plugin #

Streamline Foundation is a plugin for [Streamline](http://code.google.com/p/streamline/), a PHP/Javascript based web application framework.

## About this plugin ##
Many plugins and websites seek to implement similar functions. In addition many of these functions are so basic, or so close to the heart of any website that they should be available to every website and every plugin built with Streamline. Things like a login form, AJAX support or HTTPStream support are among these things.

It would be silly if every plugin would have to implement these functions themselves. It makes sense to distribute these functions in some form along with every basic Streamline installation. At the same time, they are not actually required for the operation of the very core of Streamline (the management of plugins, events, multilanguage support, etc).

To separate development, to keep the core of Streamline lean and mean, these functions  are maintained in a separate plugin. That is why Streamline Foundation exists: to provide a single place to make common functions available to plugins, without cluttering the core of Streamline. This encourages keeping the core lean and mean while Streamline Foundation can be developed specialized as a library of common functions.

## About Streamline ##
Streamline is a PHP/Javascript web application framework designed to quickly build web applications and web sites. It was designed so you can use it just as easily for publishing (like blogs and news sites), for support applications (project management, issue tracking), community (e.g. a facebook application) or anything else (for instance a telephony management application). Streamline uses plugins which can be used, mixed and extended on the same page without writing a line of code.

Visit the Streamline website [here](http://www.phpStreamline.org).
Visit the Streamline development trunk at Google Code [here](http://code.google.com/p/streamline).