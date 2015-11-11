Source code for LED display.  This code is a little boggy and for anyone not wanting all features of the display, that part of the code can be deleted, and it should work fine. (Such as the Kinect interface).

Also, there are some libraries that need to be installed prior to use, those libraries are also attached, please seek documentation through arduino and processing for instructions on installing them. (its pretty easy)

The code uses the computer hardware to process the audio, lights, and gather sound, and the information is then transferred to the arduino as simply an interface. We recommend using a Teensy board as it has a higher clock cycle, but it will work on an arduino UNO.

The light strips are daisy chained with an LED height of 46, and therefore every other strip in the code is flipped vertically (dont worry about the code, but it matters when you wire the strips) Your height can be anything, just change it in the beginning of the code. The width however should be 8, otherwise there will need to be a significant amount of monkeying with the code to get it to work right.

For some reason, once the code is loaded and you hit "play" in processing, it takes about 10-15 seconds for the light show to start... not sure why, and it varies quite a bit.



Here is the link for the LED strips we used.
http://adafruit.com/products/306

An arduino board can be found in most radioshacks.

We recommend using a 5V power supply rather than powering solely from USB power. USB will work, but the intensity will dim quickly as more led's are illuminated.