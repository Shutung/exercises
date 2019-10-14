def Fibonacci():
    a= int(input('How many fibonacci numbers do you want to generate? '))
    l=[0,1]
    for i in range(1,a):
        b=l[i]+l[i-1]
        l.append(b)
    del l[0]
    print (l)
        

Fibonacci()        
