# FILE_COMPRESSOR
Huffman Algorithm File Compressor

## Description
The File Compressor is a project that implements the Huffman coding algorithm for compressing and decompressing files. Huffman coding is a lossless data compression technique that assigns variable-length codes to different characters based on their frequencies of occurrence in the input.

## Usage
in the UI you can choose the file you want to compress or decompress and the program will do the rest for you.
* Compressing a file will create a new file with the same name and a .huffy extension.
* Decompressing a file will create a new file with the same name and extension as the original file.
***
**The Header Used:**

*  4 bytes for the file Signature
*  2 bytes for the file extension length
*  bytes for the file extension
*  4 bytes for the file length
*  2 bytes for the tree size
*  bytes for the tree
*  bytes for the encoded file

> The tree is saved in a pre-order traversal manner.

***


## Installation
1. Clone the repo
   ```sh
   git clone https://github.com/0xJ1NX/FILE_COMPRESSOR
    ```
2. Open the project in your IDE (IntelliJ IDEA recommended)
3. Run the project
4. Enjoy!

## Screenshots

![s1](https://github.com/0xJ1NX/FILE_COMPRESSOR/assets/95927933/a99c6cf6-efb6-4c85-85a4-698f362d4ae1)
![s2](https://github.com/0xJ1NX/FILE_COMPRESSOR/assets/95927933/bfa94b3c-dc07-4553-971a-6d73de0f283e)
![s3](https://github.com/0xJ1NX/FILE_COMPRESSOR/assets/95927933/4c223276-1e45-451e-8a7d-36e991b81e8e)
![s4](https://github.com/0xJ1NX/FILE_COMPRESSOR/assets/95927933/bfeba1f0-7882-4b1e-adf5-a4e3c1bf2398)


