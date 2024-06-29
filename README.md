# Waveshare-2.13-ePaper
Working Arduino example for the Waveshare rPi_Pico ePaper (2.13B V4 tri colour)

The Python examples provided by Waveshare for their rPi_Pico ePaper displays work fine, however their Arduino examples do not.  This appears to be because they coded initialy for a UNO device and copy and pasted the code to the Raspberry Pi Pico.  It will never work as is.  The Pico uses SPI1 to drive the display and the pin numbers provided in the example do not match.  The example code provided here has the necessary changes made to acheive a working example.
