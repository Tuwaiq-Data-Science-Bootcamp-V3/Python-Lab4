# Python-Lab4
## Functions
### Create a function that takes one parameter of type int, then it prints out the result formatted like the following pattern (if we give it 5 for example):
5 4 3 2 1   
4 3 2 1   
3 2 1   
2 1   
1   
--------------------------------------------------------------------
InteredNumber = int(input('Please Enter a number:  '))
for i in range(0, InteredNumber+1 ):
    for j in range(InteredNumber - i, 0, -1):
        print(j , end=' ')
    print('')
