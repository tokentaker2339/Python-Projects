flag = False
finallist=[]
name1 = input("Enter your name\n")
name2 = input("Enter your crush's name\n")
name1=name1.lower()
name2=name2.lower()
list1=list(name1)
list2=list(name2)
for i in list1:
    for j in list2:
        if i==j:
            flag=True
    if flag==False:
        finallist.append(i)
    flag=False
        
for i1 in list2:
    for j1 in list1:
        if i1==j1:
            flag=True
    if flag==False:
        finallist.append(i1)
    flag=False
    
x=len(finallist)
print("Number of unmatched letters are {}".format(x))

test='FLAMES'
test=list(test)

while len(test)!=1:
    if x>len(test):
        x1=x%len(test)
        test.pop(x1-1)
    else:
        test.pop(x-1)
    print (test)   
mydict={'F':'Friends','L':'Lovers','A':'Attraction','M':'Marriage','E':'Enemies','S':'Siblings'}
print("\nYour relationship status is : {} ".format(mydict[test[0]]))
