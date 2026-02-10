## Data-Encryption-Standard
# Practical implementation by hand

Data encryption standard is a symmetric key (same key for encryption and decryption) algorithm for the protection of digital data. It was developed in the early 1970s by IBM and was published as an official federal information processing standard in 1976. Messages are encrypted in blocks of 64 bits

# Steps:
1. Selection of a 64 bits key
2. The key would undergo some permutations (rearranging the characters of the key and reducing it to 56 bits). After which 16 sub keys would be generated, each of 48 bits.
3. Permutation and division of the message block.
4. The output of step 3 is then passed through 16 rounds, each of which has identical operations. 
5. Output of the 16th round then undergoes a final permutation which then results in the cyphertext.
Additional message blocks are encrypted in the same way to obtain the cyphertext.
It is however, considered no longer secured and should not be used to build new systems. This is because of it's short key size of 64 bits. The example was not decrypted for the same reason.
In January 1999, the algorithm was broken in 22 hours and 15 minutes.
It has been superceded by the Advanced Encryption Standard (AES).
# Illustration is shown on the PDF file. 
