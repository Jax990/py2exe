# py2exe
Turns any python file into a small, one file exe that can be used on almost any computer that doesn't have python installed.

# Usage

CMD:  py2exe input.py output.exe [--upx] [--upx-ultra] [--gcc-ultra] [--minify] [--no-console] [--ultra-optimize] [--icon"C:/Path/To/Icon"]

# You must have python installed for this software to work!

Any version of python should work. The software UPX, an PE compression tool is built into the software. You won't need to install it before hand. 


`--upx` - Uses UPX on the final output exe. 

`--upx-ultra` - Uses max UPX settings on all files. Can cause the exe to not work on some older devices. 

`--gcc-ultra` - Uses max GCC options on the exe, can make file smaller slightly. 

`--minify` - Compresses the input python file, and all python source files. 

`--no-console` - Disables the console from opening when you run the output exe.

`--ultra-optimize` - Strips out every last bit of python that is not needed for the exe to run, On rare occasions can break the exe.

`--icon` - Sets an icon for the output exe. 
