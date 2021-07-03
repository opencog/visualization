
Graphics and Visualization Tools
--------------------------------

This repository has been archived. The three tools below have not been
updated since 2008, and depend on APIs that no longer exist. The things
that they did were not very sophisticated; it would take you ''less''
time to write hand-written scripts to export to dotty or tulip,
than it would take for you to figure out how to use this old code.

This does not mean that we don't want or need visualization tools for
the AtomSpace; rather, that the tools here are not useful for that.
If you want to start a new AtomSpace visualization project, let the
mailing list know. We'll create a brand new git repo just for you!

In the meanwhile, there is a web-browser visualizer in

https://github.com/opencog/atomspace-explorer

Its got visual bling!  Unfortunately, it dates to 2017 and depends
on obsolete interfaces that no longer exist. The basic demo works,
but that's all. This project needs a maintainer.

The visualization tools in this git repo are:

* dotty      -- build a dotty graph of the entire atomspace
* gtk-vistualizer -- use gtk3 to visualize
* tulip      -- dump the AtomSpace to the Tulip tlp graph format
