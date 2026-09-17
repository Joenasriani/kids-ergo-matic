# ERGO-MATIC

Play: https://kids-ergo-matic-eqjk.vercel.app/

ERGO-MATIC is a board-style ergonomics quiz game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

The player rolls a 3D die to move a robot along a path of ergonomics-themed question tiles. Landing on a question tile opens a three-choice question.

**roll die → move along path → answer ergonomics question → update score/lives → continue toward finish**

- Correct answer: +20 points.
- Incorrect answer: -5 points, one life lost, and the robot returns to its position before that roll.
- The run starts with two lives.
- Reaching the finish tile ends the run and displays the total score.

## Topics represented

The current question bank includes monitor position, wrist position while typing, backpack use, phone viewing height, mouse grip, foot support, lifting, sitting posture, movement, breaks, eye care, monitor distance and elbow angle.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Evidence boundary

The quiz uses simplified ergonomics statements for game play. The repository does not establish those statements as a complete ergonomics standard, and it contains no study measuring posture change, injury prevention, retention, or transfer outside the game.

## Repository scope

The playable implementation is contained entirely in `index.html` and loads Three.js, Tailwind and canvas-confetti from public CDNs.

`index.html` is preserved as the game artifact. Documentation and discovery files must not alter the question bank, answer keys, die behavior, movement, scoring, lives, board layout, controls, visuals, timing, or runtime behavior.
