This *pretty* repo is a collection of footprints I have used with KiCad.
To add this using the Github plugin, simply copy the text in the block below
to your clipboard, then paste that onto your footprint library table editor
in KiCad.


    (fp_lib_table
      (lib
        (name github-test)
        (type Github)
        (uri https://github.com/liftoff-sr/pretty_footprints)
        (options "")
        (descr "Testing of GITHUB_PLUGIN for KiCad, it has some footprints which came from various other libraries on my system.")
      )
    )


* [100-LQFP](https://raw.github.com/liftoff-sr/pretty_footprints/master/100-LQFP.kicad_mod)
This is a 100 pin LQFP that I like when I am wearing a blue shirt and eating pizza.

* [CHP-081TA](https://raw.github.com/liftoff-sr/pretty_footprints/master/CHP-081TA.kicad_mod)
This is a piano key toggle switch I use to hang off the end of a board and set options on a 4.-20 ma input circuit.


ToDo: write a python script which creates a README.md file like this one automatically
from the contents of a pretty directory.  Of particular value are two results:

1. The 'copy and paste text block above' which makes adding libraries easy to the table editor.
2. The footprint specific text, which should be extracted from the description field
of each respective footprint.
