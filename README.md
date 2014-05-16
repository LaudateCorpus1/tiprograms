TiPrograms
==========

Repository containing programs written for Texas-Instruments calculators.

## How to compile and syntax check the programs ##
The programs inside of this repository were mostly taken from our own calculators and rewritten into a text file. This means that all of the .tib files in this repository are simply the TI-Basic code you would fine on your calculator which would then when run be converted into raw hex.

To compile these programs you should take a look at tools such as the [TI-83 Plus/TI-84 Plus Online Programming IDE](http://www.cemetech.net/sc/) or the [TI-Basic Compiler](http://sourceforge.net/projects/tibasic/). As you may see we have maintain the structure of our code's syntax close to that of the online IDE to avoid conflicts when compiling or test checking the code.

Once the code is compiled by any of these two mentioned methods, it can then be uploaded directly to the calculator in the raw .8xp format through a TI Connect cable.

## Emulating the programs ##

It is possible to emulate the programs in this repository on Windows. Please keep in mind that a ROM image of one of TI's calculators is still required to be able to emulate the system's structure. The ROM image can be obtained by connecting a calculator to a PC and transferring the image from the calculator. Once you have a ROM image you can use one of the following suggested emulators to run the code in this repository:

**[TilEm - Standalone TI emulator for Windows, MacOS and Linux](http://lpg.ticalc.org/prj_tilem/)**<br/>

**[jstified - Online TI emulator](http://www.cemetech.net/projects/jstified/)**

## Additional notes ##

As you might notice some of the programs inside of this repository are quite simple. The reason for this is that we have decided to include all of our programs for the sake of allowing newcomers to TI-Basic programming to be able to start off with more minor and simple programming tasks. At the same time these programs are more meant as examples for how little code can be used to achieve a desired programmable goal on a TI calculator.

## Collaborators ##

**[Catlinman](http://catlinman.com/)** <br/>

**[Jokler](https://twitter.com/jokler13)** <br/>

## Licence ##

This repository is released under the MIT license. For more information please refer to [LICENSE.md](https://github.com/Catlinman/TiPrograms/blob/master/LICENSE.md)