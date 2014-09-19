Available Functions for datatype Thermal
by Randall Bruder
----------------------------------------

test()

testBitmap()

printBarcode(String s, int type)
	* @param s
	*            The barcode string to print
	* @param type
	*            The type of barcode. ( UPC-A = 0, UPC-E = 1, EAN13 = 2, EAN8 =
	*            3, CODE39 = 4, , I25 = 5, CODEBAR = 6, CODE93 = 7, CODE128 =
	*            8, CODE11 = 9, MSI = 10)
   
printBitmap(int width, int height, byte[] bmp)
	* Method to print bitmaps. Each pixel is a bit (0 = black pixel / 1 = white
	* pixel) so every line of the image is comprised of bytes each containing
	* the data for 8 pixels in a row.
	*
	* @param height
	*            Height of bitmap in pixels
	* @param width
	*            Width of bitmap in pixels
	* @param bmp
	*            byte array cointaining the bitmap data. Each pixel is
	*            represeneted by a single bit in the byte array.
	
wake()

sleep()

justify(String justification)
	* Set the text justification
	*
	* @param justification
	*            The justification of the text "L"(LEFT), "C"(CENTER) or
	*            "R"(RIGHT)

inverseOn()

inverseOff()

doubleHeightOn()

doubleHeightOff()

setLineHeight(int lineHeight)
	* Set the line height of the text
	*
	* @param lineHeight
	*            The new line height
	
boldOn()

boldOff()

underlineOn()

underlineOff()

setBarcodeHeight(int barcodeHeight)
	* Set the barcode height in pixels
	*
	* @param barcodeHeight
	*            the new height of the barcode

setSize(String s)
	* Set the text height
	*
	* @param s
	*            The size of the text "S"(SMALL), "M"(MEDIUM) or "L"(LARGE)

feed()

feed(int num)
	* Feed the paper
	*
	* @param num
	*            Tumber of lines to feed
	
tab()

setCharSpacing(int spacing)
	* Set the character spacing
	*
	* @param spacing
	*            The spacing between characters

setLineSpacing(int height)
	* Set the line spacing in dots.
	*
	* @param height
	
println(String str)
	* Print a text string
	*
	* @param str
	*            The string to print
	
write(byte b)
	* Print a byte.
	*
	* @param b
	*            The byte to print

write(byte[] b)
	* Print a byte array. The OutputStream is used instead of the PrintWriter
	* because it supports byte arrays
	*
	* @param b
	*            The byte array to print

printImageWithEffect(File saveFile)