# codepage-to-unicode
Some JSON objects and C# code to generate mappings of character code pages to unicode characters--a codepage to unicode converter.

There are two versions of each file, `Unicode` and `AsciiSafe`. The `AsciiSafe` versions escape all characters except the ones present in the US-Ascii encoding. The `Unicode` versions only escape code points that don't have a printable unicode character.

The folders contain JSON objects which take a codepage and maps one of its 256 code points to the corresponding unicode character.

If you don't know what to do with these and want to know more, raise an issue and I'll try to explain more.
