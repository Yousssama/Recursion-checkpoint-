# Recursion-checkpoint-

The isPalindrome function takes a word as input.
We calculate the length of the word using the length function and store it in a variable called length.
If the length of the word is less than or equal to 1, then we return true since it's already a palindrome.
Otherwise, we compare the first and last characters of the word. If they are not equal, then the word is not a palindrome and we return false.
If the first and last characters are equal, we remove them from the word by calling the isPalindrome function recursively on the substring of the word that excludes the first and last characters.
We keep repeating this process until the length of the remaining substring is less than or equal to 1.
If we have compared all pairs of characters and they are equal, then the word is a palindrome and we return true.
