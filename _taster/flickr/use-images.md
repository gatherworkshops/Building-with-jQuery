## Use the actual images

We're generating the HTML correctly, but not linking to the image.

We need to modify our generated HTML:

    htmlString += '<a href="' + bigImageLink + '" data-lightbox="gallery">';
    htmlString += '<img src="' + bigImageLink + '">';
    htmlString += '</a>';


Note: 

This is called string concatenation. We are joining together some individual pieces of text using the "plus" sign.