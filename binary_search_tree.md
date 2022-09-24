# Binary Search Tree Challenge

You are given a list of numbers stored in a list `A`. The challenge is to build a [Binary Search Tree](https://en.wikipedia.org/wiki/Binary_search_tree) to store these numbers. Complete the outlined steps:

1. Represent each node of the tree (including its data, left child and right child).
2. Print the tree out in an understandable form.
3. Make a function to insert a list of numbers (`A`) into the tree.

Then check if you can insert all the numbers in `A` into your tree and that it prints out as expected.

## Additional Tasks

4. Write a function to check if the Binary Search Tree that you've created is balanced.

> Hint: A tree is considered balanced when the difference between the `min depth` and `max depth` does not exceed 1, i.e. if the list had `n` elements in it the height of the tree would be `log(n)` (base 2).

5. Adapt your function to insert a list of `n` numbers so that it runs in `O(n log(n))` time. Bear in mind that this is just the average case for a random sequence of numbers. If the list `A` was sorted it would take `O(n^2)`.

6. Adapt your function to check if the tree is balanced so that it runs in `O(n)` time.