Given a string and a pattern, find all anagrams of the pattern in the given string.

Every anagram is a permutation of a string. As we know, when we are not allowed to repeat characters while finding permutations of a string, we get N!N! permutations (or anagrams) of a string having NN characters. For example, here are the six anagrams of the string “abc”:

    abc
    acb
    bac
    bca
    cab
    cba

Write a function to return a list of starting indices of the anagrams of the pattern in the given string.