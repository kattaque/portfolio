---
name: Drench
tools: [JavaScript, HTML, CSS]
image: 
description: This project has an individual showcase page, not just a direct link to the project site or repo. Now you have more space to describe your awesome project!
---

# drench

## BACKGROUND + ACCESS
An accessible version of the classic game "Flood", that can be found [HERE](https://www.chiark.greenend.org.uk/~sgtatham/puzzles/js/flood.html).

Website to the game can be found [HERE](https://kattaque.github.io/drench/). The purpose of this project is to create a better online experience for users with limited physical mobility. It is specifically targeted to be available and usable for the sighted, the visually impaired (color-blind), and those without fine motor skills. As a color-based grid game, it helps build visual-spatial skills and strategic thinking. 

The goal of the game is to fill the grid with the same color in as few moves as possible. The game will comprise of various levels, with varying levels of difficulty. The game board would start off small, but wil enlarge for the higher levels: easy (5x5), medium (7x7), hard (12x12), and very hard (20x20).

 As previously stated, the goal is to fill the entire grid with the same color, starting with the upper left and selecting neighboring colors until the whole board is covered with one paint color. The input will be using speech recognition API on GitHub that is adapted to  recognize voice commands as input. Players can choose the colors simply by saying the color name out loud. In addition to the game being motor-impaired-friendly, it so that some of those who are visually impaired could also play. Through research, it's been found that pastel color palettes are preferred by those who are colorblind. The board also fills the whole screen so that it’s easily viewable.
 
For maximum audience reachability, the game will only require a keyboard and/or a mouse. A touch screen is also usable.

## TECHNOLOGIES + FRAMEWORKS

This game was inspired by the usage of the game Flood, as mentioned above, but implemented with speech recognition API to make it more accessible. The speech recognition software used the speech-to-text function with code from [THIS](https://mdn.github.io/web-speech-api/speech-color-changer/) specific API to recognize the various colors the users were saying. The game itself was built using JavaScript. The website was built using HTML/CSS, and compiled with Pug. 

The technologies used were minimal; it only requires a laptop that contains microphone input, and is something that most computers are equipped with, no matter what operating system. 

## DIRECTIONS FOR USAGE
1. Choose the difficulty that you'd like from EASY (5 x 5) to VERY HARD (20 x 20).

2. Allow for microphone usage on the webpage.

3. Click anywhere to begin.

4. Starting from the top left corner, fill the board so that it's all one color by saying the colors of adjacent blocks aloud! 

## ISSUES

There were a few issues while building the game with speech recognition. One was that words other than the colors were being counted as points, even though the code only limited the counter to increase if one of the colors were said out loud. 

During the process of creating this website, there were a few issues, including: colors not being recognized properly, game not functioning properly (the wrong blocks would change color), etc, but those were resolved along the way. 

## FUTURE WORK
A fundemental goal for future work would be to provide additional forms of input for a broader audience of users. One such step in that direction would be to perfect implementing hand gestures as an additional form of input. This could be an integral addition, as it can be used as a form of rehabilitation therapy for motor skills. Also, those with limited speech woudld also have a difficult playing at the current version. Furthermore, other forms of input like a joy stick, or head/facial tracking could all be next steps to delve into that weren't able to be fleshed out during the duration of this course project.



<p class="text-center">
{% include elements/button.html link="https://github.com/kattaque/drench" text="Learn More" %}
</p>
