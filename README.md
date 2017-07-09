##### *UNDER DEVELOPMENT*

# RGB-Randomly-Generated-Buttons
Create Markdown button images to link to anything.

## Two approaches:

### Taking advantage of route params:
```
/create/a
/:width/by/:height/image
/with/:textcolor/text/that/says/:text
/with/border/color/:bordercolor
/using/thumbnail/:thumbnailurl
/image.png
```

### As an API:
##### Query params:
* width - the width of the image
* height - the height of the image
* textColor - the color of the text
* text - the text on the button
* borderColor - the color of the border
* thumbnailUrl - the url of the image that will go to the left of the text

## A Visual aid of what I'm talking about:

![visual aid](http://i.imgur.com/uFxKQo5.png)

## Why do this?

Consistancy is really nice. Take a look at this repo:
https://github.com/mtntop/mtnbot/blob/master/README.md#current-platforms

It looks TERRIBLE because all of the images were different sizes and when they were made the same size, some became pixelated.

I want there to be a really simple programmatic way of creating these images.
