# list-without-duplicates
list=list(map(int,input().split()))
a=[]
for i in list:
    if i not in a:
        a.append(i)
print("the list after deleting duplicates:")
for i in a:
    print(i,end=" ")
        
