README -  Search Word Puzzle

HOW TO RUN

In Visual Studio, open the project file from the project folder - PillarWordPuzzleKata\PillarWordPuzzleKata\PillarWordPuzzleKata.csproj.
Once the project is opened just click on "Run"
Press any key to terminate the program.

All files for this project are stored in the executable folder - PillarWordPuzzleKata\PillarWordPuzzleKata\bin\Debug

This program is meant to work for ANY puzzle size, given an input file in the appropriate format (and not just the one used for this kata)
The solution to the puzzle obtained from the website is given in the "...puzzle solution.txt" files for your reference. I challenge you to feed it a puzzle it cannot 
solve :)

I tried different puzzles of different sizes and words and sharing letters between  words as much as possible, etc and all work fine. There are currently 2 puzzle files. 
The program is currently set to run the "word puzzle 2.txt"
file which is the larger puzzle. To search a different puzzle, just change the name of the puzzle file in the puzzleFilePath variable in the source code.

The basic idea here is to search in each of the 8 directions for any given character in the grid, and each search looks up a word of a specified
length in the given direction. This is done for every distinct search word length. The process continues until all the words have been found or
the end of the grid has been reached.

ABOUT THE INPUT FILE - "word puzzle 2.txt"

This puzzle is a 40x40 grid with 22 search words

For the input data make sure that the first line contains the search words separated by spaces. I could've used commas but that's how I go it from the website...

Make sure the first line of input ends in a carriage return after the last word and NOT a space

All rows of letters in the grid should end with a space (ONE)

After the last space of  the last row, there should not be any more data in the file (you may manually delete all trailing blank spaces but this should not be necessary)

