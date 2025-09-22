# Slice-and-Splice-Algorithm

The `frankenSplice` function takes two arrays and an index as input.  
It copies all elements from the first array into the second array, starting at the specified index.  
The original input arrays remain unchanged.

Parameters

-arr1 (Array): The array whose elements will be inserted.

-arr2 (Array): The array where elements from arr1 will be inserted.

-index (Number): The position in arr2 where the insertion starts.

Returns

-Array: A new array with elements of arr1 inserted into arr2.

Notes

-The original arrays arr1 and arr2 are not modified.

-Uses slice() to copy arr2 and splice() with the spread operator ...arr1 to insert elements.
