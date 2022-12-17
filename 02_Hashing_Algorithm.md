Day 2 of learning #blockchain<br>
--Hashing Algorithm--

Basically, a block present in a blockchain stores some information like:<br>
-Block number.<br>
-Data of transaction.<br>
-Previous hash.<br>
-hash.<br>
In blockchain, it is very much necessary for a block to identify the previous block connected with it. That's why each block stores the hash of previous block.<br>

What is hash?<br>
In simple words, Hash is basically the fingerprint of the block, It is unique for each block. It is a 64 hexadecimal characters encrypted data, Encrypted by SHA256 algorithm.<br>

How SHA256 algorithm works?<br>
It basically converts the data into a 64 hexadecimal characters.<br>

Doc,mp4,audio,etc --> SHA256 algo --> encrypted 64 characters.<br>
each character is of 4 bits so in total it has 256bits.<br>

5 Requirements of hashing algorithm :-<br>
1) It should be one way.<br>
--> It should be possible to encrypt the given data but, Decryption of the encrypted data must not be possible.<br>

2) Deterministic.<br>
--> For one input it gives the same output always. for eg,<br>
ABC (input data) -->SHA256-->123...DA23 (always returned when ABC is passed in SHA256)<br>

3)Fast computation.<br>
--> Formation of encrypted data should be very fast in order to make blockchain.<br>

4)Withstand collisions.<br>
-->Cannot be hacked by hackers.<br>

5)Avalanche effect.<br>
-->A very very small/negligible change in data will change the encrypted data completely.<br>
NOTE : First block in a blockchain is known as, Genesis Block.<br>
![day2](https://user-images.githubusercontent.com/92376931/208231267-a8fbffbb-e7fd-4260-84eb-843dfcd6864d.jpg)
