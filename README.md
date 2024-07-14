# Assignment5
num=int (input("enter number: "))
for i in range(num):
  fact=1
  x=1
  while x<=num:
    fact=fact*x
    x=x+1
  print("factorial",num,"is",fact)
