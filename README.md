# Persian Plate Recognition
This project combines classification and opencv library to seperate the letters in persian plates and recognize them.

Input: Letters 1 - 9 in persian and persian alphabet letters used in plates

Model: KNeighborsClassifier

Output: The plate's predicted letter and numbers

How it works:
1. Upload the files containing different types of persian letters and numbers, resize them and turn them into black and white images using a for loop
2. Split the data into training and testing sets
3. Train a classification model (KNN)
4. Evaluate the model's accuracy
5. Upload a plate for testing the code
6. Detect where the blank spaces between numbers are in order to seperate them
7. Predict each number

Results:
The model achieved a 75% accuracy and nearly guessed all the numbers in the plate correctly

What I learned:
1. How to use a for loop to read multiple files and make changes in them
2. How to use opencv library to resize an image or change its coloring
3. How to seperate the itmes of an image based on empty spaces between them

Future developements:
Alter the program to detect english plates
increase model accuracy by using larger datasets
