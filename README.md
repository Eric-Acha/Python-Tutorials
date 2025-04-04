#One of the unique features of Tuples
##Normally every data structure creature has its unique location in the memory
But when you create two Tuples chronologically and assign them the same values,
the proceeding tuple does not take effect as it assumes it is the preceding tuple.

If you try running the code below you will see that the two tuples are the same as they are in the same space in the memory. 

t1 = 1, 2, 3

t2 = 1, 2, 3

print(id(t1), id(t2))
