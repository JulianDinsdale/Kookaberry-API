
Display API 
===========


Description     
                                                       
The Display is based on the SH1106.  Monotone , Cyan, x = 0to 127, y= 0 to 63 
Specification

	
display.init_display()
							Initialises and clears the display.
display.fill(c)
							c is the colour.  c=0 no colour, c=1 fill with colour.
display.clear()
							Clears the display, equivalent to display.fill(0)
display.setfont(font)
							available fonts are:
								fonts.mono5x5
								fonts.mono6x7
								fonts.mono8x8
								fonts.mono8x13
								fonts.sans12

							Note:  Need to import fonts