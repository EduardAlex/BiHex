# BiHex
Simple binary to hexadecimal and backwards
# How to use

`from bihex import *`

To create an instance, use:

`foo = BiHex("b10110100")`, where the letter behind the number is the base (2 = b, 8 = o, 10 = d, 16 = x)

To display the number in:
- decimal: `foo.returnnum("d")`, gives `180`
- binary: `foo.returnnum("b")`, gives  `"0b10110100"`
- hexadecimal: `foo.returnnum("x")`, gives `"0xB4"`
- octal: `foo.returnnum("o")`. gives `"0o264"`
