# CMPS 2200 Recitation 6
## Answers

**Name:**_________________________


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
Name	Fixed Length	Huffman 
f1.txt	1340	826
alice29.txt	1039367	676374
asyoulik.txt	876253	606448
fields.c	78050	56206
grammar.lsp	26047	17356


The pattern is that huffman is more efficient than fixed-length for every file. The huffman code is about .65 more efficient which is extrememly large compared to the fixed-length. It only improves as the files get bigger with more text.

- **e.**

To calculate the Huffman cost we need to determine the number of binary digits required to make up 1 character and multiply this by the frequency of that character. We will do this for every character - However the frequency is the same for each so we will end up with a balanced tree. A balanced tree will have a root node and 2 children. Those two children will continue to have 2 children. This will mean that both Huffman and Fixed-length will have similiar costs.
