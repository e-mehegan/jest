# Jest Introduction

## NOTE
- Making a practice Dice Rolling App and testing with Jest

<br>
<br>

## Notes on Unit Testing

- Unit testing is about the outcomes of the function in the code
- Should be able to chop your app into function and test the functions to make sure they are working as expected and producing the correct outputs
- Useful for validating code
- Narrowing down on problems
- Corner bugs

- Best way for unit tests is in TDD
	- write your tests before writing the actual code
	- helps define output
	- planning out function

- Jest is most popular
	- Good for unit testing

<br>
<br>


## What was covered

- Learning Jest (JS test framework) - https://jestjs.io/docs/getting-started 
	- basic Jest test suites
		- describe
		- test 
		- test.each
		- test.skip
		- beforeEach & afterEach
		- beforeAll & afterAll
    
	- varieties of matchers
		- https://jestjs.io/docs/using-matchers
		- https://jestjs.io/docs/expect
    
	- Jest code coverage
	- mocks functions 
		- https://jestjs.io/docs/mock-function-api 
		- https://medium.com/@rickhanlonii/understanding-jest-mocks-f0046c68e53c 

- Refresher on TDD concepts
	- apply user stories to Jest test suites
   
- Building a basic terminal app with TDD
	- environment variables!
		- https://www.npmjs.com/package/dotenv

# Dice rolling app 

## Users 

- Tabletop RPG gamers 
	- Roll a variety of dice and get results 
	- Roll a twenty-sided dice (D20) and see the result 
	- Roll a twenty-sided dice (D20) twice and seeing the worst result (roll with disadvantage) 
	- Roll a twenty-sided dice (D20) twice and seeing the best result (roll with advantage) 
- Casual tabletop gamers 
	- Roll a six-sided dice (D6) and see the result


