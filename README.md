# LuaJIT with limited support for Lua5.3

This is a fork of LuaJIT 2.1, providing limited support for Lua 5.3 features.

## Key features
The following changes have been implemented:
- Added support for bitwise operators from Lua 5.3 (**x64 only**).
- Enabled 64-bit integer bit manipulation.
- Added metatable support for overloading bitwise operators.

**Note**: This implementation has not yet been thoroughly tested. Feedback and issue reports are welcome!

## Credits
This work is based on the following pull request:

https://github.com/LuaJIT/LuaJIT/pull/312

Special thanks to the original contributor for his effort.
