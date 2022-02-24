# prime-count
n=int(input("enter a value: ")) def prime_count(n):     c = 0     for num in range(n):         if num &lt;= 1:             continue         for i in range(2, num):             if (num % i) == 0:                 break         else:             c += 1     return c print(prime_count(n))
