# Fibonacci-by-python 
def fibnoseries(n):

    f=0

    s=1

    print(f,s,end=' ')

    for i in range(2,n):

        next=f+s

        print(next,end=' ')

        f=s

        s=next

n=int(input())

fibnoseries(n)
