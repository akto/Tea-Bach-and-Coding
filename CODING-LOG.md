# CODING LOG
## LOGGED AT
### [Go to 2024 Logs](#2024)
### [Go to 2020 Logs](#2020)
### [Go to 2019 Logs](#2019)
### [Go to 2018 Logs](#2018)
### [Go to 2017 Logs](#2017)


## 2024
 - ### 24-12-1
   - **An Issue for urlOpener:** I noticed that urlOper for selected engines is not working as I wanted it to I thought there was a bug, but it is related to pop-up blocking. It would be best if you permitted pop-ups to open. So, there is no problem with urlOpener. Just a reminder while using it.
 - ### 24-11-30
   - I’ve created a code [`urlOpener.js`](https://github.com/akto/library/blob/master/js/urlOpener) to open URLs of search engines, dictionaries, video search engines, etc. with a search query. I also created a mess opener for selected engines.
   - Added a snippet for css animations using webframes to [`snippets.css`](https://github.com/akto/library/blob/master/css/snippets.css).
 - ### 24-11-29
   - I've code a simple Array prototype in [`Array.prototype.count.js`](https://github.com/akto/library/blob/master/js/Array.prototype.count.js). It counts the given value in an array and return a number of matched items. If there is no match then it returns 0.
     
 - ### 24-11-28
   - I've made some changes in my old [`pomodoro.js`](https://github.com/akto/library/blob/master/js/pomodoro.js) file. I've changed changeState to toggleStatus method. I create a new resume method because changing on-off with a pause method is non-sense. I bind `this` keyword to make it run inside setInterval function.
   - fix a bug, this bug makes the start function only loop through the existing status after you run `stop` function. But I would like to start over to the time loop with the settings we have. 
     
 - ### 24-11-27
   - I understand that I can't implement a separate timer on my pomodoro application because I need to manipulate the countdown value and it can be done only inside the setInterval (or setTimeout). I have maden a little changes in my [`newPomodoro.js`](https://github.com/akto/library/blob/master/js/newPomodoro.js) file. But I can get rid of it completely later. My old code seems more relevant now.
   - Tomorrow I need to check both pomodoro code and keep only one for the sake of efficiency. I need to modify some codes in my old code. Maybe add a better alarm notification method and change toggling status method.
   
 - ### 24-11-26
   - **New beginnings**. After a long time I can't ignore the urge to be in developer world again. I'm starting over in little pieces.
   - If you want to create a single object without inheritance, like configuration, use object literals in js. You don't need multiple instances of same object. So, it is the reason for object literal is here.
   - [`Instagram Post for a Simple Bug`](https://www.instagram.com/p/DC0raO0tIiO/?utm_source=ig_web_copy_link&igsh=MzRlODBiNWFlZA==) This bug make me wonder around for couple of minutes. But, If you put parentheses after you call a callback in setInterval, it runs immediately once and it doesn't run with every repetative call by declared time interval.
   - I had an ugly solution for toggling 2 options. It's a brute force if and else statement just I used shorter if statement. Then I thought to change it for better solution. I had something in my mind but I asked chatGPT to generate me a code for toggling 2 options. I wanted it versatile and one line solution. So the solution that it gave me is the solution I have thought but I need to give credit to AI on this. I have created a [`toggleState.js`](https://github.com/akto/library/blob/master/js/toggleState.js) file. I will use it later on my pomodoro app.
   - Created and wrote a new [`newPomodoro.js`](https://github.com/akto/library/blob/master/js/newPomodoro.js) file. It's not complete.
     
## 2020

- ### 19.10.2020
  - Again It's been long time. Now I am working in an European Union Railway Construction Project and It tooks a lot of time of me. It's even hard to find time for yourself. So till now I've been lost my way. But I am always looking for returning to my love -programming-.

## 2019

- ### 24.10.2019
  - It's been long time not to write here. We had been in an intense period of construction works. But from now on, I will try to add some bits to my coding skills. Let's see.

## 2018

- ### 22.03.2018
  - I finished [`exact-cahnge.js`](https://github.com/akto/algorithms-problem-solving/blob/master/exact-change.js) and [`inventory-update.js`](https://github.com/akto/algorithms-problem-solving/blob/master/inventory-update.js).
  - I created [`no-repeats-please.js`](https://github.com/akto/algorithms-problem-solving/blob/master/no-repeats-please.js).
  - I finally created a test-suite. [`test-suite.js`](https://github.com/akto/algorithms-problem-solving/blob/master/test-suite.js)

- ### 21.02.2018
  #### Pins of the day
  - When I searched for mobile design principles, I found this [Principles of Mobile App Design: Introduction](https://www.thinkwithgoogle.com/marketing-resources/experience-design/principles-of-mobile-app-design-introduction/) Google tutorial series. It should be considered as a fundamental course for mobile design. [`mobile`]

- ### 07.02.2018
  - I create [`exact-change.js`](https://github.com/akto/algorithms-problem-solving/blob/master/exact-change.js). Today has been busy.

- ### 06.02.2018
  - I finished [`symmetric-difference.js`](https://github.com/akto/algorithms-problem-solving/blob/master/symmetric-difference.js). I used some codes from my [`unite-unique.js`].
  - I started a new plan. It's relative and strict. ( 10 mins work and 5 mins break, I do this loop for 3 times. Then I give a long break such as 10-15 mins. Then do this loop 3 times again. And it's strict. If working or break session paused for an important reason - like tasks of daily job- It must begin from the same place that it paused. Thus It is a program with importance and priority. I must do the most important task in the begining.)
  - New program has 10 or 15 mins work sessions because I can't focus more than 15 mins to anything. I know myself and I should create a routine that reflect my personal features.
  - Tonight I've remembered the [Project Euler](https://projecteuler.net). And give it a look. I've seen that I missed a problem in between first 10 problem and decided to solve it. It was an easy palindrome problem. I had a script to check if a value is palindrome. I used it and create [`projecteuler-largest-palindrome.js`](https://github.com/akto/algorithms-problem-solving/blob/master/projecteuler-largest-palindrome.js).
  #### Pins of the day
  - I used [`Array.prototype.splice`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice), [`Array.prototype.map`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map) and [`Array.prototype.reduce`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce) in my [`symmetric-difference.js`](https://github.com/akto/algorithms-problem-solving/blob/master/symmetric-difference.js).

- ### 05.02.2018
  - I messing out on [`symmetric-difference.js`](https://github.com/akto/algorithms-problem-solving/blob/master/symmetric-difference.js).

- ### 04.02.108
  - I couldn't work today. It was a day which passed in hospital.

- ### 03.02.2018
  - I created [`symmetric-difference.js`](https://github.com/akto/algorithms-problem-solving/blob/master/symmetric-difference.js).

- ### 02.02.2018
  - I finished the [`record-collection.js`](https://github.com/akto/algorithms-problem-solving/blob/master/record-collection.js). It's quite easy.

- ### 01.02.2018
  - I created [`record-collection.js`](https://github.com/akto/algorithms-problem-solving/blob/master/record-collection.js). Not finished only created the file.

- ### 31.01.2018
  - I finished the [`validate-us-phone-numbers.js`](https://github.com/akto/algorithms-problem-solving/blob/master/validate-us-phone-numbers.js) finally. Actually I don't like my solution. I need to use 3 regExp pattern to solve it. I need to learn more about Regular Expressions.
  - Today is busy in my daily job. Tomorrow I will be in the field again.

- ### 30.01.2018
  - I was at the field. So I don't have any time to code or do anything else.

- ### 29.01.2018
  - Still playing with regular expressions.
  - I don't have time to code nowadays. I've been very busy in my daily job.

- ### 27.01.2018
  - I Kept playing with regex patterns.

- ### 26.01.2018
  - I only try a few regex patterns for [`validate-us-phone-numbers.js`](https://github.com/akto/algorithms-problem-solving/blob/master/validate-us-phone-numbers.js). Regular Expressions are very tricky subject and finding the right pattern for your search is not easy. I need to focus more on this subject.
  - Today I did a lot of things at work and didn't have time to code. I try a few reg ex in the night.

- ### 25.01.2018
  - I've kept writing some code for [`validate-us-phone-numbers.js`](https://github.com/akto/algorithms-problem-solving/blob/master/validate-us-phone-numbers.js). I try to write code at least one min in a day.

- ### 24.01.2108
  - I created [`validate-us-phone-numbers.js`](https://github.com/akto/algorithms-problem-solving/blob/master/validate-us-phone-numbers.js).

- ### 22.01.2018
  - I've created [`arguments-optional.js`](https://github.com/akto/algorithms-problem-solving/blob/master/arguments-optional.js) recently at 19:43.
  - I've finished it at 23:43. This one take a little bit time because I couldn't focus for sometime.
  #### Pins of the day
  - I need to learn more about closures [`Javascript Closures`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)

- ### 21.01.2018
  - I created [`binary-agents.js`](https://github.com/akto/algorithms-problem-solving/blob/master/binary-agents.js). I recently start this algorithm today.
  - I finished [`binary-agents.js`](https://github.com/akto/algorithms-problem-solving/blob/master/binary-agents.js). It's not hard to solve. Actually I looked for how I can translate binary to characters and find a solution after that.
  - I created [`everything-be-true.js`](https://github.com/akto/algorithms-problem-solving/blob/master/everything-be-true.js). I am recently working on that. And I finished it. ( at 22:55 ). It was an easy one too. And today at least I could focus for some time.
  #### Pins of the day
  - I used [`String.fromCharCode`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/fromCharCode).

- ### 20.01.2018
  - I created [`steamroller.js`](https://github.com/akto/algorithms-problem-solving/blob/master/steamroller.js). JS code to flatten arrays. I started to work on it yesterday but finished tonight. Sometimes I have some difficulties about focusing to the subject that I worked.

  #### Not to self:
  - You need to make focusing exercises.

- ### 17.01.2018
  - I created [`finders-keepers.js`](https://github.com/akto/algorithms-problem-solving/blob/master/finders-keepers.js). JS code to looks through an array (first argument) and returns the first element in the array that passes a truth test (second argument)
  - I created [`drop-it.js`](https://github.com/akto/algorithms-problem-solving/blob/master/drop-it.js). JS code to drop the elements of an array (first argument), starting from the front, until the predicate (second argument) returns `true`.
  - I solved first one yesterday and `drop-it.js` today. They are easy problems.
  #### Pins of the day
  - A pin from yesterday about smallest common multiple solution [`Question about least common multiple problem`](https://stackoverflow.com/questions/31302054/how-to-find-the-least-common-multiple-of-a-range-of-numbers)

- ### 16.01.2018
  - I have been working on [`smallest-common-multiple.js`]() recently. Instead of using my own solution to this problem, I found a nice solution on [stackoverflow.com](https://stackoverflow.com/a/31302607/2839009). I had used an object to count all repeatable primes. But still can't figure out how I can repeat the divisions. I will keep try to figure it out later.

- ### 15.01.2018
  - I created [`spinal-tap-case.js`](https://github.com/akto/algorithms-problem-solving/blob/master/spinal-tap-case.js). JS code to convert a string to spinal case. Spinal case is all-lowercase-words-joined-by-dashes.
  - Add some functionality to [Pomodoro Clock App](https://codepen.io/egemen/pen/zPzJQp). I tried to make the clock start again after an increase in the session or break amounts. I managed to do it but this time break and session amounts intermixed. So I decided to add an eclectic resetting properity to the application. Now It can be resetted. But clicking creates a new problem. I will look at it later.
  - When I find time, I have been working on the [`smallest-common-multiple.js`](https://github.com/akto/algorithms-problem-solving/blob/master/smallest-common-multiple.js). Decided to create files before I have finished them. Thus I can keep track the changes that I have done and check the thinking process of mine later when I need.

- ### 12.01.2018
  - First 12 days of 2018 had a lot of distractions for me. I couldn't code. I need to create a mobile coding environment to use everywhere. Also I need to be ready to these kind of distractions mentally.
  - I am starting to work on a problem which is about [smallest common multiple](https://www.freecodecamp.org/challenges/smallest-common-multiple).

- ### 03.01.2018
  - It's been a week with a lot of distractions. I can't code.
  - I created [`boo-who.js`](https://github.com/akto/algorithms-problem-solving/blob/master/boo-who.js).
  - I guess i will start to code again next week. I am in a vacation that I can't reach the comp easily.

## 2017

- ### 26.12.2017
  - Today I was in the field trip too. I couldn't have time to code when I am in the field.
  - And tomorrow I'll be in the field till the noon or maybe more.
  - Yesterday I was in the field and didn't have access to any computer.
  - I created [`missing-letters.js`](https://github.com/akto/algorithms-problem-solving/blob/master/missing-letters.js). It's a code to find missing letters in a letter sequence in alphabetical order.

- ### 24.12.2017
  - I created [`dna-pairing.js`](https://github.com/akto/algorithms-problem-solving/blob/master/dna-pairing.js). It's code for matching the DNA codes.
  - I watched one video about computer basics.
  - I probably can't make practices for two days. I will be at field trip.
  #### Pins of the day
  - Codrops collective [#376](https://tympanus.net/codrops/collective/collective-376/).
  - Inspirational designs at [uijar.com](https://uijar.com/).

- ### 23.12.2017
  - I created [`pig-latin.js`](https://github.com/akto/algorithms-problem-solving/blob/master/pig-latin.js).
  - I watched one video about computer basics and do one piece of jquery lessons on freecodecamp.
  #### Pins of the day
  - I find a new site about [design princibles](https://principles.design) of various web sites, apps etc...

- ### 22.12.2017
  - I finished 1 video on @freeCodeCamp.
  - I created [`search-and-replace.js`](https://github.com/akto/algorithms-problem-solving/blob/master/search-and-replace.js). JS code to replace provided values with arguments in the sentences. It's a @freeodecamp algorithm challange.
  - I solved an adventofcode challange and create [`advent-sum-of-diff-in-rows.js`](https://github.com/akto/algorithms-problem-solving/blob/master/advent-sum-of-diff-in-rows.js). This script can be used to find accumulation of the sum of differences of max and min values in rows.
  - I'll use `advent-` prefix to indicate the scripts of solutions to [adventofcode.com](http://adventofcode.com) challanges. It's too late for @freeCodeCamp codes.
  - In js to find the max value of an array. Array.reduce() can be used. When you return a or b in the reduce method it checks every value in the array with elaminate the min one of the two value. Such as -> ( [1,2,3,7,4,5,6] --> (1,2),(2) -> (2,3),(3) -> (3,7),(7) -> (7,4),(7) -> (7,5)(7) ....
   #### Pins of the day
  - Methods that I used today: [`Math.max()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/max) - [`Math.min()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/min)

- ### 21.12.2017
  - I created [`where-art-thou.js`](https://github.com/akto/algorithms-problem-solving/blob/master/wherefore-art-thou.js).
    It's a js code to looks through an array of objects (first argument) and returns an array of all objects that have matching property and value pairs
  - I finished 2 videos on @freeCodeCamp.
  - I solved an algorithm [Sum of the all prime numbers till given value `sum-of-all.js`](https://github.com/akto/algorithms-problem-solving/blob/master/sum-all-primes.js)
  - I finished the [Pomodoro Clock Apps](https://codepen.io/egemen/pen/zPzJQp). It has been challenging for me. Because I had tasks to do in my daily job and gone to the field trips about it. It's very hard to develop something while you are working in a job like that.
  - Maybe I'll seperate background colors of session and break times in the [Pomodoro Clock Apps](https://codepen.io/egemen/pen/zPzJQp) later.
  - Today I can say that I am productive. I solved one algorithm, watched 2 vids, finished the pomodoro clock.
  #### Pins of the day
  - I finished video 6-7-8 at [Computer Basics playlist](https://www.youtube.com/playlist?list=PLWKjhJtqVAbmfoj2Th9fvxhHIeqFO7wOy)
  - Check out [Dev Tips Video Channel](https://www.youtube.com/channel/UCyIe-61Y8C4_o-zZCtO4ETQ)
  - Check out to [contribute to the open source projects](https://github.com/freeCodeCamp/how-to-contribute-to-open-source)
  - Check out - [The startups of Türkiye and which technology they use](https://github.com/frontendistanbul/technologies)

- ### 20.12.2017
  - Today I applied to renew my passport and identity card. It was a busy morning. After that I need to deal with some task in the job.
  - My daily job takes a lot of time of me.
  - So I couldn't code much. But;
  - I solve an algorithm problem from @freeCodeCamp [Sum of all the odd numbers in a fibonacci sequence to given value](https://github.com/akto/algorithms-problem-solving/blob/master/sum-of-all-odd-fibonacci-sequence-to-given-value.js)
  - Create 1 new js file which is a solution to a @freeCodeCamp algorithm and update and edit README.md
  - I almost finished the [pomodoro clock](https://codepen.io/egemen/pen/zPzJQp) but I decided to do it very simple firstly.
    because I need to learn and read more about js objects.
  - After first version I will improve the [pomodoro clock](https://codepen.io/egemen/pen/zPzJQp) eventually.
  #### Pins of the day
  - I like codrops collective. But I first to mention about [30 Seconds of Code](https://github.com/Chalarangelo/30-seconds-of-code). It has very nice code snippets.
  - Today I look up to [Array.reduce() method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce) in MDN Web Docs. I used it to sum the only odd values in a fibonacci sequence.
  - Also I use [Array.pop() method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop). I just look up to it because of don't make a syntax mistake and be sure about it remove only the last element of the array.
  - Codrops Collective [#374](https://tympanus.net/codrops/collective/collective-374/)

- ### 19.12.2017
  - I need to deal with my daily job tasks most of the day again.
  - There is a meeting in the deparment about surveying. But at least I've created this log.
  - I create [`sum-all-numbers-in-a-range.js`](https://github.com/akto/algorithms-problem-solving/blob/master/sum-all-numbers-in-a-range.js)
  - and I update the links in the README.md of Algorithms-problem-solving repository.

- ### 18.12.2017
  - I couldn't code today. Because of my daily job tasks.
