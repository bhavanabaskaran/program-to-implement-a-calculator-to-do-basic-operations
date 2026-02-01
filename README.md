# program-to-implement-a-calculator-to-do-basic-operations
def add(x,y):
print(x+y)
def subtract(x,y):
print(x-y)
def multiply(x,y):
print(x*y)
def divide(x,y):
print(x/y)
print(&quot;Enter two numbers&quot;)
n1=input()
n2=input()
print(&quot;Enter the operation +,-,,/ &quot;)
op=input()
if op==&#39;+&#39;:
add(int(n1),int(n2))
elif op==&#39;-&#39;:
subtract(int(n1),int(n2))
elif op==&#39;&#39;:

multiply(int(n1),int(n2))
elif op==&#39;/&#39;:
divide(int(n1),int(n2))
else:
print(&quot; Invalid entry &quot;)
