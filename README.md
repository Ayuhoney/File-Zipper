# File-Zipper

A huffman coding library and command line interface to the library. The encoder is a 2 pass encoder. The first pass generates a huffman tree and the second pass encodes the data. The decoder is one pass and uses a huffman code table at the beginning of the compressed file to decode the data.
lib huffman has functions for encoding and decoding both files and memory.

The Huffmans algo creates a 1-1 mapping for each byte of the input file and replaces each byte with the
mapped bit sequence.
 Unlike Huffmans code dont need an extra dictionary to be saved. Also create a mapping to byte sequence
It creates mapping of multiple byte to binary sequence.
