# blind-4-75
product of array exxcept self
may be the problem tries to address division by zero/multiplication by zero anamolies/performance related thing with respect to division.

anyways ,key point being the fact that we are allowed to use only one list/array .(not counted in space complexity purposes.

and that is what makes logic bit tricky.

I mean without that i can use left product variable to keep track of product of all left values except current index(at beginning it is 1).
then build left product array.
same can be done for right product variable ,by iterating from last element.
then build right product array.
multiply both to get final array/list.
but ,when given only single array,at first ,we store left product .
then use that and multiply right product variable in second pass.
time complexity; O(n)  2 iterations.
spaace complexity: O(1) noo extra space except the array which is returned
