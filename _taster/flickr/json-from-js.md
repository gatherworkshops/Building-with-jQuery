## Loading JSON from JavaScript

In your script.js, start by creating a variable to store our API endpoint:

    var query = "http://www.flickr.com/services/feeds/photos_public.gne?tags=rabbit&format=json&jsoncallback=?";

    var mycallback = function (data) {
        console.log('success');
        console.log(data);
    }

    $.getJSON(query, mycallback);

Note:

This is a long one so you might want to copy and paste it!