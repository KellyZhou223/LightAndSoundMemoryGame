# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Kelly Zhou**

Time spent: **~15** hours spent in total

Link to project: https://glitch.com/edit/#!/hail-assorted-lime?path=README.md%3A41%3A0

## Required Functionality

The following **required** functionality is complete:

* Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* "Start" button toggles between "Start" and "Stop" when clicked. 
* Game buttons each light up and play a sound when clicked. 
* Computer plays back sequence of clues including sound and visual cue for each button
* Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* User wins the game after guessing a complete pattern
* User loses the game after an incorrect guess

The following **optional** features are implemented:

* Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* Buttons use a pitch (frequency) other than the ones in the tutorial
* More than 4 functional game buttons
* Playback speeds up on each turn
* Computer picks a different pattern each time the game is played

## Video Walkthrough (GIF)

![LightAndSoundGame](https://user-images.githubusercontent.com/41167481/161350679-126278ea-3e85-47f0-ab16-b4495c403b5c.gif)
![LightAndSoundGame2](https://user-images.githubusercontent.com/41167481/161350704-51a147ee-8fc0-491b-814d-e8d95f47d632.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
Outside resources that I used to complete my submission are the W3Schools and Geeks For Geeks websites, which were helpful in explaining HTML, CSS, and JavaScript concepts, including how to use certain functions as well as how to structure the documents.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One challenge that I encountered in creating this submission was writing the guess() function for mimicking the pattern. Implementing this function was challenging at first because there were many different cases to consider. For example, there was a case for whether the user pressed the correct button according to the pattern. After considering this case, we also had to think about how far the user’s progress was to decide whether to play the next sequence. In the beginning, I was overwhelmed by all the different cases we had to implement. However, I overcame this challenge by taking a step back and imagining myself as the user playing the game. I went through all the different options by hand, pressing different buttons to repeat the pattern. For instance, in one case, I would follow the pattern correctly and keep track of my progress counter. If my progress reached the end of the pattern, then I would win the game. In another case, I would lose the game by purposefully pressing the wrong button. Throughout this process, it was very helpful to keep track of the different variables on a sheet of paper.  I would write down my guess counter, progress, and pattern index, and keep updating them as I progressed through the game. This helped me organize my thoughts and understand how to control the different cases. Then, I was able to translate my thought process into my actual implementation. Writing the function after going through the game was a lot simpler and comprehensible.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
One question that I have about web development after completing my submission is how to create more dynamic web pages or applications. After completing my submission, I got the opportunity to dive deeper into creating an interface for users, such as the users pressing buttons to guess, and this selection being recorded and processed. This makes me want to learn more about how users interact with the applications, and how I, as a web developer, can create websites that respond to a certain user’s preferences. This makes me very curious about dynamic web development, creating sites that display different types of content every time a user goes on the page. I am also very curious to learn more about a career in web development. After completing my submission, I became more intrigued about this field and aspire to improve my skills in web development. I would like to learn more about what web developers do on a daily basis, what kinds of projects they work on, etc. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would add additional features, such as a ticking timer, multiple strikes, or different game modes. Specifically, there could be different challenges associated with the Light and Sound Memory game. For example, one mode could be a timed game where the user tries to guess the pattern within a certain time limit. Another mode could be a game with an extensive pattern, which tests the user’s ability to memorize a very long pattern. Moreover, another mode could be the buttons switching places, so the user must memorize the exact colors and sounds, not just the location of the button. I would also try to implement an account and leaderboard system, where users can log in and try to beat each other’s scores in the different game modes. They can try to beat other players’ times in guessing the pattern or their scores in guessing the longest pattern. These are all features of the game that I would implement if given more time.



## Interview Recording URL Link

https://www.dropbox.com/s/c83umrqqqgergmk/video8828350040.mp4?dl=0


## License

    Copyright Kelly Zhou

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.




 
