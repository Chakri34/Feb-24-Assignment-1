# Feb-24-Assignment-1
n=int(input("Enter range of list: "))
lst=[]
count=0
for q in range(1,n+1):
    lst.append(q)

for num in lst:
    if num>1:
        for j in range(2,num):
            if (num%j)==0:
                break
        else:
            count=count+1
print("number of prime numbers in list is : ",count)
