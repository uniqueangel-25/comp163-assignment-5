# comp163-assignment-5
print("=== Challenge 1: Collatz Conjecture ===")
current_number = int(input("Enter starting number: "))
print(f"Sequence: {current_number} ", end="")
step_count = 0

while current_number != 1:
    if current_number % 2 == 0:
        current_number = current_number // 2
    else:
        current_number = (3 * current_number) + 1
    print(f"{current_number} ", end="")
    step_count += 1

print(f"\nSteps: {step_count}\n")

print("=== Challenge 2: Prime Number Checker ===")

n = int(input("Enter a number: "))

while n <= 1:
    n = int(input("Please insert a number greater than 1: "))
print(f"Testing divisors from 2 to {n-1}...")
is_prime = False

for i in range(2,n):
    if n % i == 0:
        is_prime = True
        break
if is_prime:
    print(f"{n} is not prime (divisible by {i})")   
else:
    print(f"{n} is prime!")
