# File-Zipper
![Screenshot from 2023-08-29 01-12-15](https://github.com/Ayuhoney/File-Zipper/assets/99753206/4b8493b2-4cce-4bdc-af0c-30d2eb869bca)
![Screenshot from 2023-08-29 01-12-10](https://github.com/Ayuhoney/File-Zipper/assets/99753206/5a8552d8-1b04-4bcf-a87d-8ba30882be8a)
![Screenshot from 2023-08-29 01-12-05](https://github.com/Ayuhoney/File-Zipper/assets/99753206/43c45efb-46d4-4261-a98f-aa2edbac31a8)
![Screenshot from 2023-08-29 01-11-08](https://github.com/Ayuhoney/File-Zipper/assets/99753206/74f2b312-35c2-466f-a2f2-73ecd72ed4ef)
![Screenshot from 2023-08-29 01-10-35](https://github.com/Ayuhoney/File-Zipper/assets/99753206/ecc48239-6cd0-491b-9a46-0825267ca1f0)
![Screenshot from 2023-08-29 01-07-10](https://github.com/Ayuhoney/File-Zipper/assets/99753206/c73d1da5-8668-476c-95e8-8db87ebecdfb)
![Screenshot from 2023-08-29 01-06-05](https://github.com/Ayuhoney/File-Zipper/assets/99753206/ddc137b0-ca98-40ee-a774-ddaefe27c78a)
![Screenshot from 2023-08-29 01-05-57](https://github.com/Ayuhoney/File-Zipper/assets/99753206/c958bec8-9715-440a-8bca-f45e78b2ce17)
![Screenshot from 2023-08-29 01-05-42](https://github.com/Ayuhoney/File-Zipper/assets/99753206/56c533d0-a7ca-42ce-b5e1-a1f6ff4cdcde)

A huffman coding library and command line interface to the library. The encoder is a 2 pass encoder. The first pass generates a huffman tree and the second pass encodes the data. The decoder is one pass and uses a huffman code table at the beginning of the compressed file to decode the data.
lib huffman has functions for encoding and decoding both files and memory.

The Huffmans algo creates a 1-1 mapping for each byte of the input file and replaces each byte with the
mapped bit sequence.
 Unlike Huffmans code dont need an extra dictionary to be saved. Also create a mapping to byte sequence
It creates mapping of multiple byte to binary sequence.
