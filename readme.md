<!-- number of "#" can be represented as "h1/h2/h3..." -->
<!-- # Project 1 Documentation
## by Jameson Wang


## Introduction

Explain what is your project here, what does it do, etc.

## Technologies Used

- HTML
- CSS
- JS
- JQuery

## Challenges

#### I have trouble with

my code looked like this

```js
console.log("hello")
```

it was giving me a problem...when it was fixed it looked like this:

```js
console.log("goodbye")
```

### Example Table

| Column1 | Column2 |
|---------|---------|
| thing1  | thing2  |
| yadda1  |  yadda2 | -->

# Project 1 Documentation
## by Jameson Wang


# Introduction

Creating a trivia game where users have to select the correct answers to gain points to win.

## Technologies used

- HTML
- CSS
- JS
- JQUERY

## Challenges

### I have trouble with

finding the {content_type} in the URL

it was giving me an error but was able to fix it by capitalizing the content type with "triviaGame"

Had trouble logging "correct" answer in the dev tools.
- Gave me problems with having all answers being clicked on to have an outcome of "incorrect" but fixed it by going to Contentful.com and added a new section with the answer, thus registered on click to have a "correct" outcome in the dev tools.

Having trouble with creating an alert that states who is the winner when a player reaches 10 points. This was the few code blocks that I've tried:

``` 
const winner = () => {
    for (let i = 0; i <= 10; i++) {
        console.log(winner)
    }
    alert("Player 1 wins")
}
```
Also tried: 

``` 
const winningConditions = () => {
    if ($p1score === 10) {
        alert("Player 1 win!")
    }
}
```

## Tasks
- Linked the URL to the script tag in the HTML

- Created basic styling of on CSS to have the visuals of the trivia game

- Added app state and created an array of players, and adding current questions

- Creating an array of questions

- Made a main DOM element with JQuery to have variables of the questions, answers, and scores of player 1 and 2.

- Completed the basic foundation of the trivia game

- Created a mobile-first design

- Create an alert to announce who the winner is

- Changed li to button