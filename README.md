Portable AES-SIV
================

This is a C++ project that implements a portable [Synthetic Initialization Vector](https://tools.ietf.org/html/rfc5297) mode with
AES encryption. The AES implementation is not mine and can be replaced with minimal difficulty.

This code has been tested on Windows and on Arduino Uno. It was written primarily for use with
Arduino and other compatible embedded microcontrollers.

**IMPORTANT:** Although the standard AES-SIV test vectors successfully pass, there is NO
GUARANTEE that this is a 100% correct and secure implementation. Please exercise caution when
using this code for anything.
