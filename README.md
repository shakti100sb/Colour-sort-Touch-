Color Sort – Touch-Based Game
=============================

Overview
--------
Color Sort is a fun and interactive 2D touch-based game where players match a central colored block with one of the four corner blocks. The game tests your reflexes, color recognition, and quick decision-making skills.  

The game includes scoring, a timer, high score tracking, and interactive touch controls for an engaging experience.

How to Play
-----------
1. Start the Game
   - When the page loads, you’ll be prompted to enter your name.
   
2. Objective
   - Match the color of the central block with the correct corner block by tapping the corners.
   - If you cannot match, tap the DUMP button to discard the block.

3. Scoring
   - +10 points: Correct corner match
   - -10 points: Wrong corner match
   - -5 points: Dumped a block that could have been matched
   - +1 point: Dumped a block that could not be matched  

4. Special Features
   - The corner colors change each round, keeping the game dynamic.
   - Timer displayed on the scoreboard shows real-time elapsed time.
   - Current score is prominently displayed in the center.
   - High scores are stored in local storage and shown on the scoreboard.

5. Controls
   - Tap corners: Match the central block with corner colors
   - DUMP button: Discard a block
   - Pause/Resume button: Pause the game at any time
   - Quit button: Restart the game

Layout
------
- Top middle: “MATCH THE COLOUR” title  
- Below title: Instructions (disappear after 10 seconds)  
- Current score: Displayed below instructions in large font  
- Canvas: Main game area with corner blocks, central block, and dump button  
- Top right: Scoreboard showing username, time, current high score, and all-time top score  
- Bottom right: Pause and Quit buttons  

Technical Details
-----------------
- HTML5 Canvas for rendering game elements
- JavaScript handles:
  - Game logic
  - Touch-based controls
  - Dynamic scoring
  - Timer
  - High score storage (localStorage)
- CSS for styling and layout

How to Run
----------
1. Save the HTML code as index.html.
2. Open index.html in a mobile or touch-enabled browser for best experience.
3. Start playing immediately!  

Note: High scores are saved per browser/device. Clearing browser data will reset scores.

Author
------
- Developed using HTML5, CSS, and JavaScript  
- Designed for touch-based interactive gameplay  
- Developed by Shakti 
