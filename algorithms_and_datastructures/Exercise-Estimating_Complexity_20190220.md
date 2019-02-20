
# Overview 

---

**Disclaimer**: this is intended to be a living document, not a traditional one which is written once and never updated. 
Check the updates on the Associated GitHub Repo

**Task**: Let's estimate complexity, both spatial and computational, for different problems


## Meta 

| Field         | value         |
| ------------- |-------------|
| Name      | Exercise - Estimating Complexity 20190220 |
| Description      | Exercises about complexity estimation of different algos      |
| Ver | 0.1      |
| Last Update | 2019-02-20      |



---

**Problem**: For a given NxN Matrix, estimate Computational Complexity of computing all the submatrixes

**Discussion**:

- to fully identify a submatrix it is necessary to define position (2 params) and size (2 params) inside the main matrix: so it is a total of 4 params all independet among them hence it is O(N⁴), in fact you need
O(N²) to produce W and H independently

- O(N²) to produce w \in [0, N-1] and h \in [0, N-1] indepedently

- in the case of a square submatrix you have the additional vinculus of W=H hence the size degrees of freedom decreases from 2 to 1 hence the final complexity is O(N³)

---




**Problem**: let's extend the above mentioned problem of submatrix computation adding the computation of the submatrix sum

**Discussion**:

- the complexity of the submatrix computation is fully maintained, in addition you have the complexity of the sum computation which basically means

- from a time perspective, to iterate over all the W*H submatrix elements it's O(N²) in time

- from a space perspective, it requires to track the partial sum so just O(1)



