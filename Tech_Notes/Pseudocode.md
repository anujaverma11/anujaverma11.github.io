# Pseudocode
## - Breaking down large problem into small pieces.
## - Avoid language specific words
## - Identify an Input and Output first.
## - Keep your pseudocode language agnostic (no Ruby method names). It should read somewhat like english
## - Capitalize keywords like IF, ELSE, UNTIL, WHILE, CASE, etc.
## - Indent sections that are dependent on lines above it.

- For Example
- Input: a word (a string)
- Output: true/false (a boolean)
- I know that a word is a palindrome if the word is same as the reverse.
- I am assuming all words are all lowercase when they are passed in.

Create a counter and set it to zero.
Create an empty container object.

WHILE the counter is samaller than the length of the word minus 1
  Push the letter at the counter index to the container
  Add one to the counter.
End WHILE

Create a new empty container object
Create a new counter and set it to negative one.

Until there is no value (nil)of the letter at the counter index.
Push the letter at the counter index to the container
  subtract one from the counter.
End UNTIL

IF the first container is same as the second container. Its a Palindrome(true)
ELSE it is not a palindrome (false)
END IF

http://users.csc.calpoly.edu/~jdalbey/SWE/pdl_std.html