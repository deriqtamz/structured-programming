# structured-programming

#no a

input_list = [1,2,3,4,5,6,7,8,9]

even_list = []
for num in input_list:
    if num  % 2 == 0:
        even_list.append(num)
    print("even numbers in the list",even_list)
    
 
#no b

#prog for a multiplication table for given number up to 12

def print_multiplication_table(numb):
    for i in range(1, 13):
        print(f"{numb} x {i} = {numb*i}")

#test for multiplication table
numb =int(input("enter a number:"))
print_multiplication_table(numb)

#no c

# prog that finds the largest number in a list without using the max function

def find_largest_number(input_list):
    largest = input_list[0]
    for num in input_list:
        if num > largest:
            largest = num

input_list = [69,2,84,10]

print("largest number in the list", find_largest_number(input_list)) 


# no d

# strings
check_string_identity(input_string,comp_string):
input_string :original input_string
comp_string : comparison_string
 return input_string ==  comp_string

if   check_string_identity(input_string,comp_string):
     print("the string are identical.")
else: print("the strings are not identical")
