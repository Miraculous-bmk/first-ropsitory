# first-ropsitory
i = 0
total = 0
nunber = int(input("Enter a number "))
if nunber == 0:
    print("Enter a number greater then zero")
    exit()
while True:
    total = (total + nunber)
    i = i + 0
    nunber = int(input("Enter another number: "))
    if nunber == 0:
        print(f"Total is {total + i}")
        break
