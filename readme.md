# Apricot Chameleon PC091-B
## 11B279 21

There is almost zero information online about this 1988 vintage computer motherboard. What information I have found is documented on Twitter in [this thread](https://twitter.com/DTL/status/1422919801475842049).

There are three EPROMS on the board:

1. *2764-20JL* **'S' ROM FONT 29BB**
2. *TMM27128AD-20* **PC286 HI 1-2-1**
3. *TMM27128AD-20* **PC286 LO 1-2-1**

These are in the git repo. The HI and LO ROMs need to be merged to form a 16-bit ROM for the 286 processor on the board. This is done in hardware on the board. Looking at the ROM images in a hex editor it seems they would be merged at some offset, as there is clear text at the start of both ROMs before thinsg become garbled by interleaving. 

[The Centre for Computing History
](https://t.co/R8O4M0eFnW?amp=1) has the only known complete computer using this board.

