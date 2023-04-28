# m7_lcd_test
This is a test module for several LCD functions from ESOS32.

INSTRUCTIONS

Connect the NUCLEO-L452RE board to your computer via USB.
Upload the m7_lcd_test.hex onto the NUCLEO-L452RE with STM32CubeProgrammer.
Press the black Reset button on the NUCLEO-L452RE and watch the LCD print off the test functions, each should last 2-4 seconds.
1. clearScreen() - clears screen  
2. writeChar() - writes out the message 1 character at a time
3. writeBuffer() - writes what is in buffer
4. setCursorDisplay() & setCursorBlink() - cycles through the 3 options for the cursor: blink, no-blink, and hide cursor
5. setDisplayVisible() - resets display for 2 seconds before showing text again
