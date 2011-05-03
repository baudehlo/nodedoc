Nodedoc
=======

This quick hack module gives you access to node documentation on the
command line.

Installation
------------

First edit the file `nodedoc` and change the value of `NODE_DOC_DIR` in that
file. This is the directory to the `node/doc/api` directory. You can make
a global installation by creating the directory `/usr/local/share/node/doc`
and copying the files there.

Then copy the `nodedoc*` files to somewhere in your path:

    $ sudo cp nodedoc* /usr/local/bin/

Finally, to find documentation for the 'fs' module, type:

    $ nodedoc fs

It's all a bit rough and ready. Patches welcome. It requires a perl and
an nroff installation to work.

Contains code from the [markdown-js][1] project.

[1]: https://github.com/evilstreak/markdown-js
