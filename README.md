Sample Weinre Extension
=======================

A sample extension for [weinre](http://pmuellr.github.com/weinre/).

Install
=======

    mkdir ~/.weinre
    mkdir ~/.weinre/extensions
    cd ~/.weinre/extensions    
    git clone git@github.com:pmuellr/weinre-ext-sample.git
    (restart your weinre server)
    
Programming
===========

Extensions are folders stored in your `~/.weinre` direction.
Each folder is a different extension.
Each extension should have a file included in it's base
directory named `extension.html`.

To get access to the Web Inspector programming API, you
should include the following file in your `extension.html`
and any other `.html` files you use which need the API.

    <script src="../../web-inspector-API.js"></script>

To see what's available in the API, unzip a `weinre.jar` file,
and read the extract file `web/client/ExtensionAPI.js`.
Good luck, Jim.

License
=======

The files are available under *either* the terms of the modified BSD license *or* the
MIT License (2008). See http://opensource.org/licenses/alphabetical for full text.

Copyright (c) 2011 IBM Corporation (everything else)