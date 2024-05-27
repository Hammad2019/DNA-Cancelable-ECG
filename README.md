DNA to Amino Acid Conversion Script

Overview

This script contains functions to convert DNA sequences into amino acids, and further encode binary and numerical representations of data. The primary purpose of the script is to process input data from a file, convert it into a format suitable for biometric analysis, and write the processed data to an output file. The script was used in our published paper: "Cancelable ECG biometric based on combination of deep transfer learning with DNA and amino acid approaches for human authentication" in Elsevier Information Sciences journal.

Components

Amino Acid Dictionary

The aminodict dictionary maps RNA codons to their corresponding amino acids. Each codon (a sequence of three RNA nucleotides) is associated with a single amino acid or a stop signal

Functions

    dnaconvert: Converts a binary string into a DNA sequence.

        binaryconvert: Converts a DNA sequence into a binary string.

        dnaToAmino: Converts a DNA sequence into an amino acid sequence using the aminodict dictionary.

        worint: Converts a word into an integer by calculating the sum of the ASCII values of its characters.

        get_bin: Converts a decimal number to a binary string.

        File Processing

The script reads data from Finger-Data1.txt, processes each word, and writes the results to Finger-Data1mod.txt.

Usage

    Ensure the input file Finger-Data1.txt is in the same directory as the script.
    
    Run the script: The script will read from Finger-Data1.txt, process the data, and write the results to Finger-Data1mod.txt.
    
    Check the output file Finger-Data1mod.txt for the processed data.

References

This script is part of the research presented in the paper: "Cancelable ECG biometric based on combination of deep transfer learning with DNA and amino acid approaches for human authentication", published in Elsevier Information Sciences journal: https://www.sciencedirect.com/science/article/pii/S0020025521011889
