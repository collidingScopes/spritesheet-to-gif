# Sprite Sheet to GIF Converter

A browser-based tool that converts sprite sheets into animated GIFs.

**Use it here: [https://collidingscopes.github.io/spritesheet-to-gif](https://collidingscopes.github.io/spritesheet-to-gif/)/**

<img class="example-image" src="assets/siteOGImage.png"> 
<img class="example-image" src="assets/sprite-animation.gif"> 

## Features

- Upload any sprite sheet image
- Configure rows and columns to extract frames
- Adjust animation speed and quality
- Preview individual extracted frames
- Download generated GIF

## Usage

1. Upload your sprite sheet
2. Set the number of rows and columns in your sprite grid
3. Adjust frame delay (animation speed) and quality
4. Click "GENERATE GIF"
5. Download your animated GIF

## Technologies

- Pure HTML, CSS, and JavaScript
- Uses [gif.js](https://github.com/jnordberg/gif.js) by Johan Nordberg for GIF generation
- No server-side processing required

## Setup

Simply clone the repository and open `index.html` in a browser:

```bash
git clone git@github.com:collidingScopes/spritesheet-to-gif.git
cd spritesheet-to-gif
```

## License

MIT