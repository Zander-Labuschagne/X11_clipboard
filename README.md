# X11_clipboard library

class containing C code to use the main clipboard object of X11.

~90% of this code is borrowed from exebook's barebones implementation: https://github.com/exebook/x11clipboard
 
I have just added abstraction by merging everything into two simple and easy to use functions in one C++ class for my own use.

Author: Zander Labuschagne <zander.labuschagne@protonmail.ch>

To compile add ``-lX11`` argument to ``g++`` to include the X11 libraries
This should only be compatible with Linux systems, if not please inform me.
I am still learning C++ so if anything is unacceptable or a violation to some standards please inform me.
