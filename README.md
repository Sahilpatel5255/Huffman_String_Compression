# Huffman_String_Compression

Huffman Compression
This project implements Huffman Compression, a lossless data compression algorithm. Huffman Compression is based on the frequency of occurrence of a data item (character) and is particularly effective for compressing text and other data with varying character frequencies.It can reduce the sixe of  the file upto 50% of original text file 

#Features

1. Encode text files using Huffman Compression.
2. Decode Huffman-encoded files to their original text.
3. Command-line interface for ease of use.
   
#Prerequisites
Python 3.x

#Working
1. To compress
  ( in python shell)
    >>> from huffman import huffman 
    >>> path = "your file path of the text file"  
    >>> h = huffman(path)
    >>> h.compress()
2. To Decompress
    >>>h.decompress("your compressed bin file path")
