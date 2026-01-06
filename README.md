# Linear-Search-in-a-List

l=[2,58,95,999,67,35,35,77,1,2]
n=int(input("enter the number to be saerched:"))
found=0
for x in l:
    if x==n:
        print("item found at position:",l.index(n)+1)
        found=1
if found==0:
    print("item not found")

OUTPUT

enter the number to be saerched:2
item found at position: 1
item found at position: 1

