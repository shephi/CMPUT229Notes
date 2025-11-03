- RARS, incorrectly, zero extends constants expressed in hexadecimal

ex. andi s7, s3, 0xFF0

s3        = 1010 0011 0001 1111 1110 1100 0110 0010
0xFF0 = 1111   1111   1111    1111 1111 1111   1111 1111 -> 0xFF0 = 1111 1111 0000, sign extended!!!
s7        = 1010 0011 0001 1111 1110 1100 0110 0000
