
# COMPARISON OF COMPLEX-VALUED AND REAL-VALUED NEURAL NETWORKS FOR PROTEIN SEQUENCE CLASSIFICATION
## Overview
This study evaluates the effectiveness of complex-valued deep learning methods in extracting meaningful information from biological sequences, specifically comparing these methods against real-valued deep learning models using the same dataset. The comparative analysis covers three different forms of protein sequences: DNA, Codon, and Amino Acid.

Steps for Each Study:
- Data Import: Downloading protein sequences from NCBI as fasta.
- Preprocessing: Synchronizing and labeling sequences.
- Encoding: Digitizing and saving as a dataframe.
- Classification: Using real-valued deep networks for classification.
- Visualization: Displaying results with graphical representations.

## The project consists of two primary methodologies (Complex and Real), each conducted as three sub-studies for different sequence types, followed by a comparative analysis using cross-validation.

  
# 1. Complex-Valued Neural Network Approach
Description:
Protein sequences (DNA, Codon, Amino Acid) are encoded into complex numbers using the proposed Complex Coding Method. These digitized sequences are then classified using Complex Artificial Neural Networks (ANNs), and their performance is benchmarked against Real-valued ANNs.

##  Sub-Studies:
- Study 1: DNA Sequences - Encoding DNA sequences into complex numbers and classifying with Complex-ANN.
- Study 2: Codon Sequences - Encoding Codon sequences into complex numbers and classification with Complex-ANN.
- Study 3: Amino Acid Sequences - Encoding Amino Acid sequences into complex numbers and classifying them with Complex-ANN.

# 2. Real-Valued Neural Network Approach
Description:
Kinase and GPCR protein sequences are encoded into real numbers using the integer coding method. These sequences are then classified using Real-Value Deep Learning methods.

##  Sub-Studies:
- Study 4: DNA Sequences - Encoding DNA sequences into complex numbers and classifying with Real-ANN.
- Study 5: Codon Sequences - Encoding Codon sequences into complex numbers and classification with Real ANN.
- Study 6: Amino Acid Sequences - Encoding Amino Acid sequences into complex numbers and classifying with Real ANN.

# 3. Comparative Analysis
- Study 7: Complex ANN vs. Real ANN - Using cross-validation, the performance of Complex and Real-valued ANNs are compared using metric averages for DNA, Codon and Amino Acid sequences. For 10 Fold, t-test is performed with the generated accuracy ratios.



## Technical Requirements
The study is implemented using Python in Jupyter notebooks. Essential libraries include Keras, TensorFlow, pandas, and numpy, which need to be installed to replicate the study.
