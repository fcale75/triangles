# Auxiliary files for the paper "Fields of definition for triangle groups"

All files are written in magma unless they have the form file.nb, in 
which case they are mathematica files.

## Proof that $\mathrm{min}(p,q,r) \ge B$ for various B
- 33bound
- 885bound
- 33bound.out
- 885bound.out

These files prove that there are no exceptions to the Hilbert series
for n = 1..33 and n= 34..885 respectively. 

Running time: 267 hours. (Also executed in parallel on
100 cores.)

## Proof of Theorem D
### Codimension two case

- cross
- crossstrict
- datacross
- cross.out
- crossstrict.out

The file cross verifies Theorem D for the 266743 triples in the 
codimension 2 case. 

The file crossstrict verifies the stronger version of the 5-Lemma on
the same triples now with the lower bound 1 + 5/24 > 1+1/5.

Both of these use the same data file datacross.

Running Time: 70 seconds and 76 seconds respectively.

- ComputingMoments.nb

This file is used to compute the averages $E[(e(t)-24)^{12}]$
in the generic place and on hyperplanes, as well as computing 
the list of exceptional hyperplanes, as well as the 266743 
exceptional lines. Running times are indicated in the file.

Running Time: 20 minutes to compute the hyperplane integrals,
5 minutes for generating the list of exceptional lines.

- BadLines.nb

This file computes the lines of small height on the exceptional hyperplanes.

### Codimension 1 case

- badlines
- databadlines
- badlinesstrict
- databadlinesstrict
- badlines.out
- badlinesstrict

badlines verifies the 5-Lemma for the low height lines on the
14 exceptional hyperplanes. 

badlinesstrict verifies the stronger version with the stronger lower bound 1+5/24 > 1+1/5.

There are two data files, since for the stronger lower bound the height bounds are slightly different.


Running Time: 20 seconds each.

## Miscellaneous

- smallbox
- bigbox
- smallbox.out
- bigbox.out

These programs are used to verify Lemma 4.3.1 and 4.3.2 respectively.

Running Time: 7 seconds each.
