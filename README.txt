README for [Codes and results for "On the intersection of Cantor sets and products of random matrices"]


This issue contains the scripts used in the proof of my paper "On the intersection of Cantor sets and products of random matrices".

See "Supplementary for Lemma 3.5.pdf" for the values of p,q and the information on change of variables. 

The files # NAC checker for Lemma 3.5 v2 (b from 7 to 21).txt and "# NAC checker for Lemma 3.5 v2 (b over 21).txt" are python scripts saved in .txt file. These files were ran in the following environment.


Operating system: Windows 11 (64-bit)

Python: Python 3.13.5 (64-bit)

Floating-point library:
NumPy’s double-precision float64

Interval arithmetic libraries:
decimal (Python standard library) with directed rounding (ROUND_FLOOR, ROUND_CEILING)
mpmath (version compatible with Python 3.13) using outward-rounded mpi intervals

Other libraries
time, sys, fractions, itertools, math, numpy


To reproduce the NAC check for 7 ≤ b ≤ 21:
python "NAC checker for Lemma 3.5 v2 (b from 7 to 21).txt"

To reproduce the NAC check for b ≥ 22:
python "NAC checker for Lemma 3.5 v2 (b over 21).txt"


The results for each scripts are the files "Result of # NAC checker for Lemma 3.5 (b from 7 to 21).txt" and "Result of # NAC checker for Lemma 3.5 (b over 21).txt", respectively.



Nima Alibabaei