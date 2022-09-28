# Image-Encoder
Python Image Encoder using PIL
Project can be seen in action here: https://drive.google.com/file/d/12WXrxETh9fwg9-Tik7imv0RB_a8iK2tO/view?usp=sharing

This project takes a message and a value that applies a ceaser shift by that number in ASCII, and then creates an ceaser cypher encrypted message. The ASCII value of each character in that encrypted message is then saved as the A value (transparency) in the RGBA value of each pixel, and a modified image with the message encoded into it is subsequently outputted.

Image before encoding:

![pulsar](https://user-images.githubusercontent.com/14097239/192820908-af467819-c79a-419a-9dd7-1547a951d131.png)

Message to be encoded: "Hello, how are you doing today?"
Caesar Shift: 5

Encoded Message: "Mjqqt1%mt|%fwj%~tz%itnsl%ytif~D"

Image with encoded message embedded within the transparency value of the pixels:

![Unknown](https://user-images.githubusercontent.com/14097239/192821535-2863e77c-b4c0-4e99-93c3-2bee35a862b5.png)

This final image looks almost identical to the original.
