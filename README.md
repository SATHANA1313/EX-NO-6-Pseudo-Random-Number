# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
import random
def main():
    n = int(input("Enter how many random numbers to generate: "))
    print("Generated Random Numbers:")
    for _ in range(n):
        print(random.randint(0, 2**31 - 1), end=" ")  # randint to mimic C's rand() range
if __name__ == "__main__":
    main()
```
# OUTPUT:
<img width="1692" height="792" alt="Screenshot 2025-09-18 082749" src="https://github.com/user-attachments/assets/079f0b64-92a4-4830-8fd3-b66decd7c548" />

# RESULT:
The above program is executed in Implementation of Pseudorandom Number Generation Using Standard library
