# palindrome.py

numbers = [3,4,1,9,6,2,8]
print(numbers)
x = int(input("Enter the position of the element to be deleted: "))
numbers.pop(x)
print(numbers)


output:
[3, 4, 1, 9, 6, 2, 8]
Enter the position of the element to be deleted: 4
[3, 4, 1, 9, 2, 8]

