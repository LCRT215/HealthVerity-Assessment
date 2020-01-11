# HealthVerity-Assessment

Question 1

    You stumble across a random number generator on GitHub. The author believes that their
    generator will create an infinite sequence of integers that won't repeat. Their random number
    generator is seeded with a list of size N containing integers between 0 and N-1 (inclusive). It
    then returns "random" numbers by iterating through the list. The generator starts by returning
    the value at index 0. It then uses that value as the index for the next value to return, and
    so on. If the generator was seeded with the list [1, 2, 0], the first number it would return would
    be 1, then 2, then 0, and then it would repeat the sequence. Thus, the number of distinct
    values would be 3.

    <!-- Part a: -->
    Write a function that takes as input the seed list of the random number generator of up to 1
    million integers and returns the count of distinct integers the random number generator would
    return. Hint: len(set(input_list)) does not produce the right answer

    Sample input: Sample output:
    [1, 2, 0] 3
    [4, 1, 3, 4, 2] 3

    <!-- Part b: -->
    Can part a be done with O(1) auxiliary space (i.e. using only a constant amount of additional
    memory)? If so, write a function that does it. If not, why not?
