#list with in a list
list=[[1,2],[3,4],[5,6]]
print(list[0])

#list within a tuple
#accessing the list
student=("Vijay",[22,40,90,],['Math','Science','English'])
print(student[0])
print(student[1])
print(student[2])
print(student[2][1])

#tuple sample
info=("Vijay",33,'engineer')
print(info[2])
print(info[0])
print(len(info))
print(info*2)
print(info + ('4000',4))

#tuple sample
info=("Vijay",33,'engineer')
print(info[2])
print(info[0])
print(len(info))
print(info*2)
print(info + ('4000',4))
#list functions
fruits=['apple','banana','cherry']
print(fruits[2])
print(fruits*2)
print(fruits + ['kiwi'])

#tuple(mixture of character and tuples)
nest=((1,2),('a',7),(5,6))
print(nest[1])
print(nest[1][0])

#dictionary opeartions
person={'name':'Sravya','age':22,'city':'Mumabai'}
print(person)
print("accessing and modify the person age:")
person["age"]=20
print(person)
print("adding and removing items")
person['email']='sravyaladdika22@gmail.com'
print(person)
print("all keys and values")
print(person.keys())
print(person.values())
print(person.items())
print(person.get("age"))
