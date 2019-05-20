# minimum-Swaps
Find the minimum number of swap operations Mary must perform to order all n items by decreasing popularity rating

Task

John is a famous shopkeeper who sells n items in her shop. She assigns each item a unique popularity rating in the inclusive range from 1 to n.

The shop only has one shelf, so the items are displayed array-style in a single row spanning from left to right in a random order. He wants to rearrange the items on the shelf by decreasing popularity rating such that the rating for the i item is always greater than the popularity rating of the (i + 1) item. Mary can swap any two items, i and j, in a single operation.

Specification
minimumSwaps(ratings)

Parameters

ratings: Array<Number> - an array of numbers indicating the popularity rating of each item on the shelf.

Return Value

Number - denotes the minimum number of swap operations Mary must perform to order all n items by decreasing popularity rating.

Constraints

n = number of items in ratings array

each rating value ( arri ) will be unique

1 ≤ n ≤ 2 × 105

1 ≤ arri ≤ n
