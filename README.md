# Screen Capture Library

This project produces screen captures of what is currently on the LCD and display it on the web page. This is useful when creating the user manual for a new product. It obviates the need to take (and post-process) photos of the display.

The project works by trasnferring the information obtained from the lcd.getpixel method into a bitmap string, which is generated when the web page is loaded. Another interesting technique to note is the use of the sock.urlsubstitutes property. Since we are generating the BMP file on the fly, we did not actually include a file called "enlarge.bmp".

- The code supports TEV-LB0, TEV-LB1 and TEV-LB2.
- Remember to rebuild the project when you change the LCD selected or else it might not work properly
- The main functions that deal with the screen capture are in cap_lcd.tbs