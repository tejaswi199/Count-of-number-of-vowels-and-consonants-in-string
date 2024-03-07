#Approach-1
s=input()
z="aeiouAEIOU"
v=0 
c=0 
for i in range(len(s)):
  if s[i] in z:
    v=v+1 
  else:
    c=c+1
print(v,c)

#Approach-2
s=input()
z="aeiouAEIOU"
v=0 
c=0 
for i in range(len(s)):
  if s[i].isalpha():
    if s[i] in z:
      v=v+1 
    else:
      c=c+1
print(v,c)

#Approach-3
s=input()
z="aeiouAEIOU"
v=0 
c=0 
for i in s:
  if i.isalpha():
    if i in z:
      v=v+1 
    else:
      c=c+1
print(v,c)
print(v,c)
