java cCDS523 Principle of Data Analytics and Programming
Programming Assignment 3
(Due: 20
th November 2024, 23:59)
1. (5 marks) In the past, the frequency analysis of letters was an important step in breaking cipher. Write a 
Python program that prompt the user to input the path of a text file and output the occurrence count of 
all 26 English alphabet (ignoring case) in the text file specified by the user.
Sample input and output:
Terminal
Please enter the path of the text file: asg3_q1_sample.txt
The frequency of English alphabet:
a: 1
b: 1
c: 1
… 
z: 1
You should output the count of every English alphabet one by one in alphabetical order. Each line should 
contain an English alphabet followed by its count. The counts of some English alphabets in the sample 
input and output are omitted to save space in this assignment specification but your program should 
output the count of all English alphabets.
2. (15 marks in total) In cryptography, a Caesar cipher is one of the simplest forms of substitution cipher. 
The encryption is performed through shifting each letter in the plaintext forward by a number of posi tions defined by the user along the alphabetical order. For example, if the user has defined the number 
of forward position shift to be 4, every letter E in the plaintext will be replaced by A in the ciphertext 
because character A is 4 positions in front of letter E in alphabetical order.
Consider the following mapping between each alphabet in plaintext and its corresponding alphabet in 
ciphertext where the encryption is performed by shifting 4 alphabets forward.
Plain A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
Cipher W X Y Z A B C D E F G H I J K L M N O P Q R S T U V
Process of Encryption:
Input plaintext:
The quick brown fox jumps over the lazy dog.
Encryption Process
Plain T h e q u i c k b r o w n f o x j u m p s o v e r t h e l a z y d o g .
↓↓↓ ↓↓↓↓↓ ↓↓↓↓↓ ↓↓↓ ↓↓↓↓↓ ↓↓↓↓ ↓↓↓ ↓↓↓↓ ↓↓↓
Cipher P d a m q e y g x n k s j b k t f q i l o k r a n p d a h w v u z k c .
Output ciphertext:
Pda mqeyg xnksj bkt fqilo kran pda hwvu zkc.
Process of Decryption:
The decryption of a ciphertext encrypted with Caesar cipher can be achieved by reversing the encryption 
process (i.e. shifting the letters backward).
Input ciphertext:
Pda mqeyg xnksj bkt fqilo kran pda hwvu zkc.
Decryption Process
Cipher P d a m q e y g x n k s j b k t f q i l o k r a n p d a h w v u z k c .
↓↓↓ ↓↓↓↓↓ ↓↓↓↓↓ ↓↓↓ ↓↓↓↓↓ ↓↓↓↓ ↓↓↓ ↓↓↓↓ ↓↓↓
Plain T h e q u i c k b r o w n f o x j u m p s o v e r t h e l a z y d o g .
Output plaintext:
The quick brown fox jumps over the lazy dog.
a) (6 marks) Write a program that prompt the user to input (1) the number of forward position shift and
(2) the plaintext message that they want to encrypt into the console. The progra代 写CDS523、Python
代做程序编程语言m then output the 
encrypted message to the console.
Sample input and output:
Terminal
Please enter the number of position shift: 4
Please enter the plaintext message: The quick brown fox jumps over the 
lazy dog.
The encrypted message is: Pda mqeyg xnksj bkt fqilo kran pda hwvu zkc.
b) (5 marks) Modify the program in (a) such that it will prompt the user to input (1) the number of for ward position shift, (2) the path of the plaintext text file and (3) the path of the ciphertext text file.
The program then encrypts the content of the plaintext text file and output the result ciphertext to 
the ciphertext text file.
Sample input and output:
Terminal
Please enter the number of position shift: 4
Please enter the path of the input plaintext file: plaintext.txt
Please enter the path of the output encrypted file: encrypted.txt
c) (2 marks) Modify the program in (a) such that it will prompt the user to input (1) the number of for ward position shift and (2) the encrypted message that they want to decrypt into the console. The 
program then output the decrypted plaintext message to the console.
Sample input and output:
Terminal
Please enter the number of position shift: 4
Please enter the encrypted message: Pda mqeyg xnksj bkt fqilo kran pda 
hwvu zkc.
The decrypted message is: The quick brown fox jumps over the lazy dog.
d) (2 marks) Modify the program in (c) such that it will prompt the user to input (1) the number of for ward position for shifting, (2) the path of the ciphertext text file and (3) the path of the decrypted
plaintext text file. The program then decrypts the content of the ciphertext text file and output the 
result plaintext to the plaintext text file.
Sample input and output:
Terminal
Please enter the number of position shift: 4
Please enter the path of the input encrypted file: encrypted.txt
Please enter the path of the output decrypted file: decrypted.txt
Assumption:
• Only English alphabet (upper case or lower case) characters have to be encrypted and decrypted. 
• Characters other than English alphabet are preserve during the encryption and decryption.
• Case of every English alphabet is preserved during the encryption and decryption process.
Assumptions
You may assume that every input of the program is valid in format.
Submission
Students should submit their source code as (1) a single Jupiter Notebook file (i.e. .ipynb file) OR (2) a zip file 
that contains standalone Python script files (i.e. .py files) for answering the programing questions to the 
submission box on the Moodle elearning platform on or before 20
th November 2024, 23:59. Students are 
expected to name their file submission in the name of _asg3.ipynb OR
_asg3.zip and their source code should follow the following format:

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
