# using-python-to-solve-DNA-problems
Before we look at the code, let's talk about DNA. DNA, or deoxyribonucleic acid, is the hereditary material in humans and almost all other organisms. The information in DNA is stored as a code made up of four chemical bases: adenine (A), guanine (G), cytosine (C), and thymine (T). The reverse complement of a DNA sequence is formed by reversing the letters, interchanging A and T and interchanging C and G. Thus the reverse complement of "ACCTGAG" is "CTCAGGT". A DNA is a double helix structure, one side being the DNA sequences, the other side being the reverse complement. The most important aspect of DNA sequences, is converting DNA sequences to protiens for our bodies to use. In eukaryotes, the messenger RNA, a part of DNA sequence that creates the protien, is transported out of the nucleus to the cell's cytoplasm, where it is converted to a protein sequence in a process called translation. There are 20 letters in the of protein sequences, where each letter is an amino acid. To perform the translation, the mRNA is divided into units of three consecutive letters, each called a codon. There is a genetic code for translating a codon into an amino acid. For example, the codon TCA codes for S, the amino acid serine. Normally, TAA, TAG and TGA are stop codons and translation stops when one of them is reached. The RNA enters the ribosome, and the ribosomes "reads" the DNA, and creates a chain of amino acids to create a protien. Another quality of DNA sequences are palindromes. A palindromic sequence is a nucleic acid sequence in a double-stranded DNA or RNA molecule wherein reading in a certain direction on one strand matches the sequence reading in the same direction on the complementary strand.
Now let's look at the code. There are four files that solve four main problems relating to DNA.

1) Count of ATCG.py: 
This code counts the four chemical bases: adenine (A), guanine (G), cytosine (C), and thymine (T). 

2) Reverse complement.py: 
This code finds the reverse complement of the DNA sequences. For example, if you enter the DNA seqeunces "ACCTGAG", the output will be "CTCAGGT".

3) Palindromes.py: 
This code will find the location of palindromes in a DNA sequence. Palindromes are four letter sequences. Let us say dna[4:8] is a palindrome and so is dna[15:19]. The output will be 4,15. 

4) Find protiens.py: 
This code will find and print all of the protiens in the DNA sequence, and stop at the STOP codon. This code will print the codes, not the entire protien name. This code will also not print the STOP codon. 
