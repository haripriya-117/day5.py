# day5.py
day5.py
n=6
a=[]
for i in range(n):
     x=int(input())
     a.append(x)

for i in a:
    print(i)

for i in range(len(a)):
        print(a[i])

#adding elements in list

print("A=" , a)
b=['a','s','d','g','h']
a+=b
print("Added another list:",a)

c=[2,3,4,5]
a.extend(c)

a.insert(4,"I am inserting an element")
print(a)

#deleting an element in list

del a[4]

print(a)

a.pop()
print(a)

a.remove(5)
print(a)

#store largest number from the list toa variable

list=[2,3,5,6,8,9]
max_i=max(list)
print("maximum number in list" , max_i)

#store smallest number from the list to variable

list=[3,4,5,7,8,9]
min_i=min(list)
print("minimum number in list",min_i)


#create tuple and print tuple in reverse

tuple=(45,26,67,78,34,56)
s=sorted(tuple)
print("tuple befors sorting",tuple)
print("reverse the tuple ",sorted(tuple,reverse=True))
print("sorted tuple",s)

rev=sorted(s,reverse=True)
print("reverse of sorted tuple is",rev)

#create tuple convert into list

tuple=[(2,3),(5,6),(8,6)]
result=[]
for t in tuple:
    for x in t:
        result.append(x)
print(result)
