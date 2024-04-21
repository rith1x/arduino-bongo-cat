# Arduino-Bongo-Cat
![alt text](https://media.tenor.com/fYg91qBpDdgAAAAi/bongo-cat-transparent.gif)

Bongo cat Animation on 128x64 OLED Display with Arduino UNO R3 and 2 push buttons

# Circuit Diagram

![Circuit](https://github.com/rith1x/arduino-bongo-cat/blob/390b5b8afe388b00daa378acd855a845ac66664a/Circuit%20Diagram.png)

# Steps Involved

- Downloading Bongo Cat Image
- Separating Frames (Left tap, Right tap, No tap, Both hand tap)
- Minimizing resolution to 128 x 64
- Converting into byte arrays [image2cpp](https://javl.github.io/image2cpp/)
- Defining 4 different arrays for 4 types of Image
- In arduino , Including Button Logic
- Defining the Clear buffer, Draw buffer, Update Buffer to show the byte arrays into OLED Display
- Using Conditional Logic, Check for the Button Clicks and invoking Specific Function

I referred Youtube and the well known StackOverFlow for the Project and Error Debugging!

> THANKYOU FOR READING, Try this and Enjoy the interactive Bongo cat!!! , Meow!
