# DebuggingEdgarAllanPoesCryptography
### This repository contains the script that aims to deal with *The Gold Bug's cryptogram* in a computational way. The script belongs to my Bachelor's thesis "Debugging Edgar Allan Poe's Cryptography".  
The purpose is to decipher the cryptogram exploiting the frequency analysis, like Legrand did, but in a computational way. After having established the frequencies of the cryptogram's symbols, two frequency analyses have been made in order to use them for the decryption: the first one aims to reflect the frequencies of English letters at Poe's time, while the second reflects the frequencies of contemporary English letters. The former has been established analysing the frequency of the words that Poe used in writing his tales. On the other hand, the latter has been set using the COCA corpus as basis.  
  
#### Materials foundable in the File folder:
- EAP_tales.txt: a .txt file containing all the tales written by Edgar Allan Poe (except for The Gold Bug). The tales have been extracted from "The works of Edgar Allan Poe" Volume 1-5, retrieved from [Project Gutenberg](https://www.gutenberg.org/) on which the following Project Gutenberg license is applied: "This eBook is for the use of anyone anywhere in the United States and
  most other parts of the world at no cost and with almost no restrictions whatsoever. You may copy it, give it away or re-use it under the terms of the Project Gutenberg License included with this eBook or online at www.gutenberg.org. If you are not located in the United States, you'll have to check the laws of the country where you are located before using this ebook."
- WF.csv: a .csv file created extrapolating the most frequent words - and their frequencies - from the COCA corpus
- [wordFrequency.xlsx](https://www.wordfrequency.info/samples.asp): a .xlsx file that is the one you download from www.wordfrequency.info, representing the COCA corpus
  
#### What you find in the script "Debugging_Edgar_Allan_Poe's_Cryptography.ipynb":  
Firstly, the script prints the cryptogram of the tale and its length, then it presents the symbols ordered according to their frequency.  
Secondly, the English letters' frequency at Poe's time is set through the analysis of his tales.  
Thirdly, the frequency of contemporary English letters is established extracting information from the COCA corpus.    
Once that these three frequency analyses are ready, the decryption is carried out in a computational way.  
Lastly, the decrypted message is re-encrypted, but this time using more efficient - and modern - encryption techniques. 
