# Huffman_encoding

This project implements an **encoding and decoding pipeline** using the **lossless Huffman source-coding algorithm**.

## What is Huffman Coding?

Huffman coding is a **prefix-free** compression technique, meaning no codeword is a prefix of another. This allows the encoded stream to be decoded unambiguously without separators between codewords.

It is **optimal** in the sense that it produces the **shortest average codeword length** for a discrete finite-alphabet variable with a known probability mass function (PMF). As Kleijn puts it in *A Basis for Source Coding*:

> "The Huffman code is a uniquely decodable code with the shortest average codeword length for a finite-alphabet discrete variable with known probability mass function."

In practice, the PMF is often unknown and must be **estimated from symbol frequencies** in the input data.

## Purpose

This project was primarily developed as a **practice exercise**. For real-world applications, more efficient implementations should be considered.

## Input Text

The source text used for encoding and decoding is **Chapter 1 of *The Iliad***, available here:

[https://www.planetebook.com/free-ebooks/the-iliad.pdf](https://www.planetebook.com/free-ebooks/the-iliad.pdf)

