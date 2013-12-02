hex
===

#### Pretty prints a Buffer ####

[![NPM version](https://badge.fury.io/js/hex.png)](http://badge.fury.io/js/hex "Fury Version Badge")

[![NPM installation](https://nodei.co/npm/hex.png?mini=true)](https://nodei.co/npm/hex "NodeICO Badge")

#### Functions ####

- [_module_(buffer) : undefined](#hex)

---

<a name="hex"></a>
___module_(buffer) : undefined__

Pretty prints a Buffer. For debugging purposes.

```javascript
var hex = require ("hex");
hex (buffer);
```

```
Offset   00 01 02 03 04 05 06 07 08 09 0A 0B 0C 0D 0E 0F

000000   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000010   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000020   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000030   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000040   54 41 47 42 72 65 61 6B 69 6E 67 20 54 68 65 20   TAGBreaking The
000050   4C 61 77 00 00 00 00 00 00 00 00 00 00 00 00 00   Law.............
000060   00 4A 75 64 61 73 20 50 72 69 65 73 74 00 00 00   .Judas Priest...
000070   00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 42   ...............B
000080   72 69 74 69 73 68 20 53 74 65 65 6C 00 00 00 00   ritish Steel....
000090   00 00 00 00 00 00 00 00 00 00 00 00 00 31 39 38   .............198
0000A0   30 47 72 65 61 74 20 73 6F 6E 67 21 00 00 00 00   0Great song!....
0000B0   00 00 00 00 00 00 00 00 00 00 00 00 00 00 33 89   ..............3.
```