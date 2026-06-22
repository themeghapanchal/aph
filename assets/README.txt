IMAGE NEEDED
============

The Visual Design page expects an image at:

    assets/dont-look-back.png

That's the "Don't Look Back" colorful typography illustration you wanted in
the hero section. Save it here as a PNG and the hero will pick it up
automatically.

Background note
---------------
The image you shared has a light grey background. The website page is
cream, so the two don't match exactly. Two options:

  1) Easy way: drop the file in as-is (PNG or JPG). The CSS uses
     mix-blend-mode: multiply, which blends the grey backdrop into the
     cream page so it mostly disappears. The colored letters stay vivid.

  2) Cleaner way: remove the background first so the image has a
     transparent background, then save as PNG. Free tools:
       - remove.bg
       - photoroom.com
       - Canva's background remover

Either works. Once the file is at assets/dont-look-back.png the hero
will display it. Refresh the page to see it.
