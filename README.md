# ERGO-MATIC

Play: https://kids-ergo-matic-eqjk.vercel.app/

ERGO-MATIC is a board-style ergonomics quiz game.

## How it plays

The player rolls a 3D die to move a robot along a question path. Landing on a question tile opens a three-choice ergonomics prompt.

**roll die → move → answer question → update score/lives → continue toward finish**

Rules:

- correct answer: +20 points;
- incorrect answer: -5 points, one life lost, and the robot returns to its pre-roll position;
- the run starts with two lives;
- reaching the finish tile ends the run and displays the score.

## Question topics

The built-in bank covers monitor position, wrist position while typing, backpack use, phone viewing height, mouse grip, foot support, lifting, sitting posture, movement, breaks, eye care, monitor distance and elbow angle.

## Content note

The prompts are simplified ergonomics game content rather than a complete ergonomics standard or professional assessment.

## Implementation

The game is contained in `index.html` and uses Three.js, Tailwind and canvas-confetti from public CDNs.

## Event activation

This game was developed as one module in a multi-game interactive children’s edutainment activation in the UAE.

Event production: [Peach Society](https://peach-society.com/) — Dubai-based event and experiential production company.
