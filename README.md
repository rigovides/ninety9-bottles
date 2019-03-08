# 99 bottles of beer
## Instructions
Using the XCode project included in the repository, code a program that generates individual verses for the “99 bottles of beer” song given a verse number. A sample `song.txt` with the whole song is included for reference.

i.e.
`print(verse(99))`
Prints:
```
99 bottles of beer on the wall, 99 bottles of beer.
Take one down and pass it around, 98 bottles of beer on the wall.
```

The program also requires generating ordered verses given a continuous range of verse numbers.
 i.e.
`print(verses(75, 73))`
Prints:
```
75 bottles of beer on the wall, 75 bottles of beer.
Take one down and pass it around, 74 bottles of beer on the wall.

74 bottles of beer on the wall, 74 bottles of beer.
Take one down and pass it around, 73 bottles of beer on the wall.

73 bottles of beer on the wall, 73 bottles of beer.
Take one down and pass it around, 72 bottles of beer on the wall.
```
 
Mind the spaces between verses.

Finally, the program can generate the whole song
i.e.
`print(song())`

Inside the project, you will find a test target with a single test suite `BottlesTests`, with a minimum of required cases and a description of what needs to be tested in each one of them. Implement the proposed tests. 
	Feel free to add more cases if it adds robustness, adds edge cases, etc. to your code.

Optionally: Send a PR back to the repository with your solution

## What will be evaluated? (In order of importance)
* Code style, good practices, in both code and tests
* Approach & analysis of the problem
* Pass required tests 
* Solution completion with all scenarios

Recommendations:
* Start by making the `testFirstVerse` test under BottlesTests pass, then continue as pleased.
* git commit can help you make checkpoints and submit a stable solution
* You can look at documentation, stackoverflow, etc. (Strictly for sintax & debugging)





