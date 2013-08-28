hex
===

_Node.js project_

#### Pretty prints a Buffer ####

Version: 0.0.1

#### Installation ####

```
npm install hex
```

#### Functions ####

- [_module_(buffer) : undefined](#hex)

---

<a name="hex"></a>
___module_(buffer) : undefined__

Pretty prints a Buffer. For debug purposes.

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
000040   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000050   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000060   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000070   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000080   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000090   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
0000A0   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
0000B0   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
0000C0   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
0000D0   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
0000E0   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
0000F0   FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF FF   ÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿÿ
000100   54 41 47 42 72 65 61 6B 69 6E 67 20 54 68 65 20   TAGBreaking The
000110   4C 61 77 00 00 00 00 00 00 00 00 00 00 00 00 00   Law.............
000120   00 4A 75 64 61 73 20 50 72 69 65 73 74 00 00 00   .Judas Priest...
000130   00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 42   ...............B
000140   72 69 74 69 73 68 20 53 74 65 65 6C 00 00 00 00   ritish Steel....
000150   00 00 00 00 00 00 00 00 00 00 00 00 00 31 39 38   .............198
000160   30 47 72 65 61 74 20 73 6F 6E 67 21 00 00 00 00   0Great song!....
000170   00 00 00 00 00 00 00 00 00 00 00 00 00 00 33 89   ..............3.
```