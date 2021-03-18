# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: David Zhu

Time spent: 2 hours spent in total

Link to project: https://glitch.com/edit/#!/probable-fluorescent-rattlesnake

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/4e2826a8-257e-49bc-a9d2-3ffa0c33b340%2Fezgif-7-f42bb1b550bc.gif?v=1616032253198)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

None

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The biggest challenge was learning the languages work. I have little experience with Javascript and almost none with Javascript and CSS.
However, I was able to use my knowledge of other programming languages and the examples given in order to deduce the correct syntax.
Javascript was the easier to learn as it was similar to Python and used common ideas like loops, variables, and functions to create the logic for winning and losing as well as keeping track of the status of the player in the game.
CSS is different, but I learned a lot about the different ways CSS can style the contents of the page like color, shape, and width. It is alot more diverse and accessible than what I had previously done with just HTML. I looked at the example code to extrapolate the information I needed to different classes such as the ones that changed the color of the squares.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

The main question I have about web development is on the the design, implementation, and testing. 
How much time is usually spent on each part and how much say does the engineer get in each part? 
How does testing the code work on a small indivudal feature level tests and a larger scale integration tests?
How often do front end engineers work new projects versus maintaining old ones?
What are the more unique challenges a front end engineer faces compared to a back end one and vice versa?
What technologies are essential to know for a new front end developer enterting the industry?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I would create a Simon says game that goes on infinitely as long as the player keeps getting the pattern right. The implementation would have to be different in that we can't store a predetermined pattern to follow.
A more fun solution is a pattern that is updates itself with a ranodm square as the player enters the next stage of guessing. This would also mean that there is no win condition. The player would play until they lose.
Other than that I would add more features. The most interesting ones for the pplayer would be to add options for a variable amount of squares and a time limit to increase the difficulty.



## License

    Copyright David Zhu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.