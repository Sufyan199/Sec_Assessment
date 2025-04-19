a = 15
b = 4


c = a-b
d = a/b
e = a//b
f = a%b
g = a/b
print(c )
print(d )
print(e )
print(f )
print(g )

#Q: 2:

num1 = 10
num2 = 5.6
num3 = 4.43

print(float(num1))
print(int(num2))
print(str(num3))

#Q3:

fruits = ["apple", "banana", "cherry", "coconut", "pineapple", "mango", "orange"]

print(fruits [0])
print(fruits [-1])
print(fruits [5])

#Q4 : 

numbers = [10, 20, 30, 40, 50]

print(numbers[0 : 3])
print(numbers[3 : ])
print(numbers[1 : ])
print(numbers[ : 1])
print(numbers[::-1])
print(numbers[0 :len(numbers):2 ])


#Q5 :

nums = [1, 2, 3]
nums.insert(1, 99)
print(nums)

nums = [1, 2, 3]
nums.extend([4, 5])
print(nums)


nums = [4, 1, 3, 2]
nums.sort()
print(nums)


order = ["burger", "fries", "coke"]

order.append("ice cream")

order.remove("biryani")
print("Final order:", order)


passengers = ["Ali", "Zara", "Ahmed"]
passengers.insert(2, "Sara")
passengers.remove("Zara")
passengers.reverse()
print("Passengers in order of entry:", passengers)
