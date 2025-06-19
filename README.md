# Huffman Text File Encoder and Decoder

This project demonstrates how Huffman coding can be used to compress and decompress text files, aiming to reduce file size and optimize storage efficiency.

## Project Structure

- `encode.cpp` – Implements the encoding process using Huffman coding for text files.
- `decode.cpp` – Handles decoding of compressed `.huf` files back into their original text format.
- `huffman.cpp` – Contains the core Huffman tree logic and helper functions used by both encoder and decoder.
- `huffman.hpp` – Header file that defines structures and interfaces used in `huffman.cpp`.

## Requirements

You’ll need a C++ compiler (like `g++`) installed on your system to compile the source files.

## How to Compile

Use the following commands in your terminal or command prompt to compile the encoder and decoder:

### Compile the Encoder

```sh
g++ encode.cpp huffman.cpp -o encode
```

### Compile the Decoder

```sh
g++ decode.cpp huffman.cpp -o decode
```

## How to Use

### To Encode a file

To use the encoder, run the following command:

```sh
./encode inputFile.txt compressed.huf
```

This will create a compressed file named `compressed.huf` in the current directory.

- `inputFile.txt`: The input text file you want to compress.
- `compressed.huf`: The output compressed file.

### Decoding a File

To use the decoder, run the following command:

```sh
./decode compressed.huf outputFile.txt
```

This will create a decompressed file named `outputFile.txt` in the current directory.

- `compressed.huf`: The input compressed file.
- `outputFile.txt`: The output text file that will contain the decompressed content.



