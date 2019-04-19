# perl_scripts
A collection of useful perl scripts, mostly for fasta manipulation


#fasta_to_one_line.pl

This script takes a standard formatted fasta file and collapses the sequence data onto one line. Requires Perl and Data::Dumper
The output will replace the file given in the input

````
fasta_to_one_line.pl input_fas_file.fas
````

##Example: 

Input: 
>seq1
gcgggggttt
taggtgatag

>seq2
tcatttatat
caggtagtag

Output:
>seq1
gcgggggttttaggtgatag
>seq2
tcatttatatcaggtagtag
