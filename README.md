Invisibility Cloak using opencv and colour segmentation
The algorithm is simple and can be described in following steps:-
  1)Capture the background and store it , to reduce noise capture multiple frames and take average
  2)Detect red colour cloth using colour detection any other colour can also be used then  manipulate
    hue accordingly and mask it.
  3)segment out the red colour detected and replace it with background captured
  4)Generate the final augmented output to create a magical effect
