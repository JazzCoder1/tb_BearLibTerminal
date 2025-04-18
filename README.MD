# twinBASIC Wrapper for BearLibTerminal


## What is BearLibTerminal

BearLibTerminal is a library that creates a terminal-like window facilitating flexible textual output and uncomplicated input processing.

The homepage is here:
http://foo.wyrd.name/en:bearlibterminal

Notable features of BearLibTerminal include:

* Ease of Unicode usage.
* Support for bitmap and vector (TrueType) fonts.
* Extended output facilities: tile composition, alignment, offsets.
* High performance (uses OpenGL).
* Keyboard and mouse support.
* Windows, Linux and OS X builds.


### twinBASIC Binding/Wrapper
This code allows the use of BearLibTerminal in twinBASIC.  
Multiple examples are provided.  
Not all of the API calls have been tested.
This is a 32-bit binding.  
(Font loading and applying fonts are not working, maybe someone could fix this) 

![screenshot](https://github.com/JazzCoder1/tB_SIGIL/blob/main/screenshots.PNG "Examples")

### License

This twinBASIC BearLibTerminal Wrapper uses the UnLicense.  
BearLibTerminal is licensed mainly under the MIT license with a few parts under other permissive licenses:

Modified FreeType2: FreeType License.  
PicoPNG: zlib license.  
NanoJPEG: custom KeyJ's Research License.  


### What is twinBASIC
twinBASIC is a new BASIC language compiler that strives to be 100% compatible with Visual Basic 6 (and VBA).  
Check it out here: https://twinbasic.com/
and here: https://github.com/twinbasic/