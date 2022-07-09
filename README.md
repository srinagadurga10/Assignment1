# Assignment1
s=input()
o=''
for i in s:
    if i.isdigit():
        o=o+i
print(*set(o))
