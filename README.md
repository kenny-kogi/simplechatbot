# simplechatbot
print("Hello! My name is Aid.")
print("I was created in 2020.")
print("Please, remind me your name.")

name = input()

print("What a great name you have,", name, "!")
print("Let me guess your age.")
print("Enter remainders of dividing your age by 3, 5 and 7.")

r3 = int(input())
r5 = int(input())
r7 = int(input())

age = (r3 * 70 + r5 * 21 + r7 * 15) % 105
print("Your age is", age, ": that's a good time to start programming!")
print("Now I will prove to you that I can count to any number you want.")

number = int(input())
counter = 0
while counter <= number:
    print(counter, "!")
    counter += 1
determinant = True
while determinant:

    print("Let's test your programming knowledge.")
    print("Why do we use methods?")
    print("1. To repeat a statement multiple times.")
    print("2. To decompose a program into several small subroutines.")
    print("3. To determine the execution time of a program.")
    print("4. To interrupt the execution of a program.")

    ans = int(input())


    def question_1(answer):
        if answer == 2:
            global determinant
            determinant = False
            print("Completed, have a nice day!")
            print("Congratulations, have a nice day!")

        else:
            print("Please, try again.")


    question_1(ans)
