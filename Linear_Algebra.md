# Linear_Algebra TIL

## 2023-04-05
- LU 분해

## 2023_04_06
- $(AB)^{-1} -> B^{-1}A^{-1}$
- $(AB)^T -> B^T * A^T$
- $Ax = 0$ -> 동차 연립방정식
- $LU$ 분해
  - $U의 첫번째 행 \rarr A의 첫번째 행$
  - $L의 첫번째 열 \rarr A의 첫번째 열 / U의 첫번째 성분$ `(첫번째 행의 대각성분)`
  - $u_{ij} = a_{ij} + \displaystyle\sum_{k=0}^{i-1} \ l_{kj}u_{ik}$ 


  - $l_{ij} = (a_{ij} + \displaystyle\sum_{k=0}^{j-1} \ l_{kj}u_{ik} ) / u_{jj}$ 