# python-4
Write a python program to compute the result when two numbers and one operator is given by user.
import datetime
td=0
now=datetime.datetime.now()
print(now.day)
if now.month==2:
    td=28
elif now.month in(1,3,5,7,8,10,12):
    td=31
else:
    td=30
print("Total remaining days in the current month are:" ,td-now.day)
Output
3
Total remaining days in the current month are: 28
