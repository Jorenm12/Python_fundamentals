# Python_fundamentals
for_loops_basics_1

#first
for i in range(0,150,1):
    print(i)

#second
for i in range(5,1000,1):
    print(i*5)


#Third
def counting_dojo():
    for i in range (1,100,1):
        if i % 5 == 0:
            print ('Coding')
        if i % 10 == 0:
            print ('Coding_Dojo')

counting_dojo()

#fourth

min = 0
max = 500000
Oddtotal = 0

for number in range(min, max+1):
    if(number % 2 != 0):
        print("{0}".format(number))
        Oddtotal = Oddtotal + number

print("The Sum the following numbers from {0} to {1} = {2}".format(min, max, Oddtotal))

#fifth

def count_four():
    number = 2018
    while number > 0:
        print (number)
        number = number - 4
        
count_four()


#six

def flex_countdown(low, high, mult):
    for i in range (low, high):
        if i % mult == 0:
            print (i)
            
flex_countdown(2, 9, 3)
