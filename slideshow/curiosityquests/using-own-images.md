## Using your own images

Use an `img` tag just like you would normally, but the URL to the images is just the folder path to your image.

    <img src="images/imagename.jpg">

You can also use images the same way in your CSS:

    html {
        background-image: url('images/backgrounds/puppies.jpg');
    }

Pay attention to the spelling of your image file name - it has to match exactly! 



Note:
Once you've added some images to your `images` folder, it's really easy to use them in your website.

Notice that we don't need the `http://` part of the image URL when we are using our own image?

That is because the image is what we call "local" - it is in the same place on the web as our HTML files where we are accessing the image from.

This is a bit like calling telephone numbers in your own city and not needing to add an international calling code before the phone number.

Pro Tip: Keep an eye on your spelling! The spelling of the image path needs to be exact. That includes _UPPERCASE_ and _lowercase_ letters. It also includes the file extension, which is the bit after the dot like `.jpg` or `.png`.