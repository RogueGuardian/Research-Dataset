# Research-Dataset
A repository of the dataset used in my thesis work.

---

## What and Why
Currently within the zip file there are many folders, but 4 of them start with `TYPE`.
These are the four folders which contain the testcases used in my research.

The other folders are CWEs which might be able to be added to the categories presented but, for purposes of a proof of concept, they were left out.
Similarly there are a few CWE folders which are not present from the original NIST Juliet-C/C++ dataset.
These were removed because they were either such a specific case (there were only a handful of files in the folder itself) or that a "bug" is just bad coding practices (such as leaving passwords in comments) or were specific to something else (weak PRNG or unique to OS operations).
These were removed as we found that these were rare cases in general and only applied to specific instances which, again to build a proof of concept, were omitted.

---

## Notebook
Also included is the python notebook with all the parsing, testing, and analysis code I used.
It is definetly not the cleanest nor the prettiest code, and it is clearly meant for python-notebook style usage, but it works.
