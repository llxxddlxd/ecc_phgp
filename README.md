eccphp
======

Simple elliptic curve cryptography in PHP, uses NIST's recommended curve P-521. The crypt uses EC-ElGamal, the sign uses ECDSA algorithms.

Commands:

 g                     Generate keypair

Generates security and public key into two separate file: sec.key and pub.key.


 s <seckey> <file>     Sign file
 v <pubkey> <file>     Verify signature

