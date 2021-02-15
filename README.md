# HWS-Project8
Word building game. Building UI programattically 

## Part one
creating and styling the elements of the view then placing the elements using NSConstraint.activate

## Part two
Adding the logic to the game. First we added targets to the submit, clear and button array, then we put in blank placeholers to fill in later

next we wrote the _loadLevel_ method to load level data from the _Bundle.main.url_ file path. In thi method, we broke apart the strings into usable components and loaded that into the UI in the form of clues, answers and word-bits-buttons.

Finally we finished filling in the logic for the submit, clear and button array.

## Challenges
In addition to this I modified the code in the following ways:

1.  added a thin gray line around the buttons view

2. incorrect guesses produce alerts. this is implemented via the _submitTapped_

3. The game now deducts points for incorrect guesses
