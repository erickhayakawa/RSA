# RSA
Python program that simulate a RSA cryptography


The RSA algorithm involves four steps: key generation, key distribution, encryption and decryption.

A basic principle behind RSA is the observation that it is practical to find three very large positive integers e, d and n such that with modular exponentiation for all integers m (with 0 ≤ m < n):

{\displaystyle (m^{e})^{d}\equiv m{\pmod {n}}}{\displaystyle (m^{e})^{d}\equiv m{\pmod {n}}}
and that even knowing e and n or even m it can be extremely difficult to find d. The triple bar (≡) here denotes modular congruence.

In addition, for some operations it is convenient that the order of the two exponentiations can be changed and that this relation also implies:

{\displaystyle (m^{d})^{e}\equiv m{\pmod {n}}}{\displaystyle (m^{d})^{e}\equiv m{\pmod {n}}}
RSA involves a public key and a private key. The public key can be known by everyone, and it is used for encrypting messages. The intention is that messages encrypted with the public key can only be decrypted in a reasonable amount of time by using the private key. The public key is represented by the integers n and e; and, the private key, by the integer d (although n is also used during the decryption process. Thus, it might be considered to be a part of the private key, too). m represents the message (previously prepared with a certain technique explained below).
