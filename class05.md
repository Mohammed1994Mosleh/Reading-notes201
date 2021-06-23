# class 05Reading:

## images in html:
To add an image into the page
you need to use an <img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
![image attribute](https://tutorial.techaltum.com/images/html-attributes.jpg)
- src:

This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).

- alt:
This provides a text description
of the image which describes the
image if you cannot see it.
- title
You can also use the title
attribute with the <img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.
- height
This specifies the height of the
image in pixels.
- width
This specifies the width of the
image in pixels.

### Three Rules for Creating Images:
1. Save images in nthe right format
2. Save images at the right size
3. Use the correct resolution

### Image Resolution:
Images created for the web should be saved ata resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.

#### Vector Images:
Vector images differ from bitmap images and are resolution-independent. Vector images are
commonly created in programs such as Adobe Illustrator.

### Transparency:
Creating an image that is partially transparent (or "see-through") for the web involves
selecting one of two formats

## Foreground Color:


rgb values:
These express colors in termsof how much red, green andblue are used to make it up. For
example: rgb(100,100,90)

hex codes
These are six-digit codes thatrepresent the amount of red,green and blue in a color preceded by a pound or hash # sign. For example: #ee3e80

color names
There are 147 predefined colornames that are recognizedby browsers. For example:
DarkCyan

Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker
![color](https://qph.fs.quoracdn.net/main-qimg-aee4f35e4a63329ba93b27ed7917acb5.webp)

### Opacity:
CSS3 introduces the opacityproperty which allows you tospecify the opacity of an elementand any of its child elements.The value is a number between0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).

![opacity](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAASwAAACoCAMAAABt9SM9AAAAh1BMVEX////n7P/R2v+5x/+jtP+Lof91j/9dfP9Hav8vV/8rTOre4vjK0fjFzPSuuvSWpPF9j+5nfepQa+s9WeYmSOmImvO3wvehrvVyh/BZcu5DX+zO1fjMzuy9v+atsOCElO2fotuRldWGis8eQOCFnf9tiv9Tdv86Y/94fckbTv/t7vk2UuFnfe3i/Ly/AAACAUlEQVR4nO3QWVLbUBAAwCEEDIgAssMuyVq8yHbuf77kAvNcKYq/7iN0RNnxInWMqD5TVUTzkmoi2tdUG9GtnxPrLqKv3xJ1HzEs3xPLIWJcfSROY8Q83SWm+UxV6erfVvWjoGouC5r2Z0Hbba5Sm67fXqe2/bBbpHbDuL9J7cf5cJs6nNsqXV1U96Ws+4dS1sNjKevxKb+6ulrX+dX1db3MrxaL5Sm/urk5TfnV7e30fVm/vi3r6c8XslalrNXvUtadLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZMmSJUuWLFmyZP1n1v23Za3rL2SdSlmnqZQ1nck6lrKOVSmrakpZTVvKartNfrXp+m1+te2HXX61G8Z9frUf50N+dZjPZJW2jhHVZ6qKaF5STUT7mmojuvVzYt1F9PVbou4jhuV7YjlEjKuPxGmMmKe7xDTHX9z5HNcFKLNFAAAAAElFTkSuQmCC)

### HSL Colors:
CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation,
and lightness values.

1. hue Hue is the colloquial idea of color. In HSL colors, hue is oftenrepresented as colorcircle where the angle represents thecolor, although it may also be shown as a slider with values from 0 to 360.
2. saturation Saturation is the amount of gray in a color. Saturation isrepresented as a percentage.
100% is full saturation and 0%
is a shade of gray.
3. ligh tness Lightness is the amount of white (lightness) or black (darkness) in a color.Lightness
is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as.

## Text:
Specifying Typefaces:
- font-family:
The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.

- font-size:
The font-size property enables
you to specify a size for the
font. There are several ways to
specify the size of a font.

- @font-face:
@font-face allows you to use
a font, even if it is not installed
on the computer of the person
browsing, by allowing you to
specify a path to a copy of the
font, which will be downloaded if
it is not on the user's machine.
- src:
This specifies the path to the
font. In order for this technique
to work in all browsers, you will
probably need to specify paths
to a few different versions of the
font, as shown on the next page.
- format:
This specifies the format that the
font is supplied in. (It's discussed
in detail on the next page.)

## JPEG vs PNG vs GIF:
## Compression:
ompression can be of two types — lossless and lossy. In lossless compression, it is possible to reconstruct the original image from the compressed image because there is no information loss during compression.

- JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth

- PNG is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image.
- GIF is also a lossless image format that uses LZW compression algorithm. 

## Transparency:
- JPEG images don’t support transparency and are hence not usable for such cases.
- PNG images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency).
- GIF images support transparency by declaring a single colour in the colour palette as transparent (index transparency). Because of absence of partial transparency, the edges (specially rounded or too-detailed edges) get a poor jagged effect. Though this can be solved to some extent using dithering, with improved PNG support, GIF is unsuitable for images with transparent backgrounds.

## Colours:
- JPEG images can support around 16 million colours. This is what makes them suitable for storing images of natural scenes.
- PNG images mainly have two modes — PNG8 and PNG24. PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image.
- GIF images are limited to 256 colours.
## Animation:
- Of these 3 formats, only GIF supports animation. 
![different between image formate](https://tkddesign.co.uk/wp-content/uploads/image-file-formats.jpeg)