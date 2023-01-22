# Fekete polynomials of principal characters. 

This Github repository contains the codes that we implemented in the paper [1]. 

## Main files.

- The file "Irreducible_test_for_f" verify the irreducibility of $f_n$ (and $g_n$) where $n=pq$ and $n \leq 6000$. 

- The files "Galois_groups_kp" for $k \in [3, 5, 7, 11 ]$ verify our conjecture about the Galois groups of $g_n$ and $f_n$ for $n$ of the form $kp$. These files have the same structure. More precisely, in the first part, we verify that the Galois group of $g_n$ is $S_m$ with $m=\deg(g_n)$ by finding the smallest triple $(q_1, q_2, q_3)$ described by Proposition 9.1 in the main text. In other words, we verify Conjecture 9.3 for those n. In the second part, depending on whether the discriminant of $f$ is a perfect square or not, we find the smallest prime number $q_4$ described by Proposition 9.5 (respectively Proposition 9.6) if the discriminant of $f$ is not a perfect square (respectively a perfect square). Together with the information about the Galois group of $g_n$ found in part I, we can then verify that the Galois group of $f_n$ is exactly what is predicted by Conjecture 9.9. 











## References 

[1] Shiva Chidambaram, Jan Minac, Tung T. Nguyen, Nguyen Duy Tan, Fekete polynomials of principal Dirichlet characters.
 
