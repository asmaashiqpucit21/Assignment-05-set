# Assignment 05: -

### 1. Create an empty set and print it.


```python
empty_set = set()
print(empty_set)
set()

```

    ()
    




    set



 ### 2. Create a set of your favorite colors and print it.


```python
fav_colours = {"Red", "Green", "Blue", "Purple"}
print(fav_colours)

```

    {'Red', 'Green', 'Blue', 'Purple'}




    set



### 3. Create a set that includes a mix of data types (integers, strings, floats).


```python
mixed_set = {1, "GIS & RS", 3.15}
print(mixed_set)
```

    {1, 3.15, 'GIS & RS'}
    




    set



### 4. "Access the elements of a set using a loop and print each element."
   

```python
# Create a set
my_set = {20, "orange", 3.15, (2, 4)}	
# Accessing elements using a loop and print each element
for element in my_set:
print(element)
```

    orange
    3.15
    20
    (2, 4)
    

    

### 5. "add a new element to a set using the add() method."
  


```python
my_set = {1, 2, 3}
my_set.add(4)
print(my_set)
```



    {1, 2, 3, 4}




### 6. "Add multiple elements to a set using the update() method."


```python
my_set = {1, 2, 3}
my_set.update({4, 5, 6})
print(my_set)
```

    {1, 2, 3, 4, 5, 6}
    

### 7. "Remove and return an arbitrary element from a set using the pop() method."
  

```python
my_set = {1, 2, 3}
remove_element = my_set.pop()
print(remove_element)
```
   
    remove_element = 1

my_set = {1, 2, 3}
return_element = my_set.pop()
print(return_element)

    return_element = 1
    

### 8. "Remove a specific element from a set using the remove() method."
   


```python
my_set = {1, 2, 3, 4, 5}
my_set.remove(3)
print(my_set)
```

    {1, 2, 4, 5}
    

### 9. "Remove a specific element from a set using the discard() method."
   

```python
my_set = {1, 2, 3, 4, 5}
my_set.discard(3)
print(my_set)
```

    {1, 2, 4, 5}
    

### 10.  "Convert a string to a set of unique characters."
   

```python
string = "ASMA ASHIQ"
unique_characters_set = set(string)
print(unique_characters_set)
```

    {'H', 'S', ' ', 'M', 'I', 'A', 'Q'}
    

### 11. "Convert a set of characters to a string."


```python
Set_of_characters = {'A', 'S', 'M', 'A', 'A', 'S', 'H', 'I', 'Q'}
new_string = ''.join(Set_of_characters)
print(new_string)
```

    QSIHAM
    

### 12.  "Use the clear() method to remove all elements from a set."
   

```python
my_set = {1, 2, 3, 4, 5, 6}
my_set.clear()
print(my_set)
```

    set()
    

### 13. "Use the copy() method to create a shallow copy of a set."
   


```python
original_copy = {1, 2, 3, 4, 5, 6}
shallow_copy = original_copy.copy() 
print(shallow_copy)
```

    {1, 2, 3, 4, 5, 6}
    

### 14.  "Use the difference() method to find the difference between two sets."
   

```python
set1 = {1, 2, 3, 4, 5}
set2 = {1, 2, 8, 9, 10}
defference_set = set1.difference(set2)

```

    {3, 4, 5}
    

### 15.  "Create two sets and find their union."
   


```python
set1 = {1, 2, 3}
set2 = {4, 5, 6}
union_set = set1.union(set2)
print(union_set)
```

    {1, 2, 3, 4, 5, 6}


### 16.  "Create two sets and find their intersection."
   


```python
set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}
intersection_set = set1.intersection(set2)
print(intersection_set)
```

    {4, 5}
    

### 17.  "Create two sets and find their difference."
  

```python
set1 = {1, 2, 3, 4, 5}
set2 = {3, 4, 5, 6, 7}
difference_set = set1.difference(set2)
print(difference_set)
```

    
    {1, 2}


### 18. "Create two sets and find their symmetric difference."
   

```python
set1 = {1, 2, 3, 4, 5}
set2 = {3, 4, 5, 6, 7}
symmetric_difference_set = set1.symmetric_difference(set2)
print(symmetric_difference_set)
```

    {1, 2, 6, 7}
    

### 19. "Check if one set is a subset of another."
   

```python
set1 = {1, 2, 3, 4, 5}
set2 = {2, 4}
is_subset = set2.issubset(set1)
print(is_subset)
```

    {2, 4}
    True
   

### 20. "Check if one set is a superset of another."
   

```python
set1 = {1, 2, 3, 4, 5}
set2 = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
is_superset = set2.issuperset(set1)
print(is_superset)
```

   True
    

### 21.  "Check if two sets are disjoint (have no common elements)."
   

```python
set1 = {1, 2, 3, 4, 5}
set2 = {6, 7, 8}
are_disjoint = set1.isdisjoint(set2)
print(are_disjoint)
```

    True

    

