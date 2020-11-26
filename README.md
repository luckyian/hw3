# Password Generator

In this Password Generator project I used the code in the index.html, style.css, and script.js to create a random password generator.  By editing and adding code to the script.js file and the generatePassword function I was able to make the generatePassword function prompt the user for how many characters the user wants the password to contain, and what characters(upper case letters, lower case letters, symbols, and/or numbers) make up the password.

Upon button click of "Generate Password" the code will start the prompts/confirms to get user data to create password.  Once the data is taken from the user, the function runs data through a series of if/if else statements to evaluate how to create password.  Once the correct data set is choosen based on character selection, the code randomly selects one of the character arrays picked by the user, and then randomly selects a character from that array and writes it to the array "finalPass."  The function continues to loop, picking a random character array choosen by the user, and then a random character from that array until the total number of characters that were input by the user at the intial prompt, "How many characters do you want in the password?  Must be between 8 and 128."

Once the total number characters is reached, the function writes the array "finalPass" that contains all the characters selected by the loop to the card in the index.html to display the password generated by the generatePassword function.

## Screen Examples

![First Page](.\Assets\Home.png)
![On Click](.\Assets\Initial-prompt.png)
![Lower Case Confirm](.\Assets\Lower-case-confirm.png)
![Upper Case Confirm](.\Assets\Upper-case-confirm.png)
![Symbols confirm](.\Assets\Symbols-confirm.png)
![Numbers confirm](.\Assets\Numbers-confirm.png)
![Selections Alert](.\Assets\Selections-Input-Alert.png)
![Final Result](.\Assets\Final-Result.png)


## Built with the following tech:

* HTML
* CSS
* Javascript


### Published link:
https://luckyian.github.io/Password_Generator/index.html

#### Contributer:

Ian Wren
