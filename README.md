# TDD React

This builds a simple Calculator app based on the original https://github.com/calebpollman/react-calculator. 
Results can be found here: https://egraumann.github.io/react-calculator/

## Changes to the original
- layout (colors, round corners, different division sign)
- works with float
- displays 0.5 instead of .5

## ToDo:
- when typing in number and adding operator, I would like to keep the number in the display instead of resetting it to 0
- adding more operators (-/+, root, etc)
- (optional) when dividing by zero, it does nothing. Maybe show "error" or something like this?

## Local Setup

```sh
$ git clone git@github.com:egraumann/react-calculator.git
```

```sh
$ cd react-calculator
```

```sh
$ npm install
```

## Run Locally

```sh
$ npm start
```

## Run Tests

```sh
$ npm test
```
## Deploy to Github page
```sh
$ npm run deploy
```
