# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Huan Li**

Time spent: **9** hours spent in total

Link to project: https://empty-glow-grade.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [Y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Y] Game buttons each light up and play a sound when clicked. 
* [Y] Computer plays back sequence of clues including sound and visual cue for each button
* [Y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Y] User wins the game after guessing a complete pattern
* [Y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Y] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [Y] Buttons use a pitch (frequency) other than the ones in the tutorial
* [Y] More than 4 functional game buttons
* [Y] Playback speeds up on each turn
* [Y] Computer picks a different pattern each time the game is played
* [Y] Player only loses after 3 mistakes (instead of on the first mistake)
* [N] Game button appearance change goes beyond color (e.g. add an image)
* [Y] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [Y] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/vzYIVOK.gif)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
StackOverflow: many-many searches for my errors and console problems. W3schools: tutorials on setInterval and setTimeout. 
MDN and Google as well.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The biggest challenge was setting up the timer. I was tring to make my timer visible to the user (show on the screen), it would stop the game if the time hits 0 and reset. Finall, I wanna make sure that users would have 10 seconds to enter their guesses. To make it visible was easy after searching on StackOverflow, then I read more questions on StackOverflow and W3chools to see examples of implementing setInterval(), setTimeout() and clearInterval(), I was able to solve the second problem by using the clearInterval() before the next round timer starts. I was told that I can set the first setTimeout() has a delay equal to the longest note, and recursively call a secondary setTimeout() that has a 1 second delay to stop my timer counting down without refresh.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I'm interested in learning how back-end would work on projects that require servers. I became more curious about how to combinefrontend with the backend that I'm interested in. I can see where JavaScript, CSS, and HTML all tie in together, it's really interesting and I’m also interested in a design principles such as how a website should flow in order to appease to other users. I would love to learn how to write tests for each function as well to ensure that they worked as expected.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
 If I had a couple more hours, I would put more time and effort into implementing the clock and having images show up as the background. It'd be cool to store the game records and stats for every user. I would use cookies or a database, but that would require backend.I also would like for my code to be a lot more readable to others, so I would write more comments about the code.



## Interview Recording URL Link

[My 5-minute Interview Recording].https://loom.com/share/f59a9f2c9b3647559721d68c4425ce1b


## License

    Copyright [Huan Li]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
