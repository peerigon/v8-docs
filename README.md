About
=====

This project is intended to be an up-to-date reference for developers using the [Google v8](http://code.google.com/p/v8/)
api. The reference is automatically created by [doxygen](http://www.stack.nl/~dimitri/doxygen/).

**This is not the official v8 repository. The v8 is not ours, it's an open-source project developed by Google.**

Contribute
----------

**Please**: If you find this reference out-dated don't hesitate to create a pull-request:

1. Fork the project
2. `git clone https://github.com/<your username>/v8-docs.git`
3. `git checkout gh-pages`
4. `git submodule init`
5. `git submodule foreach git pull`
6. `doxygen`

[doxygen](http://www.stack.nl/~dimitri/doxygen/) automatically pulls the `Doxyfile` and generates the docs. If
you don't have [doxygen](http://www.stack.nl/~dimitri/doxygen/): There are ready-to-use binaries for
[every major platform](http://www.stack.nl/~dimitri/doxygen/download.html).

Disclaimer
----------

