# Simple Slides
Simple HTML based slide presenter, designed for demos and other situations where switching to PowerPoint is distracting or unnecessary.

## Usage
1) Export your presentation as PNG from PowerPoint, using *File --> Save As*. When prompted select **All Slides**
2) PowerPoint will put all of the PNG files into a subdirectory 
3) Download [release of this repo](https://github.com/benc-uk/simple-slides/releases), extract & copy *slides.html* into the directory alongside the PNG files
4) Open *slides.html* in your browser
5) If planning to serve via some hosting or other means, rename `slides.html` to `index.html`

## Controls
- Next slide: space, pgdown, down-cursor, right-cursor
- Back slide: backspace, pgup, up-cursor, left-cursor
- Blank screen: 'b'
- Hide/show slide number: 'n'
- Show elapsed time (for 5 seconds): 't'
   
## Note
The *slides.html* file is expecting the PNGs for each slide to be named; Slide1.PNG, Slide2.PNG, Slide3.PNG etc. This is how PowerPoint names them by default.

## Tip
To improve the resolution and & quality of the PNG files follow [this Microsoft support article](https://support.microsoft.com/en-us/help/827745/how-to-change-the-export-resolution-of-a-powerpoint-slide) which lets you specifiy a higher DPI (e.g. 200) for exported images
