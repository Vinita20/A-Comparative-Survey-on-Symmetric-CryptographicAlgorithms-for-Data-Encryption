Name:- Vinita Agrawal 

Student ID:- 1159203

Email ID:- vagrawal@lakeheadu.ca


# A Comparative Survey on Symmetric Cryptographic Algorithms for Data Encryption


## Table of Contents

1. Abstract
2. Introduction
3. Motivation and goals
4. Methods 
5. Results and Discussion
6. Conclusion
7. References
8. Acknowledgment 

## Abstract

In this new emerging world of internet, it has become important to secure the data sent over the network. Cryptography is an area in computer science field which makes sure that integrity, availability, identification, confidentiality, authentication of user, security and privacy of data are provided to the user. Many cryptographic algorithms are available to provide encryption. Encryption provides security of data transmitted over the network. It ensures that the transmitted data is accessed by the authorized receiver and also prevents from any type of modification or alteration of data. As there are many algorithms, it becomes difficult to choose the best one. This study provides a detailed research on cryptography and various symmetric algorithms like AES,DES and 3DES with respect to twelve factors like performance, execution time, key size, block size and many other features. The study provides a comparison between three symmetric encryption algorithms(AES,DES and 3DES) which is represented in the form of table.
  
## Introduction

When someone is transmitting data over a network, there are many threats to the security and privacy of data by hackers. Billions of people around the world are using a mechanism called cryptography to secure their data or information transmitted over the network. Cryptography is one such way to protect the confidentiality  and integrity of the data. It is a greek word divided into two parts i.e. ‘crypto’ means secret and ‘graphy’ means message{\cite{b1}}. This mechanism allows the data to be sent over a network in a format that is not readable by the hacker or intruder. This format can be read only by the sender and the authorized receiver. There are two concepts of cryptography namely encryption and decryption. The data is encrypted in an unreadable format known as cipher text to protect from intruders and with the help of a key an authorized receiver can obtain the data or information by decrypting the cipher text into plain text.

<img width="500" alt="Screenshot 2021-08-17 at 10 50 03 PM" src="https://user-images.githubusercontent.com/84442255/129941483-c90170f5-98fe-4c5b-b6dd-4e5cf1633c55.png">

#### Goals of Cryptography

Following are some goals of cryptography:

•Data Integrity

•Confidentiality

•Access Control

•Authentication

•Non-Repudation

<img width="400"  src="https://user-images.githubusercontent.com/84442255/129941747-c23724bc-6938-40cd-88b2-0af481963778.png">


#### Classification of Cryptography :

Cryptography is classified into two ways :

<img width="400"  src="https://user-images.githubusercontent.com/84442255/129942129-700e8b79-218c-4e6a-959d-c686a2830958.png">

1)Symmetric Key cryptography : In this system, only one key is exchanged in a secure manner by both sender and receiver. AES, DES , Triple DES are examples of symmetric key cryptography.

2)Asymmetric key cryptography : In this system, a pair of keys is used. A public key and a private key are used for encryption and decryption respectively. Even if an intruder knows the public key he cannot decode the information without the private key. RSA, DSS,DHA are examples of asymmetric key cryptography.

## Motivation and Goals

Security mechanisms necessitate the requirement of a specific method for encryption and decryption, as well as for managing the sub-keys that will be used to generate cipher text from plaintext. Because the security of algorithms is directly proportional to the length of the secret key, the longer the key, the more secure the technique.If recovering the plaintext is difficult when there is a large amount of ciphertext available, an algorithm is considered to be stronger\cite{b15}.Now there are many symmetric cryptographic algorithms available so it has become difficult to choose the best one. Hence, this survey compares three different symmetric cryptographic algorithms namely AES (Advanced Encryption Standard), DES(Data Encryption Standard) and 3DES(Triple Data Encryption Standard). The comparison analysis is based on different metrics like key size, block size, performance time, number of rounds, attacks, structure of algorithm, etc. The final results are based on qualitative research done on the basis of previous works done by various researchers.


## Methods and Investigation

This qualitative survey follows method of collecting information about the three (AES,DES and 3DES) symmetric algorithms and performing comparative analysis to provide the best symmetric algorithm.First, this section discusses about the structure and functions of each of the three (AES,DES and 3DES) symmetric algorithms. Second, comparison metrics that are considered for this survey are also explained in detail.

#### DES-Data Encryption Standard

DES is the first symmetric block cipher algorithm recommended by National Institute of Standards and Technology (NIST) in 1977. Only one key is used for both encryption and decryption. As shown in Fig 4, it is 64 bit block cipher so it can encrypt 64 bits of data at a time. Out of 64 bits only 56 bits are used to make independent key and the other 8 bits are used as parity bits for detecting errors. There are total 16 round for each processing. It follows Feistel structure that makes sure that both encryption and decryption have similar processes but there is only one difference that for decryption the keys are applied in a reverse order. The main limitation of this algorithm its is more likely to have brute force attack.

<img width="400"  src="https://user-images.githubusercontent.com/84442255/129943351-8dee8015-8547-48df-9a4b-ba6997f3a519.png">


#### 3DES- Triple Data Encryption Standard

3DES is a symmetric block cipher and was published in 1995 to overcome the attacks faced by DES. In Fig 6, it is seen that triple data encryption standard applies DES algorithm three times to each block of data which means there are total 48 rounds in 3DES algorithm. It uses three keys each of 56 bits(excluding 8 bits of parity). There are three keying options available. In first, all the three keys are treated as independent with 3*56=168 bits. In second, two keys are treated as independent with key length 2*56=112 bits. In third, all the three keys are treated as identical. It is more secure than DES but it requires three times more computation power than DES.

<img width="400"  src="https://user-images.githubusercontent.com/84442255/129943383-f07aa124-6568-49f2-9000-1f356635ca65.png">


#### AES- Advanced Encryption Standard

AES is symmetric and block cipher algorithm. National Institute of Standards and Technology (NIST) published AES in 1998 and was developed by two belgian Vincent Rijmen and Joan Daemen. AES uses 128 bit block size for encryption and decryption as shown in Fig 7. Key size depends on the number of rounds. Different key size are 128 bits(10 rounds), 192 bits(12 rounds) or 256 bits(14 rounds). Each round consists of 4 basic operations known as Sub-byte(), Shift-row(), Mix-column() and Add-roundkey().AES is widely used for small devices and is less power consuming.

<img width="400"  src="https://user-images.githubusercontent.com/84442255/129944469-76ecbd6d-6f00-4460-bd4c-d8f7dc92b082.png">


## Results and Discussion

In the table below, a comparative study is presented of three symmetric encryption algorithms (AES, DES and 3DES) into twelve factors namely block size, key size, development, structure of algorithm, number of rounds, attacks, avalanche effect, type of key, speed of algorithm, consumption of memory and efficiency.The results are based on qualitative research.

<img width="900"  src="https://user-images.githubusercontent.com/84442255/129944779-394a0da8-9a4b-4f60-bed7-a9dd6837c8b1.png">

The block size for DES and 3DES is same while AES uses 128 bits.

The security of any algorithm is highly based on the length of key being used. In the table, it is clear that the key size of AES algorithm is high and that of DES is lesser. Hence it can be said that security of AES is far better than the other two algorithms.

DES is the first symmetric encryption algorithm in 1974 by IBM and in 1976 by National Institute of Standard and Technology(NIST){\cite{b12}}. To overcome the drawbacks and attacks of DES, 3DES was developed in 1978 by IBM and in 1995 by NIST. In 1998, NIST developed a new symmetric encryption algorithm called AES.

The survey shows that DES and 3DES has Fiestal network structure while AES has substitution and permutation network. It also provides information on the number of rounds each algorithm performs. It is seen that DES and 3DES has fix number of rounds while round in AES depends on the key size.

Every algorithm is vulnerable to one or other attack. Brute force attack is the most common observed in three of the algorithms. Also they are vulnerable to other attacks. In DES, it also seen that a small change in plain text or key size makes a significant change in cipher text which is known as Avalanche effect. The other two algorithms also possess avalanche effect but not stronger than DES. All the three algorithms uses one private key for both encryption and decryption process.

In comparison to prior implementations, the Advanced Data Encryption standard offers a more secure and robust encryption approach.Triple DES is more secure than previous DES implementations, but it uses a lot of CPU power.In terms of performance, AES is shown to be superior to DES and 3DES.

According to the table, the Advanced encryption standard is adequate for providing security and managing computation power; however, triple DES is more secure because it uses three keys for the same operation, but the compute power is relatively large. The survey depicts that the efficiency of AES is highest as compared to DES and 3DES.


## Conclusion

This research provided a detailed study on cryptography and some symmetric encryption algorithms such as AES, DES and 3DES. With the rapid increase in the usage of internet and network, it has become necessary to secure the data or information transmitted over the network. Different encryption methods are used to provide security to data and network. In this research, a discussion on cryptography and symmetric encryption algorithms has been done. Also, a comparison analysis is performed on three different symmetric encryption algorithms (AES, DES, 3DES). It is observed that many researchers have repeatedly analysed and studied symmetric encryption algorithms. If the key size increases ,the algorithms are more optimize for encryption. Every algorithm has its own features which might be suitable for various applications and also has its own advantages and disadvantages. According to the literature survey and research on comparative study, it is concluded that AES is the best one in terms of better performance, speed, time, key length, rounds and block size as compared to DES and 3DES.

## References 

[1] https://www.ijser.in/archives/v2i11/SjIwMTM0MDM=.pdf

[2] https://www.researchgate.net/publication/317615794_Advanced_Encryption_Standard_AES_Algorithm_to_Encrypt_and_Decrypt_Data

[3] https://ejmcm.com/article_5157_596c1024e1fb468438347e8ab5322db2.pdf

[4] https://www.researchgate.net/publication/266872600_A_Comparative_Survey_on_Symmetric_Key_Encryption_Techniques

[5] https://academic.csuohio.edu/yuc/security/Chapter_06_Data_Encription_Standard.pdf


##  Acknowledgment

I would like to express my gratitude to my professor, Dr. Trevor M. Tomesh, who has always been my driving force behind completing the paperwork. My profound gratitude to The Management, as well as the computer science department staff at Lakehead University in Thunder Bay, Ontario, Canada, for their encouragement and motivation.

