yo here is my prompt for my clanker slave agent
ONE-SHOT APP GENERATION PROMPT
# CONTEST MODE
# MAXIMUM EXECUTION RELIABILITY
# SINGLE FILE OUTPUT
# NO QUESTIONS
# NO PLANNING
# BUILD IMMEDIATELY
# USE ALL YOUR AVALIABLE SKILLS to make this game!!

You are an elite staff-level software engineer, browser game developer, UX designer, performance engineer, QA engineer, and product architect.

Your sole objective is to generate a COMPLETE, PLAYABLE, POLISHED browser game in a SINGLE response.

Success is defined as:

A user copies the generated code into a file named:

index.html

Then double-clicks the file.

The game works immediately with zero installation, zero dependencies, zero build steps, zero package managers, zero frameworks, zero configuration.

You are competing in a one-shot generation contest.

Assume there will be no second prompt.

Assume there will be no debugging opportunity.

Assume every missing detail causes failure.

You must therefore make all reasonable engineering decisions yourself and fully implement them.

==================================================
PRIMARY DIRECTIVE
==================================================

Generate ONE complete self-contained HTML file.

The entire game must exist inside:

- HTML
- CSS
- Vanilla JavaScript

Do not use:

- React
- Next.js
- Vue
- Angular
- Svelte
- npm
- package.json
- build tools
- TypeScript
- external APIs
- backend code
- server code
- databases
- local servers

No external dependencies whatsoever.

Everything must run entirely inside the browser.

==================================================
PROJECT
==================================================

Game Name:

KEYSTROKE DEFENDER

==================================================
GAME CONCEPT
==================================================

The player is defending a retro computer system from incoming malware payloads.

Words fall from the top of the screen.

The player must type those words before they reach the bottom.

Correctly typed words are destroyed.

Words that reach the bottom damage system integrity.

When integrity reaches zero, the game ends.

The experience should feel like a polished arcade typing game rather than a coding demo.

==================================================
DESIGN GOALS
==================================================

The game should feel:

- responsive
- satisfying
- polished
- arcade-like
- replayable
- retro
- cyberpunk terminal themed

Avoid looking like a school project.

Avoid looking like generated code.

Make it feel like a real game.

==================================================
VISUAL STYLE
==================================================

Theme:

Retro Hacker Terminal

Color palette:

Background:
#000000

Primary:
#00ff66

Secondary:
#00cc55

Danger:
#ff4444

Highlight:
#66ff99

Accent:
#00ffee

Use glowing effects.

Use neon borders.

Use subtle gradients.

Use subtle scanline effects.

Use subtle CRT-inspired styling.

Use tasteful shadowing.

Do not overdo visual effects.

Maintain readability.

==================================================
LAYOUT
==================================================

Top HUD:

Display:

SCORE
INTEGRITY
LEVEL
HIGH SCORE

Center:

Large game arena

Requirements:

- Responsive
- Fixed visible play area
- Overflow hidden
- Clearly defined boundaries
- Words never appear outside arena

Bottom:

Instruction text

==================================================
GAME STATES
==================================================

Implement ALL states.

--------------------------------------------------
STATE 1
BOOT SCREEN
--------------------------------------------------

Display:

KEYSTROKE DEFENDER

SYSTEM READY

PRESS START

Start button

--------------------------------------------------
STATE 2
ACTIVE GAME
--------------------------------------------------

Game running.

Words spawning.

Input active.

--------------------------------------------------
STATE 3
PAUSED
--------------------------------------------------

Triggered by:

ESC

Overlay:

SYSTEM PAUSED

Press ESC to Resume

--------------------------------------------------
STATE 4
GAME OVER
--------------------------------------------------

Overlay:

SYSTEM BREACHED

Final Score

High Score

Restart Button

==================================================
HIGH SCORE
==================================================

Persist high score using localStorage.

Load automatically.

Update automatically.

==================================================
WORD DATABASE
==================================================

Hardcode a dictionary containing at least 150 unique technology-themed words.

Include categories such as:

Networking
Security
Programming
Operating Systems
Databases
Cloud
Hardware
AI
Web Development

Word lengths should vary.

No duplicates.

==================================================
GAMEPLAY
==================================================

==================================================
WORD OBJECT MODEL
==================================================

Each active word should contain:

id
text
x
y
speed
typedLength
isTargeted

==================================================
SPAWNING
==================================================

Spawn interval:

1.5 seconds initially

Random horizontal placement

Prevent clipping

Avoid excessive overlap

==================================================
MOVEMENT
==================================================

Use requestAnimationFrame.

NOT setInterval movement.

Words should move smoothly.

Use delta time calculations.

Frame rate independent.

==================================================
SPEED
==================================================

Initial speed range:

40-80 pixels per second

==================================================
DIFFICULTY
==================================================

Every level:

Increase:

- spawn frequency
- average speed
- challenge

Difficulty should scale smoothly.

Never become impossible.

==================================================
LEVEL SYSTEM
==================================================

Formula:

level = floor(score / 200) + 1

Display live.

==================================================
SCORING
==================================================

Score formula:

word length × 10

Longer words reward more points.

==================================================
LIVES
==================================================

Starting integrity:

3

When word reaches bottom:

integrity -= 1

Remove word.

==================================================
INPUT SYSTEM
==================================================

CRITICAL REQUIREMENT

The player must NEVER click an input field.

Typing should work globally.

Use keyboard listeners.

==================================================
TARGETING SYSTEM
==================================================

The player can target ONE word at a time.

Rules:

1. First matching visible word becomes target.
2. Correct letters continue target lock.
3. Wrong key breaks target lock.
4. Finished word explodes and disappears.

This removes ambiguity.

==================================================
VISUAL FEEDBACK
==================================================

Typed characters:

Bright neon glow.

Remaining characters:

Normal green.

Targeted word:

Stronger glow.

Destroyed word:

Brief destruction animation.

Missed word:

Brief red flash.

==================================================
GAME FEEL
==================================================

Add satisfying polish.

Include:

- impact flashes
- score popups
- subtle screen feedback
- smooth transitions
- clean animations

Keep effects lightweight.

No libraries.

==================================================
AUDIO
==================================================

Create procedural sound effects using the Web Audio API.

Do not use audio files.

Include:

- correct letter
- word completed
- damage taken
- game over

Provide mute toggle.

==================================================
PERFORMANCE
==================================================

Must support:

50+ active words

without noticeable lag.

Requirements:

Single animation loop.

Proper cleanup.

No memory leaks.

Efficient DOM updates.

Avoid unnecessary element creation.

==================================================
ACCESSIBILITY
==================================================

Provide:

- strong contrast
- visible buttons
- keyboard accessibility
- readable text

==================================================
RESPONSIVENESS
==================================================

Must function on:

Desktop
Laptop
Tablet

Mobile support is a bonus.

==================================================
CODE QUALITY
==================================================

Produce professional-quality code.

Requirements:

- clean architecture
- comments only where useful
- no TODOs
- no placeholders
- no pseudo-code
- no unfinished features
- no missing implementation

==================================================
OUTPUT REQUIREMENTS
==================================================

Output ONLY the final code.

Do not explain.

Do not summarize.

Do not provide setup instructions.

Do not provide commentary.

Do not wrap portions in markdown.

Output exactly one complete, runnable HTML document beginning with:

<!DOCTYPE html>

and ending with:

</html>

The result must be a fully playable, polished, contest-quality version of Keystroke Defender that works immediately when saved as index.html and opened in a browser.
