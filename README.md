# Tuple-Methods
These methods are called directly on a tuple object

1.count(value): Returns the number of times a specified value occurs in the tuple.
my_tuple = (1, 2, 3, 4, 1, 1, 5)
count_of_ones = my_tuple.count(1)
# Output: 3


2.index(value, [start, [end]]): Searches for the specified value and returns the position (index) of its first occurrence. 
Optional start and end parameters can limit the search to a specific range.If the value is not found, a ValueError is raised.
my_tuple = ('apple', 'banana', 'cherry', 'apple')
index_of_banana = my_tuple.index('banana')
# Output: 1
