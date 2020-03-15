# DinosaurQuiz
Ross and Rachel are on a date. Ross, being the super geek he is, takes Rachel to see dinosaur exhibits.
Each dinosaur has a name and K attributes which are described by an ordered K-tuple ( A1, A2, A3,..., AK ). Each attribute Ai is an integer between 0 to L inclusive. Ross tells Rachel about N dinosaurs. For each dinosaur, he tells her its name and gives her the K-tuple describing its attributes.
Afterwards, he wants to play a quiz with Rachel. He gives Rachel Q K-tuples and ask her which dinosaur they belongs to. As Rachel loves Ross and doesn't want him to think she wasn't paying attention, she wants to answer all questions correctly. Help her in this task.

Input:
The first line contains N, K, L and Q, the number of dinosaurs, the size of the K-tuple, the maximum value of any attribute and the number of questions that Ross asks.
N lines follow. The next ith line contains a string which is the name of the ith dinosaur and K space separated integer which are the attributes for the ith dinosaur.
Q lines follow. The next ith line contains K space separated integer denoting a K-tuple.

Output:
For each question, output the name of the dinosaur that the K-tuple belongs to.
It is also possible that Ross is asking a trick question and the tuple doesn't describe any dinosaur. In such a case, output "You cant fool me :P" (Quotes are for clarity)

Constraints:
1<=N<=100000
1<=K<=5
1<=L<=15
1<=Q<=100000
0<=Ai<=L
1<=Length of Dinosaur's name<=10
Dinosaur's name will contain only lowercase alphabets [a-z].

Note:
No two dinosaurs will have the same K-tuple or name.

SAMPLE INPUT 
5 3 9 5
baryonyx 5 1 7
jobaria 1 2 3
oviraptor 9 7 1
troodon 6 9 5
minmi 7 4 5
9 7 1
1 2 3
5 8 8
1 2 3
7 4 5
SAMPLE OUTPUT 
oviraptor
jobaria
You cant fool me :P
jobaria
minmi
Time Limit: 2.0 sec(s) for each input file.
Memory Limit: 256 MB
Source Limit: 1024 KB


