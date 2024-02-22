# JavaScript 1

JavaScript can be a cliff.

We will start with a button with an event listener. All our code will go inside the code block of a single function block attached to the listener. We introduced it back in Bootstrap, and it looks like this:

    <!-- index.html  -->
    <button id="myButton1">Play!</button>

    // script.js
    myButton1.onclick = function() {
      alert("Hello World!");
    }

This snippet is small enough to memorize, but does the job. It has a lot of concepts that we can unpack over the coming weeks.

## Concepts map

* Re-Introduce bird's eye view of JavaScript
* Start again with the JavaScript guessing game.

## Day 1

Run JS from a button click. See demo.

This will introduce a lot of concepts, with very little to remember. It will provide a basis for intuition that will come later. e.g. What is a function? What is a code block? What is an event? What is a callback?

Students can copy/paste the guessing game into the callback function.

Students will try to modify the code to their liking.

Breakpoints and stepping through code.

* Set textContent to You Win!
* Set img src to Winner
* Set background color.

We could introduce an endless loop with a break if we want.
We could style with Bootstrap

## Day 2

Concept: conditional statements, lt and gt, functions and return values

Now that we have the idea of JS in context, we will being our deep dive on JS the language

We will extract the work from yesterday into the lesson for today and put it into a Replit (in a function) and return the value of the message/state of win or lose.

We will need to strip out the parts of the program that modify the DOM and focus on the logic. This will give us a chance to share with students the concept of the language vs. the context the language is in (the DOM).

We may have some other examples.

Start with this (after paring it down):

    function(){
      let guess = 8;
      let message;
      if(guess === 7){
        message = "correct";
      } else {
        message = "wrong";
      }
      console.log(message);
    }

Next discuss the inputs and outputs of the original guessing game and how they entered into the program. This will lead us to the function's inputs and outputs.

    let guessingGame = function(guessIn){
      let guess = guessIn;
      if(guess === 7){
        messageOutput = "correct";
      } else {
        messageOutput = "wrong";
      }
      return messageOutput;
    }

let message = guessingGame(7);
console.info(message);

Now, we can work on lt and gt logic.

Add a less than and greater than in the if statements.

Example 2:

Some examples:

Age check. (child, adult, senior)

Price range on Amazon/Walmart. (too expensive, too cheap)

speed limit (too fast, too slow)

calorie intake (too low, to high)

Start with a function without input or output.

    let ageCheck = function () {
      let age = 10;
      let ageClass;
      if(age > 65) {
        ageClass = "senior";
      }
      ...
      console.log(ageClass);
    }
    ageCheck();

Then, add input and output

Breakout room: Try one of these on your own in a breakout room.

## Day 3

Concept: variables and boolean algebra, not (!) operator

Now that we have a reason for boolean algebra (the if-statements and the check boxes), we can introduce it.

The ideas is that the variables will hold calculations that are not directly present in the data. The variables will introduce new concepts that are obvious given the variable names.

It will be a good idea to exhaust all possible logical combinations so students can feel like they are exploring each problem space completely.

Give at least two examples, then work out one together. Start with a brainstorming session of examples. Choose some logical conditions that are student chosen and let students work in a breakout room for a while.

Some thing like:

    let isRobotDog, isRobotHuman, isDog, isHuman;
  
    isRobotDog = robo.checked && dog.checked
    isRobotHuman = robo.checked && !dog.checked
    isDog = robo.checked && dog.checked
    isHuman = !robo.checked && !dog.checked

    if(isHuman) {
      alert("Welcome");
    } else if(isDog) {
      alert("woof!");
    } else if(isRobotHuman) {
      alert("wElCoME BEEp bEeP");
    } else if (isRobotDog) {
      alert("wOoF BEEp bEeP");
    }

Or Coffee with sugar, milk

  isSugarFreeBlack = !sugar && !milk;
  isSugarFreeWithMilk = !sugar && milk;
  isBlackWithSugar = sugar && !milk;
  isSugarFreeWithMilk = sugar && milk;

  // print costs:
  if(isSugarFreeBlack) {
    alert("That will be $2.45")
  } else if(isSugarFreeWithMilk) {
    alert("That will be $2.95")
  }
  ...

Again, step through the code in Dev Tools.

## Day 4

concept: more variables and types -- strings, numbers and conversions

    <input type="text" id="numberOfPeopleInput">

    let numberOfPeople = parseInt(numberOfPeopleInput.value);
    alert("The number of people is: " + numberOfPeople); 

    if(numberOfPeople>9) {
      alert("This elevator has a max load of 9 people");
    } else {
      alert("Up or down?");
    }
    // or even
    isOverloaded = numberOfPeople > 9;
    if(isOverLoaded) {
      alert("This elevator has a max load of 9 people");
    } else {
      alert("Up or down?");
    }

Focus on the importance of variable names.

## Day 5

Bring it together.

Think of an application for each of these situations

Page 1: Two checkboxes

Page 2: One input

Page 3: One checkbox and one input

Style the page with Bootstrap.

**Bonus** perform validation on a on an input.

## Day 6

Now we introduce many checkboxes

An "Are you ...?" survey.

Ex: Are you a Bull's fan?

-[ ] Are you from Illinois?
-[ ] Have you ever owned Air Jordan's?
-[ ] Are you over 40?
-[ ] Have you been ignoring the NBA for the last 15 years?

Count the number of checks. If greater than X, output the answer.

You will need an Accumulator that contains the count. Use n++

DOM manipulation:

* set the bulls fan check mark.
* add textContent: "You are a bulls fan!"
* add img of bulls icon.

## Day 7

loops and arrays

Continue from the previous day's work. Put the checkbox values into an array. Loop

first past the post while loop.

    fanSide = 0;
    notFanSide = 0;

    while(!isDecided) {

    }


