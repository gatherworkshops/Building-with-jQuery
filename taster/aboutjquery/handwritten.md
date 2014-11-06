## Handwritten jQuery

Can be used to modify a single element:

    $('#pageTitle').css('color', 'white');

Or to modify a whole lot of elements in the same way:

    $('img').each( function() {

        this.width(100);

    });


Note:

When jQuery is handwritten, it is used to modify objects on the page.

For example, the first piece of code makes the page title white.

The second piece of code gets all the images on the page, then loops through them and sets them all to 100px wide.