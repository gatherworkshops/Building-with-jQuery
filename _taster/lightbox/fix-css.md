## Fix the CSS

The images are broken!

The CSS is trying to link to the icons in an images folder.

In `lightbox.css` instead of:

    url('img/next.png')

You just want:

    url('next.png')



Note:

This is optional! It does work without.