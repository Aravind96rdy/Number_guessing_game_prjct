## Using python we generate a random number and ask the user to guess the number.
### Steps to implement to get desired output

1. Import random module to generate random numbers.
2. create a variable to store random number generated using function `randint`
3. we create try block to catch invalid input.
4. if input is not "int" a `ValueError` is raised and except block catches to print a message.
5. `If` and `elif` is used to know if the guess value is greater or lesser than the generated random value.
6. `else` is used if the guessed number is matched with random number.
7. If,elif statements are placed in a infinte `while` loop until it `break` if the number is matched.