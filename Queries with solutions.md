# Python
Exercise1

Exercises - Lists, Dictionaries, Tuples

THECODEX EXERCISES - Lists, Dictionaries, Tuples





#1. Create a list of names and print the second item.



list = [1,2,3,4,45]

print(list[1])



#2. Create a list of sports and then replace the second item with another sport.



sports = ['football', 'cricket', 'baseball', 'hockey']

sports[1] = 'icehockey'

print(sports)



#3. Create a list containing numbers and delete the fifth number from the array.



num = [0,1,2,3,4,5,6,7]

del num[5]

print(num)



#4. Create two lists of numbers and merge them.



num1 = [1,2,3]

num2 = [4,5,6]

num3 = num1 + num2

print(num3)



#5. Create a list of numbers and find the length, minimum, and maximum.



numm = [12,13,40,50]

a= len(numm)

b= max(numm)

c= min(numm)

print(a,b,c)



#6. Create a dictionary of students and scores and print out a student’s score.



students = {'arun':12, 'vijay':15, 'varun':18, 'Jayy':20}

print(students['Jayy'])

print(students)



#7. Create a dictionary with the key being names and values being ages and then delete the second key/value pair.



newd = {'a':12, 'b':12, 'c':23, 'd':18}

del (newd['b'])

print(newd)

          



#8. Create a dictionary of names and ages and then print out all the keys and values



# The dictionary of names and ages

names = {

    'teena': 12,

    'seema': 17,

    'lisha': 18,

    'akanksha': 23

}



# Printing all the keys

print("Names:")

for name in names.keys():

    print(name)



# Printing all the values

print("\nAges:")

for age in names.values():

    print(age)





#9. Create a tuple of your favorite movies



tup =('ironman', 'avengers', 'spiderman', 'drstrange')

print(tup)



#10. Create a tuple and print all the items from the first to third index.



tup =('ironman', 'avengers', 'spiderman', 'drstrange')

print(tup[0:3])


