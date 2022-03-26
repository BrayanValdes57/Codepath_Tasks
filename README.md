# Pre-work - *Memory Game*

**"Simon says" Interactive Game!** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Brayan Valdes**

Time spent: **4** hours spent in total

Link to project: Glitch - https://glitch.com/edit/#!/saber-living-feather?path=index.html%3A27%3A14
## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

 Lossing demonstration
 ![loss](https://user-images.githubusercontent.com/102376236/160202767-aca3dec4-a3f2-4159-9f39-81c964e6d9c0.gif)

 inning demonstration
 ![Winning](https://user-images.githubusercontent.com/102376236/160202768-4d2800a3-5d5f-43ff-ba90-d50c760d361f.gif)

 Controls and mechanics demonstration
 ![Showcase](https://user-images.githubusercontent.com/102376236/160202769-b7bb5213-cca6-4734-bae6-37361aa27cb5.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
   https://www.w3schools.com/cssref/css_colors.asp (Used only for color codes)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

     The biggest challenge I encountered when creating this submission for the memory game was translating my knowledge of coding in C++ to foreign JavaScript, CSS, and HTML. 
     One example of this struggle was when I was figuring out the optional task of speeding up the clueHoldTime variable each time the user guessed the color correctly. 
     In C++ I could have done this easily but the format of editing variables in this language proved to be frustrating at first. 
     I kept running into the issue that after I clicked the stop button, the timer didn’t reset to 1000. So, it started up fast instead of resetting to the initial value, but I persevered and found my solution to this issue. 
     It was a very rewarding feeling of accomplishment. What I figured out was that, by adding “(clueHoldTime = 1000)” in the stopGame() function and the if else loseGame part of the guess function, I could reset the speed to 1 second when the player either lost the game or clicked on the stop button. 
     This is not a complex task but I kept formatting (clueHoldtime=1000); as var clueHoldtime =100 and it wasn’t working. I did it like this because in C++ we change a global variable by just stating int clueHoldTime = 1000; but still, it was a fun challenge.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

     The most important question I have after completing my submission is: How do all the different programming languages correlate with each other? 
	 Since before completing this submission, I only had experience in C++, I had no idea why all these other languages were needed when using only one would be easier. 
	 Later, after having completed this project, I see now that all the languages in programming are sort of specialized in some specific tasks. 
	 For example, HTML is specialized in creating website text while JavaScript is used to add functionality and interaction to that website like buttons. 
	 So, after seeing how these two languages tie into each other, I would like to know and understand all the specialized tasks each language is built for and how to effectively use them with each other to build better apps and projects in the future.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
     
	 If I had a few more hours, I would like to add something I saw an issue on as I was working on the project.  
	 This issue being that while the program was showing the pattern that the user had to memorize and then later on repeat, the user could still click on the colored squares. 
	 I would have liked to add the functionality of not being able to press the buttons until the pattern was completed by the computer, or maybe even penalizing the user for doing so. 
	 An idea would be to instead of not letting the user click the squares while the sequence was being shown, to penalize them and make them loose the game if they pressed the squares while the sequence was being played. 
	 These ideas would have been great additions but aside from not having the time to do so as I am applying a bit late. Also I don’t have the expertise to do so, but I would love being taught to be able to accomplish this!



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Brayan A Valdes

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
