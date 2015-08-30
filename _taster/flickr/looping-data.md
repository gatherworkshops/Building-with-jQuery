## Looping Data

We know we are receiving the data, so now we need to loop through it.

We need to know the url of each image, so let's try printing that.

    $.each(data.items, function(i,item){
        var imageLink = item.media.m;
        var bigImageLink = imageLink.replace("_m.jpg", "_b.jpg");
        console.log(imageLink);
        console.log(bigImageLink);
    });


Note:

You can delete the previous two `console.log()` lines, as they may get in the way.