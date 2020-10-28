# Bitmap-to-C-Converter
Generate an array of chars for displaying on Nokia 5110 LCD using Phillips PCD8544 LCD Controller

Written in Scratch 3.0
Made for Dr. Widder's EE 2920 class

How to use:
-Create an 84x48 monochrome bitmap file
-Resize to 420x240
-Click "See Inside", then select Stage, Backdrops, upload an image and select the image you want to scan.
-Click the Run button (slow mode shows you exactly what is happening, drag the Fast Mode slider to 0 for slow mode)
-Right click the list that pops up, the select "Export"
-Paste exported text file with code below into a file named "bitmap.h". Delete the last comma in the list.
-Add more static const char [] arrays for more bitmaps



<b>Code for .h file:</b>

#ifndef BITMAP_H__
#define BITMAP_H__

static const char bilkeyconvert [] = {
 // PASTE HERE
  };

#endif BITMAP_H_
