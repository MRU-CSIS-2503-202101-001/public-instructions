# Drill - Initialization Speedrun

_(aka Let There Be...Stuff )_

**Accept this project by going here: https://classroom.github.com/a/rD8suKoi**

## Preamble

A speedrun is meant to practice running through some basic skills as quickly as possible. Unlike non-speedrun drills, where you're typically asked to build a custom class and then "drive" it a bit, a speedrun drill is meant to be done solely in your `public static void main`.

## Time Required

JP's times:

1. importing accepted GitHub repo into Eclipse: **00:38**
2. coding passing solution: **05:53**
3. punting solution back to GitHub repo: **00:37**
4. submitting and verifying result: **01:13**

Your target time for step 2: **24 minutes**

## Skills Covered

Show you can...

- [ ] initialize an array with shorthand/shortcut syntax?
- [ ] use `List.of` to easily pass a Collection to the `ArrayList` constructor that takes a Collection.

## Instructions

1. Complete the  **//TODO** entries in the `main` method in the `Main` class provided, using the documentation to guide you.
   1. If you have completed the task properly, you will pass all the tests in `MainTests`.
   2. You might find it useful to run your main if your tests aren't passing. Here is what you should see in the console for a correctly working main:

---
---

Here are the 3 ints: [1, 2, 3]  
Here are the 3 doubles: [3.14, -0.22, 1.7976931348623157E308]  
Here are the 3 strings: [Wait...what?, Push the button, Frank., Game over, man - game over!]  
Here are the 5 foods: [Okonomiyaki, null, null, Surstromming, Green Eggs and Ham]  
Here are the 2 games: [Ticket to Ride (8), The Awful Green Things from Outer Space (7)]  

---
---

> **Crud you gotta deal with**
> - getting the number of things in an array is different than getting the number of things in an ArrayList
> - if you want to get a nice toString for an array, you need to use Arrays.toString


## Tests

> *Since this is the first week of drills, I'll explain in detail what's going on with testing. After the first week, I'll assume you're cool with it.*

Your code is being tested through `MainTests.java`. Although it looks kinda scary, all that's going on is this:


1. The test is told what things to "type" when prompted by your `main` code. For this drill, there is no input, but for all future ones, there will be.
2. The test then runs the main, "typing" its input and observing what comes out in the console. That output is checked line-by-line with the Strings you see in the `List.of` part of the test. Your output has to match these Strings **exactly** - the order, spelling, and even capitalization all have to match for the test to pass. Using the `Compare Actual With Expected Test Result` mini-button is a **lifesaver** here!



