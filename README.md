# SyntheticDataForCharacterRecognition
1) random texts (1000 sentences of random lengths from 1 to 9 words generated by Python module Faker).
2) random colors (10 different font colors: black, red, blue, green, purple, orange, brown, gray, cyan, magenta; 10 different background colors: white, light gray, yellow, lightblue, light green, beige, lavender, light coral, peachpuff, honeydew); the combination is 100 different color effects.
3) random font sizes in the range of 20-40.
4) random font styles: 10 different True Type Fonts:  (Arial, Constantia, Calibril, Gabriola, Lucida Sans Unicode, Times New Roman, Palatino Linotype, Perpetua, Verdana, Tw Cen MT);
5) randomly applying Gaussian blur effect.
6) randomly applying noise effect.
7) randomly applying rotational angle of the generated text within a range of -10 to 10 degrees. Overall, these different random effects when combined offer a large variety of test examples to assess the prediction capabilities of this TrOCR model: >~1.8 million possibilities (100 different color effect x 10 different fonts x 21 font sizes x 2 (with and without blur) x 2 (with and without noise) x 21 rotational angles (using the integers to estimate the lower ends, as actual angles are floating points and thus have much large angle ranges).

a) Cases 1, 9 and 10: All seven factors mentioned above are randomized.

b) Case 2: Texts are the same with Case 1, but all other six effects are fixed at black/white for font/background colors, 30 font size, Arial font, no blur, no noise, and no rotation.

c) Cases 3-8: Texts are the same with Case 1, and each of the six effects from 2) to 7) as mentioned above is fixed at black/white for font/background colors, 30 font size, Arial font, no blur, no noise, and no rotation, respectively, while all other effects are the same with Case 1 texts.

Note: 
These 12 case zip files are named as imageCase1-1.zip, imageCase2-1.zip, imageCase3-1.zip, imageCase4-1.zip, imageCase5-1a.zip, imageCase5-1b, imageCase6-1a.zip, imageCase6-1b.zip, imageCase7-1.zip, imageCase8-1.zip, imageCase9.zip, imageCase10.zip

In each case folder the output.txt is the original texts file.
