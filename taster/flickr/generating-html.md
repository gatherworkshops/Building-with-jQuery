## Generating HTML

We've got links to our images, but to use them on our page we'll need to convert them into HTML.

Before your loop, create a String to store our HTML:

    var htmlString = '';

Inside your loop, create some HTML:

    htmlString += '<a href="image.jpg" data-lightbox="gallery">';
    htmlString += '<img src="image.jpg">';
    htmlString += '</a>';



Note:

We're recreating the HTML we hard-coded earlier, but from JavaScript.