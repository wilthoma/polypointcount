# polypointcount

This repository contains auxiliary files to our paper "Moduli spaces of curves with polynomial point counts".
Explicitly, there are the following programs:

- `Wt11Asymptotics.nb`: A Mathematica notebook that contains several smaller numerical verifications used in section 6 of the paper.
- `eulerchar13.ipynb`: A sage (jupyter) notebook that contains the computation of the weight 13 Euler characteristic. The results (a table) are displayed section 5 of the paper.
- `eulerchar11.ipynb`: A sage (jupyter) notebook that contains the computation of the weight 11 Euler characteristic of M_g. The non-vanishing of the Euler characteristic for 9<=g<=600 and g !=12 is used in the proof of the main result. Also, the file contains a smaller computation that enters `Wt11Asymptotics.nb`.
- `eulerchar11withp.ipynb`: A sage (jupyter) notebook that contains the computation of the non-equivariant weight 11 Euler characteristic of M_g,n.
(I.e., the difference to the previous file is that here n>0.)
 The results are not used in the main Theorems. This is used only for the verification of the main conjecture.


To run the Mathematica notebook, just open the file in Mathematica.
To run the sage code (`*.ipynb` files), download the files, run
```
sage -n jupyter
```
and open the files from the web interface of the jupyter server.