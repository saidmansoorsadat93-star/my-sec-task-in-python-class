# my-sec-task-in-python-class
# 1. List of favorite fruits
fruits = ["Apple", "Banana", "Mango", "Orange", "Grapes"]

print("Original List:", fruits)

# Add one fruit
fruits.append("Pineapple")

# Remove one fruit
fruits.remove("Banana")

print("Updated List:", fruits)


# 2. Tuple containing name, age, and city
person = ("Ali", 20, "Lahore")

print("\nName:", person[0])
print("Age:", person[1])
print("City:", person[2])


# 3. Set of numbers
numbers = {1, 2, 3, 4, 2, 3, 5}

print("\nOriginal Set:", numbers)

numbers.add(6)

print("Updated Set:", numbers)


# 4. Dictionary
student = {
    "Name": "Ali",
    "Age": 20,
    "Course": "Python"
}

print("\nName:", student["Name"])

# Update age
student["Age"] = 21

# Add city
student["City"] = "Lahore"

print("Updated Dictionary:", student)


# 5. Convert list into a set
num_list = [1, 2, 3, 4, 5, 3, 2, 6, 7, 8]

unique_values = set(num_list)

print("\nOriginal List:", num_list)
print("Unique Values:", unique_values)
