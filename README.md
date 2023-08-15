# DAY-3-PYTHON-jupiter-notebook
#INDEXING AND SLICING
text = "i love india"
text[0]
'i'
text[2:]
'love india'
text[:5]
'i lov'
text[::-1]
'aidni evol i'
list = ["sai","kiran","nani","hari"]
print(list)
type(list)
['sai', 'kiran', 'nani', 'hari']
list
​
marks = [45,55,32,36,47,55,52]
marks.sort()
print(marks)
[32, 36, 45, 47, 52, 55, 55]
print(55 in marks)
True
print("sai" in list)
True
for names in list:
    print(list)
['sai', 'kiran', 'nani', 'hari']
['sai', 'kiran', 'nani', 'hari']
['sai', 'kiran', 'nani', 'hari']
['sai', 'kiran', 'nani', 'hari']
len(marks)
7
marks = [45,55,32,36,47,55,52]
max(marks)
55
marks = [45,55,32,36,47,55,52]
min(marks)
32
list = ["sai","kiran","nani","hari"]
list.clear()
list
[]
list = ["sai","kiran","nani","hari"]
list.insert(2,"appu")
print(list)
['sai', 'kiran', 'appu', 'nani', 'hari']
list = ["sai","kiran","nani","hari"]
list.reverse()
print(list)
['hari', 'nani', 'kiran', 'sai']
​
  Cell In[36], line 3
    print(true)
    ^
IndentationError: expected an indented block after 'if' statement on line 2


list = ["sai","kiran","nani","hari"]
hai = ["vani","krishna"]
list.extend(hai)
print(list)
['sai', 'kiran', 'nani', 'hari', 'vani', 'krishna']
list = ["sai","kiran","nani","hari"]
list.index("hari")
3
list = ["sai","kiran","nani","hari"]
list.pop(1)
'kiran'
list = ["sai","kiran","nani","hari"]
list.reverse()
list
['hari', 'nani', 'kiran', 'sai']
​
