
# AIM
  To Write a program in python to test whether a given number is prime or not

# ALGORITHM
  1. Start
  2. Input a number n
  3. If n is less than or equal to 1, print "n is not a prime number" and stop
  4. Set a flag is_prime = True
  5. Loop from i = 2 to sqrt(n):
  6. If n % i == 0, then:
  7. Set is_prime = False
  8. Break the loop
  9. If is_prime is True, print "n is a Prime Number"
  10. Else, print "n is not a Prime Number"
  11. End



# PROGRAM
```python
a = int(input())
if a%2==1:
    print(f"Given number {a} is a Prime Number")
else:
    print(f"Given number {a} is not a Prime Number")
```

# OUTPUT
![image](https://github.com/user-attachments/assets/ec6f0a10-b533-4543-b39c-2ec6793d3231)

# RESULT
  THUS THE EXPECTED OUTPUT IS ACHIEVED 
