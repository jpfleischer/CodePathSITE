# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Jacques Fleischer

Time spent: **8** hours spent in total

Link to project: https://rich-maroon-colony.glitch.me

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn


## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/I8th2q8Y4j.gif)
![](http://g.recordit.co/MUPQj4LESV.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[Guide to hiding images](https://careerkarma.com/blog/css-hide-element/)

[Stackoverflow post about integrating images within photos](https://stackoverflow.com/questions/2444894/how-to-set-background-image-in-submit-button)

[Glitch support page on how to add assets to home directory in terminal](https://support.glitch.com/t/assets-folder-path/4638/6)

[HTML img tag](https://www.w3schools.com/tags/tag_img.asp)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

An issue that I experienced when creating this game website was trying to solve the button image problem. I had to solve the problem of getting an image to appear on the button when it was clicked; since the solution was not immediately apparent, I had to do some digging around on Google. Eventually, I found a stackoverflow post that showed how to include an image from a URL (online on the Internet and not locally saved) in CSS. While this was a good solution since I had URLs provided by Glitch, I was not satisfied. I preferred a local solution saved on the server.
So, I discovered a Glitch support thread started by a user who was seeking to save images locally (by locally, this means on the server that hosts the website). I had to use Linux commands to create a directory named “assets” in the home directory. Then, I changed the URL link in the CSS file to ../assets/blue.png (and this was altered for the other colors, as well). This reassured me as the previous URL was quite long and I was worried that it was not a permanent link. All in all, the predicament was not so hard to solve, and I had fun finding the solution.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

A question I have regarding web development is, what is a “frontend” and what is a “backend”? While I could find the answer on Google, I prefer to have a hands-on learning approach by designing my own— if it is necessary to use these within the program. Furthermore, I wish to learn more about the capabilities of JavaScript and how it can augment the user interface of an online browser program.
While I am primarily interested in JavaScript, I would like to learn more about different tags of HTML and CSS: perhaps how to create an audio player within a webpage from scratch instead of importing a pre-made one.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

To improve upon this project, I would build a dynamic background- perhaps a simple sky- that turns from night to day as the user progresses in the game. I would also create a function that gives the user three tries throughout the game, so that one wrong answer does not immediately disqualify the user from going any further. Furthermore, I would love to create a random number generator that outputs random numbers from 1 through 4 to create a unique pattern/list for the game; right now the game outputs the same pattern every time a user plays.
The game right now is simple but is able to be infinitely expanded with many features. My biggest idea is to create a multiplayer functionality, so that paired with another player, whoever gets the farthest (largest amount of correct guesses) wins.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/fvAjN2w9dm4)


## License

    Copyright Jacques Fleischer

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
