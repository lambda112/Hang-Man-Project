# Hang-Man-Project
Another simple project regarding the popular game hangman. The user enters an input which is then turned into list so i can access each indivudal letter in the word. Orgionally i tried using a dictionary and a dictionary comprehension to assign those values a key but they do not work well with duplicate values meaning words with duplicate letters such as "cheese" would only display the first e letter found and not all 3. Then i set the number of guesses the player has which is the same as the actual hangman game 7. A while loop was used to end the game if the player uses up all their guesses and if statements where used if they correctly guesed. For extra functionallity i added extra componenets such as a hint function where the player can ask for a hint if they are stuck using a simple if statement which checked the input. As well as outputting the result of the game into a file stored on the users D drive including the name of the person who chose the word, the actual word and the date/time
