# **LCCS Searching and Sorting Algorithms**
- **Note-** you need to be able to write a recursive and non-recursive version of each sorting algorithm
# Searching Algorithms
## Linear Search
### Algorithm in Pseudo-Code
1. Search each item in the list **from start to finish**
2. If you find the item, **return it's index**
3. If not, return the **lenght of the list, or -1**, whichever you wish

### Example of Linear Search
- **Input:** A list **L** and a search arguement of 14
- **Output:** Start at index 0 and check if it's equal to the search arguement, if not, keep going

```python
    L = [15, 4, 41, 13, 24, 14, 12, 21]

    L[0] == 14? No
    L[1] == 14? No
    L[2] == 14? No
    L[3] == 14? No
    L[4] == 14? No
    L[5] == 14? Yes!

    return 5 <--index
```

## Binary Search
- **Binary Search** is a search algorithm **used in a sorted array** by repeatedly dividing the search interval in half
- Because we repeatedly divide the search space, it is said to follow the **divide and conquer approach**

### Algorithm in Pseudo-Code
1. Sort the list
2. Set low = first item in the list
3. Set high = last item in the list
4. Set mid = (high + low)/2 <-- *Using floor division here*
5. If item at mid location, retun item, else, it must be to the left or the right of the middle value
6. If the value at the mid position is less than the target value
    - Set low = mid + 1
7. If the value at the mid position is greater that the target value
    - Set high = mid - 1
- **Repeat, Make sure low is never greater than high**

### Example of Binary Search
```python
    L = [2, 4, 5, 7, 8, 9, 12, 14, 17, 19, 22, 25, 27, 28, 33, 37]

    low = L[0] # low = 2
    high = L[len(L)-1] # high = list length - 1 --> high = 37
    mid = (low + high)/2 # Rounded down to lowest integer --> mid = 7

    if mid = 7:
        return mid
    elif mid < target:
        low = mid + 1

    #forget this, fix later lol.
```

# Sorting Algorithms
## Simple Sort Algorithm
### Algorithm in Pseudo-Code
1. Initialise an unsorted list
2. Initialise an empty sorted list
3. Repeat as long as there are items in the unsorted list:
    - Find the smallest item
    - Move the smallest item to the sorted list
    - Remove the item from the original list
4. Stop once there are no items in the unsorted list

```python
    L = [9, 6, 10, 4, 8, 5, 7]
    SortL = []

    
```
