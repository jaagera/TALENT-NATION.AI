TOPIC: PY - LESSON 1.9: HOW DATA IS REPRESENTED (STORED)

```
information is represented using patterns of 0s and 1s.
```

> Everything a computer stores—numbers, text, images, audio, and video—must ultimately be represented as digital data.

* In binary, each position represents a power of 2.

# So binary is not a mysterious computer language. It is simply a number system based on two possible digits.

*** A common basic storage unit is a byte: i.e 1 byte = 8 bits. Example of a byte: 01000001 ***

## Large Amounts of digital data are commonly described using units such as: (KB → MB → GB → TB)

*** You might encounter them when looking at:***
- the size of a document
- the storage capacity of a phone
- the size of an image
- the size of a video file

```
"Character encoding" is a system that maps characters (letters, numbers, symbols, and emojis) to specific numerical values so computers can store, transmit, and display text.

```

>For a computer to be able to store information it needs a "Binary Data", whihc requires a CHARACTER ENCODING. And one familiar encoding is ASCII(American Standard Code for Information Interchange). NOTE: It's not going to represent every writing system or symbol used around the world.

* That is why broader character-encoding systems exist, including Unicode.
UTF-8 is one widely used way of encoding Unicode characters as bytes. *** 

```
A character is mapped to numerical data, and that numerical data can be represented and stored using binary.

```

*** Images: From Pixels to Binary Data:
A computer does not store a photograph as one giant object called "photo." A digital image is made up of many small elements called pixels.
THE PROCESS IN IMAGE:
Image
↓
Pixels
↓
Numerical values
↓
Binary data
↓
Stored by the computer ***



*** Audio: From Sound to Binary Data:
When you record someone's voice, the computer converts the sound into a series of samples. And each sample is represented numerically whihc appears in sequence. 
THE PROCESS IN SOUNDS:
Sound
↓
Samples
↓
Numerical values
↓
Binary data
↓
Stored digitally
When the computer later plays the recording, it uses the stored digital information to reproduce the sound. ***




*** 
Video: Combining Digital Information:
Video is more complex because it contains a sequence of images, usually accompanied by audio.
A simplified model is:
Video
├── Frame 1
├── Frame 2
├── Frame 3
├── ...
└── Audio
THE PROCESS:
Video
↓
Images + Audio
↓
Numerical data
↓
Binary data
↓
Stored digitally
This is why videos can require much more storage than simple text: they may contain enormous amounts of image and audio data.

# Information	|        Intermediate representation    |	        Ultimately stored as
Number	    |       Numerical value	                    |           Binary data
Text	    |      Character → numerical value	        |           Binary data
Image	    |     Pixels → numerical values	            |           Binary data
Audio	    |    Samples → numerical values	            |           Binary data
Video	    |   Frames + audio → digital values	        |           Binary data

The representation may be different at higher levels, but eventually the information has to be converted into patterns of digital states.

>N.B: Bits represent two possible digital states, and combinations of those bits represent information. ALSO: We have to note that computers need a digital representation for everything they store. 

```
KEY:
- Numbers can be represented as binary values.
- Characters can be mapped to numerical values through character encoding.
- Images can be represented through pixel data.
- Audio can be represented through samples.
- Video combines digital image and audio information.

```
# UTF-8 (Unicode Transformation Format – 8-bit) is the dominant character encoding standard on the web, capable of representing all 1,114,112 valid Unicode code points using a variable width of 1 to 4 bytes per character.

