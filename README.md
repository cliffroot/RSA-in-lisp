RSA-in-lisp
===========

RSA encryption and decryption written is lisp. 

The implementation of RSA algorithm. It features probabilistic Miller-Rabin primality test to generate 2 prime numbers fast enough. First it generates 355 consequent numbers in which there should be (according to prime number distribution) one prime number with P(A) ~ 0.37. Then it tests all the numbers, if it fails to find a prime, we repeat the procedure. 

After that, the canonical RSA is implemented. 
