# Text-Encoding

Encode any text with Shannon-Fano algorithm.
Consists of several parts
<br/>part1:
<br/>Input: “Text.txt” file (English text). Goal: C++ (or another) program finds all symbols (not only letters) in this text and computes their probabilities. Outpit: list of all unique symbols from the text with their probabilities.
<br/>part2:
<br/>Input: “Text.txt” file and the result from Part 1. Goal: Encode the text from the “Text.txt” file using Shannon-Fano or Huffman algorithm with probabilities from Part 1. Output: a sequence of binary digits. 
<br/>part3:
<br/>Input: a sequence of binary digits from Part 2. Goal: Decode back into text the result  binary sequence after Part2 (using ShannonFano code). Output: a text identical to an initial text from “Text.txt” file.
<br/>part4:
<br/>Input: a sequence of binary digits from Part 2. Goal: Encode the result  binary sequence after Part2 (Shannon-Fano code) with Hamming code. Output: a sequence of binary digits ready for error-correction.
<br/>part5:
<br/>Input: a sequence of binary digits from Part 4. Goal: Add errors to the result  binary sequence after Part4 (Hamming code) with a certain interval. Output: a sequence of binary digits after Hamming code with artificially created errors.
<br/>part6:
<br/>Input: a sequence of binary digits from Part 5. Goal: Decode Hamming code and fix errors. Output: a sequence of binary digits identical to an output sequence from Part 2.
