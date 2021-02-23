# ICS4U_OutputBinary

Your job in this coding challenge is to do the reverse of what we saw in the video. You will read input from a text file, encode it into binary, and output that binary to a binary file.

The input file will be called "input.txt"
The output file should be called "output.bin" (or if running Python on Windows locally (ie not on Repl.it, then call it "output.txt")

Helpful hint:
To turn 'a' into a binary number

1. Take the ord('a')
```
ord_a = ord('a')
```
2. Convert that into a binary string of type byte
```
binary_byte = f"{ord_a:08b}".encode()
```
3. You can write ```binary_byte``` to a file opened with the 'wb' mode
