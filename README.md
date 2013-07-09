AES encryption agorithm implemented in Matlab for a University of California, Merced CSE 178 Computer Security and Network Security class
------------------------------------------------------------------------------------------------------------------------------------------

Takes input of a hexadecimal plain text message and a 16 byte hexadecimal key.

1. key is expanded to a 176 byte key. 
2. First 4 words are bitxored with the plain text message. 
3. Nine rounds of byte substitution, shift rows, mix columns, and adding round key at the end.
4. During the final round: a byte substitution, shift rows, and add round key take place.