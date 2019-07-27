TODO: Reflect on what you learned this week and what is still unclear.
def recur_fibo(n):
    if n <= 1:
       return n
    else:
        return recur_fibo(n-1) + recur_fibo(n-2)

print(recur_gibio(4))
  4的话输出的n=3
# 1 1 2 3 5 8 13 21 34
