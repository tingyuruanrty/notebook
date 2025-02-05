[course lecture link](https://www.youtube.com/playlist?list=PLSt7rwoPGTy10qdPeuqzC-qn5zeHCYoSf)
# 1. The matrix-vector multiplication problem
![[Pasted image 20250204141857.png]]
![[Pasted image 20250204142104.png]]
![[Pasted image 20250204140834.png]]
![[Pasted image 20250204142632.png]]**A** is an arbitrary matrix of m rows, n columns
x is an arbitrary vector of n rows
b is a vector of m rows
![[Pasted image 20250204143542.png]]
## in matrix vector multiplication problem, the inner dimensions must agree
![[Pasted image 20250204144826.png]]

## forward problem
![[Pasted image 20250204150729.png]]
give input, give out output

# 2A. nonsingular linear systems problem
![[Pasted image 20250204150424.png]]
## backward problem
![[Pasted image 20250204151205.png]]
## what is nonsingular matrix?
![[Pasted image 20250204153559.png]]
**2a is a special case of backward problem for problem 1**

# 2B. general linear system problem
contrast to 2a, A could be singular or rectangular
![[Pasted image 20250204155113.png]]
find all possible unknown x vector such that A \* x = b
out put is definitely hit by the function, and when the function is one to one
![[Pasted image 20250204161413.png]]
output hit by the function is in the range, but the function is one to one
![[Pasted image 20250204161438.png]]
output vector given is not hit by the function
![[Pasted image 20250204161501.png]]
## 

# aside
![[Pasted image 20250204160420.png]]
full column rank: one to one