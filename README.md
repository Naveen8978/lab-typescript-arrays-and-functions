![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | Typescript Introduction - Strings and Numbers

## Learning Goals

After this lesson, you will be able to:

- Develop some basic TypeScript functions.
- Develop some basic arraysa and perform some array related operations.
- You will learn to work with mixed arrays.
- Create a TypeScript interface, and use it from a class.
- Implement two different interfaces and use them from classes.

## Requirements

- Fork this repo.
- Clone this repo.
- Install TypeScript on your computer

```$ npm install -g typescript```

## Submission
Upon completion, run the following commands:
```
$ git add .
$ git commit -m "done"
$ git push origin master
```
Navigate to your repo and create a pull request from your master branch to the original repository master branch.

In the pull request name, add your ProGrad Id and last names separated by a dash "-"

## How to run the project
- To compile the project
- Open the terminal inside Vscode editor and execute the following command.
    - ``` tsc main.ts ```
- Once you complie your typescript code, main.js file get generated automatically.
- Now run the main.js file to see the output. To run the file, use the command given below
    - ``` node main.js ```
- You can see the output in the terminal.
- Also open the index.html and see the output in browser console.

![Complile&Run](https://i1.faceprep.in/ProGrad/typescript-lab-image1.png)

## Introduction
When we are studying, it's very common to understand arrays cises and tasks. Some of them are more important than others, but we have to remember all of them.

We are going to help you with this. How? We are going to work with arrays in TypeScript. We are going to create different operations following different strategies with TypeScript. In the process, we will cover several important basic topics: variable types, arrays, functions, classes, and interfaces.

Project Structure
The project structure will be as follows:
```
starter-code/
├── progression-1
    ├── index.html
    ├── main.js
    └── main.ts

```
You are going to work over the *.ts files.

Note: Remember that the *.js files are generated every time we save the TypeScript files in our solution.

## Progression #1: 
- Go to main-service.ts.
- Create an Interface called StringManipulationService and don't forget to export it.
- Define the following methods inside the StringManipulationService,
    - print(word:string): void;
    - printWithSpace(sentence:string) : void;
    - findVowel(str: string) : void

## PROGRESSION #2: 
- Go to main.ts.
- Create a class called as StringManipulations which should implement the StringManipulationService.
- Your class should implement all the three methods.
- print(word:string): void method should take string as input and it should perform the following operations
    - Display the given string without any modifications(use console.log to print)
    - Display the given string in uppercase.
    - Display the given string in lowercase.
    - Display the character at a particular position in a given string.
    - Concat the given string with another string.
    - Slice the given string and display.
    - Find the length of the given string.
- printWithSpace(sentence:string) : void method should take string as input and display the given string by adding space between every character.
- findVowel(str: string) : void should take string as input and display the number of vowels in a given string.
    
## PROGRESSION #3: 
- Go to main-service.ts.
- Create an Interface called NumberManipulationService and don't forget to export it.
- Define the following methods inside the StringManipulationService,
    - findPrime(num: number) : void;
    - findMagic(num: number) : void;
    
## PROGRESSION #4:
- Go to main.ts.
- Create a class called as NumbersManipulations which should implement the NumberManipulationService.
- Your class should implement all the two methods.
- findPrime(num: number) : void method should check whether the given number is a prime number or not
- findMagic(num: number) : void method to check whether the given number is a magic number. A magic number is a number in which you need to repeatedly add the numbers until a single digit is reached. if the number is equivalent to 1, then the given number is a magic number, else display it is not a magic number.
for example, consider a number 199 -> 1 + 9 + 9 = 19 -> 1 + 9 = 10 -> 1 + 0 = 1. So 199 is a magic number.
    

Happy Coding ProGrad ❤️