# Persian Plate Recognition
This project combines classification and opencv library to seperate the letters in persian plates and recognize them. Persian plates pose a unique challenge, as they're longer than most other plates, and some letters can be quit similar in appearance, making them hard to detect for models, especially for those like KNN that rely on simple distance metrics.

Dataset: Due to size, the full dataset is provided as a zip file. Download and extract the folder before running the code.

Input: Letters 1 - 9 in persian and persian alphabet letters used in plates , a full persian plate to test the code

Model: KNeighborsClassifier

Output: The test plate's predicted letter and numbers

How it works:
1. Upload the files containing different types of persian letters and numbers, resize them and turn them into black and white images using a for loop
2. Split the data into training and testing sets
3. Train a classification model (KNN)
4. Evaluate the model's accuracy
5. Upload a plate for testing the code
6. Detect where the blank spaces between numbers are in order to seperate them
7. Predict each number

Results:
The model achieved a 75% accuracy and guessed nearly all the numbers in the test plate correctly

What I learned:
1. How to use a for loop to read multiple files and make changes in them
2. How to use opencv library to resize an image or change its coloring
3. How to seperate the itmes of an image based on empty spaces between them

Future developements:
Replace KNN with a Convolutional Neural Network (CNN)
Alter the program to detect english plates.
