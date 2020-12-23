# list_permutation_heap_algorithm_lotusscript
List permutation function based on Heap's algorithm, compatible with Lotus Script and Visual Basic

The initial call to the function can be done like this:

```
Dim PermutatedPairsList As ListOfVariant
Set PermutatedPairsList = ArrayPermutations(Array, Array.MaxIndex)
```

It assumes that Array is zero-based, and one-dimentional.

`ListOfVariant` is a custom class that stores a list of elements each is of a Variant datatype. This allows storing a whole array as an element in this List.
Eventually the function returns a ListOfVariant where each element is a copy of the original array but in a different ordering of the elements.

`ListOfVariant.AssimilateListOfVariant(anotherlist)` appends the elements of `anotherlist` into the current list.
