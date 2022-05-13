# Color-Separator
ImageJ Plugin for extracting color images

This ImageJ Plugin splits 2 new RGB files from a single RGB file, based on the average R,B,G color values in an ROI. The procedure preserves the original image.

Installation:
Simply copy the .class file in the plugin folder of your ImageJ installation or use compile and run in the plugin menu on the .java file.

How it works:
draw a ROI in the region of the color of interest and start the plugin. A small Gui will pop up with the individual R,G,B values and the tolerance in %. You can change the values according to your requirement. After pressing the OK button 2 new image windows will pop up. One image will contain all pixel within the chosen color range from the original image. The second image will hold all remaining pixel.
