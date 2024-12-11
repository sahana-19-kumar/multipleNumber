number = int(input("Enter a number: "))
if number % 10 == 0:
    if number < 100:
        print(f"{number} is a multiple of 10 and less than 100.")
    else:
        print(f"{number} is a multiple of 10 but not less than 100.")
else:
    print(f"{number} is not a multiple of 10.")
