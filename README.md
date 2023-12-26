For Oblige 7.70, Andrew Apted opted to add some non-standard 
extensions of Lua 5.1.  To wit, `continue` and `each`, e.g.

```
a={1,2,3} each b in a do if(b<=1) then continue end print(b) end
```

This repository is a version of Lua 5.1.5 with Apted's non-standard
Lua extensions used in Oblige 7.70 integrated.

Personally, I would had stuck with stock Lua 5.1, mainly for LuaJit
compatibility, but that was not the choice Andrew made.
