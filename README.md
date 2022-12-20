# Day8_query-string

s=input()
len1=len(s)
str1=""
l=[]
query=sorted(set(input().split()))
for i in query:
    if((i[0:len1])==s):
        print(i)
