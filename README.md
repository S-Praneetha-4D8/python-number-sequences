a=list()                 
for i in range(1,111,3):   #-->generation of numbers with step size 3  
    print(i,end=' ') 

'''printing the 23rd element in the odd series numbers ranging from 200-300 using list and range function'''
term=int(input('enter the term value'))
odd_nums=list(range(201,300,2))
print(odd_nums)
print(odd_nums[term-1])

'''print the descending numbers with in a given range 49 47 45 43 using a for loop'''
for i in range(49,39,-2):
    print(i,end=' ')
