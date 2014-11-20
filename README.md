Smartboards aims to make managing artboards easier in Sketch.  Gridify is the first plugin 

## Gridify
###### Shortcut: cmd + opt + g

* Aligns artboards to a grid with `100px` gutters
* Renames the artboards based on column (number) and row (letter) [`A00`, `A01`, `B00`, `B01`, `B02`]
* Alphabetizes the artboards in the layers list.

To install, download "`Smartboards`" as a zip file and then add the folder to your Sketch plugin folder (In Sketch 3, choose `Plugins` > `Reveal Plugins Folder`)

Notes: Gridify expects that artboards are the same size (width and height). It also expects that artboards that are meant to be in the same row are aligned on the same Y-axis value.  It doesn't care about the X-axis value.

There's a slightly hidden feature that I use a lot but is hard to describe.  If you place an artboard in between two rows on the Y-axis and run the Gridify, it will create room for a new row by shifting existing rows down by one, and then will rename accordingly.  Imagine you have an artboard that is 10x10 at Y = 1, and another artboard that is 10x10 at Y = 111.  If you place a third artboard where 1 < Y < 111, it will do all of the rest of the heavy lifting for you. 

