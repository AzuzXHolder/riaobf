# RBXLuaObfuscator
this is a modified [RBXLuaObfuscator](https://github.com/kosuke14/RBXLuaObfuscator) (made by [**kosuke14**](https://github.com/kosuke14)) version

### Script
```lua
local obfuscator = loadstring(game:HttpGet("https://raw.githubusercontent.com/AzuzXHolder/riaobf/refs/heads/main/source.lua"))()

obfuscator(
 [===[
  --// Paste your source here
  print("Hello World!")
 ]===],
 "GayHorse_", --// Custom Variable
 "ProtectWithCondom" --// WaterMark
)
```
**NOTE**: will be copied to clipboard after executed!
