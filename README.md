# Caesar-Cipher
The Caesar_Cipher function is a Python implementation of the Caesar cipher algorithm. The function first prompts the user to choose a language from a dictionary of languages or to add a new language. The user is then prompted to enter a sentence to be ciphered and a shift value to be used in the ciphering process. The function then applies the Caesar cipher algorithm to the sentence and returns the ciphered sentence.

The Caesar cipher is a type of substitution cipher that replaces each letter in the plaintext by a letter some fixed number of positions down the alphabet. For example, with a shift of 3, A would be replaced by D, B would become E, and so on.

The implementation of the Caesar_Cipher function makes use of a dictionary of languages, where each language is associated with a list of letters in that language. The function also includes a nested function called "get_choice", which prompts the user to choose a language and handles the input validation. If the user chooses a language that is already in the dictionary, the function uses the corresponding list of letters for the chosen language. If the user chooses to add a new language, they are prompted to enter a list of letters for that language.

The Caesar cipher algorithm is then applied to the sentence by shifting each letter in the sentence by the specified shift value. The function checks if the letter is in the list of letters for the chosen language, and if so, applies the shift. If the letter is not in the list of letters for the chosen language, it is not shifted and remains the same.

Once the ciphering process is complete, the function returns the ciphered sentence.

Note: This is an enhanced version of HackerRank challenge.

** you can see it through the following link:**

https://www.hackerrank.com/challenges/one-week-preparation-kit-caesar-cipher-1/problem?isFullScreen=true&h_l=interview&playlist_slugs%5B%5D=preparation-kits&playlist_slugs%5B%5D=one-week-preparation-kit&playlist_slugs%5B%5D=one-week-day-three

More about Caesar Cipher :https://en.wikipedia.org/wiki/Caesar_cipher 

***If you found any error in your language please leave me a comment***
