# Inko DataView
> [!WARNING]  
> This is a WIP. So far only methods for `int`, `short` and `byte` have been implemented.

This is an Inko package to have similar methods to Java's `DataOutput` and `DataInput` to interact with Byte Arrays.

## Examples
You can use the `Reader` class to read from a ByteArray. Example:
```rs
import dataview(Reader)

let reader = Reader.new('hello'.to_byte_array)
let value = reader.getShort(0)
```

##

This package is used by [inko-dns](https://github.com/fres621/inko-dns)