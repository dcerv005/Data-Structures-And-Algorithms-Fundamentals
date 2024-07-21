Question 2

def simple_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]

Task 1

The above functionis used to sort the array of numbers from lowest to highest. For example is arr[0] is greater than arr[1] then the function switches the indexes values.

Task 2

The Big O Notation for the function above would be linear, depicted as: O(n). The bigger the array the more the function has to cycle through the indeces.

Task 3

A potential imporvement would be to simply use the sort() method for this array. An arr.sort(), would sort the numbers in ascending order. 

