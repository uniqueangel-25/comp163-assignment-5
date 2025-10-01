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
