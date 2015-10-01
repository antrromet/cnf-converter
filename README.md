# cnf-converter
CNFconverter.py converts any propositional logic sentence into its equivalent CNF sentence.

###Input and Ouput format:
The input to the program would be a file consisting propositional sentences represented in lists as explained in Section 2. Input file “sentences.txt” is provided. The number n in the first line indicates the number of input propositional sentences in the file. The next n lines contain one propositional sentence per line. You can assume that the variables are one character strings i.e. “A”, “B”...”Z”.

The command to run the program is in the following format:  
```
python CNFconverter.py –i inputfilename
```
The output of the program would be the CNF sentences equivalent to the input propositional sentence. The output file will be named “sentences_CNF.txt” containing the n lines where each line contains the equivalent CNF sentence for each input propositional sentence provided in the input file.
