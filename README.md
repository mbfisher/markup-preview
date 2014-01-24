markup-preview
==============

Simple Rack server rendering markup files to HTML.

Uses [Andy Ferra's Gist](https://gist.github.com/andyferra/2554919) to apply
a GitHub theme.

Usage
=====

Start the server:

    $> markdown-preview
    Thin web server (v1.6.1 codename Death Proof)
    Maximum connections set to 1024
    Listening on 0.0.0.0:9292, CTRL+C to stop

Then visit `http://localhost:9292/path/to/markup`.

Pass a directory to `markdown-preview` to use as a document root...

    $> markdown-preview ~/git-projects

... `http://localhost:9292/markdown-preview/README.md` will render
`~/git-projects/markdown-preview/README.md`.
