# Sugarcaneproblem
t=int(input())
for _ in range(t):
  n=int(input())
  total=n*50
  sc=int((20/100)*total)
  igd=int((20/100)*total)
  rent=int((30/100)*total)
  exp=sc+igd+rent
  print(total-exp)
