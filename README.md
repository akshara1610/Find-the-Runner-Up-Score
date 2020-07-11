# Find-the-Runner-Up-Score

Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given  scores. Store them in a list and find the score of the runner-up.

//Code

n = int(input())
arr =list(map(int, input().split()))
arr.sort()
a=len(arr)
maxs=arr[a-1]
lst=[]
for i in range(a):                           //removing the max score and entering all the other elements to a new list
    if arr[i]!=maxs:
        lst.append(arr[i])
lst.sort
v=len(lst)
print(lst[v-1])
