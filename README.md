# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **NAME**

Time spent: **#** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

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
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Modified the UI, giving a more attractive feeling!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![https://github.com/ProgramLikeABeast/SoundBox/blob/master/Recording%20%231.mp4](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used previously studied knowledge to finish and asked on Stack OverFlow for why ActionContext is not allowed on Chrome.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
On Chrome, I still cannot play the music because it has a policy to prevent any sound produced before a user gesture on the page. I really spent a lot of time and effort to try to solve but failed. So I gave up Chrome and make it run on other web browsers.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I want to know a design pattern that carries out the whole project smoothly. At least in this project, I can feel that all components are connected with each other: CSS beautifies HTML and JavaScript gives the page some logic. Any change to any element in any one of the file may result in necessary change in other files takes a lot of time. I want to know if there's an optimal design method even "algorithm" that minimize these steps thus maximizes our productivity? Is it an advanced concept that should learn in the coming years or I can slowly learn right now in project constructions?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I will spend time add some more features: 1. Change the square buttons to piano keyboard with chromatic scale 2. make it a pitch-practice tool: play a music without changing buttons' colors and then ask the user to click the button 3. add some more "patterns" that user can listen to some demo music pieces. 4. make the UI more smooth by utilizing a good format CSS file from the internet, and study from industrial-level web pages. 5. I will add a login and signup system and utilize cloud storage technologies like Parse(it supports JavaScript!) to store user information(progress, highest score, etc.)

## License

    Copyright [YANG XU]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
