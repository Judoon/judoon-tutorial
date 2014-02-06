# Judoon tutorial

A step-by-step guide on how to use Judoon.

The tutorial lives in `tutorial.md`.  Full size images live in
`/img/fullsize/`.  Scaled images live in `/img/` and are generated via
ImageMagick by the following command:

    $ cd img/fullsize
    $ for i in *; do convert $i -resize 40% ../$i; done;

