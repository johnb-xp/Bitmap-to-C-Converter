# Bitmap-to-C-Converter
Generate an array of chars for displaying on 84x48px Nokia 5110 LCD using Phillips PCD8544 LCD Controller. Used at the Milwaukee School of Engineering with a MSP 432 microcontroller development board.
<br>

Written in Scratch 3.0 
<br>
Made for Dr. Widder's EE 2920 class
<br>

How to use:
1. Create an 84x48 monochrome bitmap file
2. Resize to 420x240
3. Open project (the .sb3 file) in Scratch. Click "See Inside", then select Stage, Backdrops, upload an image and select the image you want to scan.
4. Click the Run button (slow mode shows you exactly what is happening, drag the Fast Mode slider to 0 for slow mode)
5. Right click the list that pops up, the select "Export"
6. Paste exported text file with code below into a file named "bitmap.h". Delete the last comma in the list.
7. Add more static const char [] arrays for more bitmaps

<br>

<br>
<b>Code for .h file:</b>

#ifndef BITMAP_H__
<br>

#define BITMAP_H__
<br>
<br>

static const char bilkeyconvert [] = {
<br>

 // PASTE HERE
 <br>

  };
<br>
<br>

#endif BITMAP_H_
