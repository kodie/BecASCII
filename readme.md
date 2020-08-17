# BecASCII <3

I wanted to make something for my wife and I have no artistic skills so I decided to do something creative with my programming skills!

Te amo mi vida :heart:

## What It Does

When the window first loads, it first finds out the width and height that the characters will be based on the font face and size used (using the `getFontCharPx` function). It then chooses a random object from the `images` array located in [images.js](images.js) that has an image URL as well as it's original width and height. After that it does some math to figure out what aspect ratio we should stick to based on the image and window size and calculates how many characters wide and high the ASCII art should be. Finally, using the [aalib.js](https://github.com/mir3z/aalib.js) libary, it generates ASCII art of the image and displays it on the page.

TLDR: It generates random images of my wife (Beca) as ASCII art.

## How To Use This Yourself

Simply clone this repo and replace the images inside of [images.js](images.js) with your own!

## License
MIT. See the [license file](license.md) for more info.
