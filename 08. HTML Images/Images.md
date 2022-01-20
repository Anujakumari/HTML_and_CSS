# HTML Images
Images can improve the design and the appearance of a web page.

## HTML Images Syntax
**The HTML `<img>` tag is used to embed an image in a web page.** <br>
Images are not technically inserted into a web page; images are linked to web pages. The `<img>` tag creates a holding space for the referenced image. <br>
The `<img>` tag is empty, it contains attributes only, and does not have a closing tag. <br>

**The `<img>` tag has two required attributes:**

- `src` - Specifies the path to the image
- `alt` - Specifies an alternate text for the image
<br>

The required `alt` attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the `src` attribute, or if the user uses a screen reader). <br>

## Image Size - Width and Height
we can use the `style` attribute to specify the width and height of an image.

## Example
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Images</title>
</head>
<body>
    <img src="pic_mountain.jpg" alt="Beautiful Mountain view" style="width:700px;height:400px;">
</body>
</html>
```

## Output

![HTML_Images](https://github.com/Anujakumari/HTML_and_CSS/blob/master/img/Html_Image.png)

## Common Image Formats

Here are the most common image file types, which are supported in all browsers (Chrome, Edge, Firefox, Safari, Opera):

| Abbreviation |	File Format |	File Extension |
| ------------ | -------------| -------------- |
| APNG | 	Animated Portable Network Graphics	| .apng |
| GIF	| Graphics Interchange Format |	.gif |
| ICO |	Microsoft Icon	| .ico, .cur |
| JPEG | Joint Photographic Expert Group image	| .jpg, .jpeg, .jfif, .pjpeg, .pjp |
| PNG	| Portable Network Graphics | .png |
| SVG	| Scalable Vector Graphics	| .svg |
