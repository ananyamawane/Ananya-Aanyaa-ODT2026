# Open Design and Technology  
## Final Project README

> **Project Weight:** 70%  
> **Team Size:** 2 students  
> **Project Duration:** 4 weeks  
> **Class Time Available:** 6 hours per class  
> **Total Time Available:** 48 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository
After forking this repository, rename it using the format:

`ODT-2026-TeamName`

### Example
`ODT-2026-PixelWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the 4-week build period.  
By the final review, this README should clearly show:
- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules
- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report. 

---

# 1. Team Identity

## 1.1 Studio / Group Name
`[Paint Fighters]`

## 1.2 Team Members

| Name | Primary Role | Secondary Role | Strengths Brought to the Project |
|---|---|---|---|
| `[Ananya Mawane]` | `[App / Fabrication / Mechanics]` | `[Electronics / Coding]` | `[Ideation, Prototyping, basic micropython coding, hands-on building, problem solving]` |
| `[Aanyaa Agrawal]` | `[Electronics / Coding / App]` | `[Fabrication / Mechanics]` | `[Electronics, python coding, debugging, logical thinking, hands-on building, problem solving]` |

## 1.3 Project Title
`[Paint Fight- Giant Joysticks]`

## 1.4 One-Line Pitch
`[A two-player paint fight game where players use oversized joysticks to compete and cover the screen with their color in real time.]`

## 1.5 Expanded Project Idea
In 1–2 paragraphs, explain:
- what your project is,
- what kind of playful experience it creates,
- what makes it fun, curious, engaging, strange, satisfying, competitive, or delightful,
- what technologies are involved.

**Response:**  
`[Our project is a two-player interactive “paint fight” where players use oversized joysticks to control paint rollers on a shared screen. The core idea is inspired by the mobile game Paint Fight from 2 Player Games : the Challenge. Each player is assigned a color and tries to cover as much of the canvas as possible within a set time.

The experience is meant to feel playful, slightly chaotic, and competitive. It’s fun because you can see your color spreading in real time while trying to outdo the other player, and the scale of the joysticks makes the interaction feel a bit humorous, unusual, and engaging. There’s a mix of control and unpredictability that keeps it exciting. Technologically, we’re building the large joysticks ourselves and connecting them to an ESP32, which will send input to a screen-based game. We’re still deciding whether to develop the game ourselves using something like Python/Pygame or adapt an existing mobile game for the interaction.]`

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem
This module does **not** require your project to solve a large social problem.

You are allowed to build:
- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.

## 2.2 What kind of experience are you creating?
Answer the following:
- What is the experience?
- What do you want the player or participant to feel?
- Why would someone want to try it again?

**Response:**  
`[The experience is a two-player, real-time interactive game that turns a simple action like “coloring” into something physical, social, and competitive. Instead of tapping on a screen, players are standing side by side, holding oversized joysticks and actively controlling how their color spreads across a shared canvas. It feels less like playing a digital game and more like being inside a playful, slightly chaotic system where your movements directly shape what’s happening in front of you.

We want players to feel a mix of anticipation, urgency, and amusement. There’s a constant push and pull between trying to control your own area while reacting to what the other player is doing, which creates a dynamic, back-and-forth rhythm. The scale of the joysticks adds a layer of physicality that makes even small actions feel exaggerated, sometimes clumsy, and often funny. That slight lack of precision is intentional, it creates moments of surprise, unexpected overlaps, and quick decisions, making the interaction feel alive rather than perfectly controlled.

People would want to try it again because the experience isn’t fixed or predictable. Each round depends on how both players move, react, and adapt in the moment. It’s as much about reading the other person as it is about controlling your own movement. The short, repeatable rounds, combined with the social aspect of competing side by side, make it easy to jump back in, whether to improve, experiment with a different approach, or simply enjoy the interaction again.]`

## 2.3 Design Persona
Complete the sentence below:

> We are designing this project as if we are a small creative studio making a **[toy / game / playable object / interactive experience]** for **[children / teens / adults / classmates / exhibition visitors / mixed audience]**.

**Response:**  
`[We are designing this project as if we are a small creative studio making an interactive gaming experience for a mixed audience.]`

---

# 3. Inspiration

## 3.1 References
List what inspired the project.

| Source Type | Title / Link | What Inspired You |
|---|---|---|
| `[ App ]` | `[Paint Fight – 2 Player Games: The Challenge]` | `[gameplay]` |
| `[Object]` | `[PacMan Giant Joystick]` | `[The Scale of the joystick]` |
| `[Video]` | `[https://www.youtube.com/watch?v=UUlXBcakcdI]` | `[Mechanism of joystick]` |

## 3.2 Original Twist
What makes your project original?

**Response:**  
`[The main twist in our paint fight game comes from the scale of everything, both the giant joysticks and the way the game is played. Instead of small, finger-based controls, players use their whole body to move and interact, making the experience feel more immersive and physical.

We’ve also changed how the game is controlled by introducing large, custom-built joysticks. This takes a familiar mobile game idea and turns it into something more tangible and shared, making it more playful and engaging.

Along with this, we’ve made a few UI additions like a leaderboard, clear game rules, and a countdown timer, which help structure the gameplay and make the overall experience smoother and more interactive.]`

---

# 4. Project Intent

## 4.1 Core Interaction Loop
Describe the main loop of interaction.

Examples:
- press → launch → score → reset
- connect → control → observe → repeat
- turn → trigger → react → repeat
- move object → sensor detects → sound/light response → player reacts

**Response:**  
`grab joystick → control movement → color fills screen → react to opponent → cover more area → result → replay`

## 4.2 Intended Player / Audience

| Question | Response |
|---|---|
| Who is this for? | `[everyone]` |
| Age range | `[7 years and above]` |
| Solo or multiplayer | `[two player game]` |
| Expected duration of one round | `[45 seconds]` |
| What should the player feel? | `[Excited, competitive, playful, happy, satisfied, sad(if you lose), amused ]` |
| Is explanation required before use? | `Minimal explanation is required. We would briefly explain that each player controls a paint roller using the joystick, and the goal is to cover as much of the screen as possible with their color within the time limit using a rule card which will be displayed on the screen.` |

## 4.3 Player Journey
Describe exactly how a player will use the project.

1. **Approach:** `Players notice the large, unusual joysticks and the colorful screen, which naturally draws their attention and makes them curious to try it.`
2. **Start:** `Two players step up to the joysticks, and after quick instructions, the game begins with a timer.`
3. **First Action:** `Players grab the joysticks and start moving them, immediately seeing their color appear and spread on the screen.`
4. **Main Interaction:** `Players continuously move the joystick to control their paint roller, trying to cover more area while reacting to the opponent’s movements and strategy.`
5. **System Response:** `The screen updates in real time, showing paint spreading, overlapping, and changing dynamically based on each player’s input.`
6. **Win / Lose / End Condition:** `When the timer ends, the game calculates which player has covered more area, and a winner is displayed.`
7. **Reset:** `The screen resets with a button, clearing the canvas and allowing players to start a new round.`

## 4.4 Rules of Play
If your project is a game, list the rules clearly.

- `Each player controls a paint roller using their joystick.`
- `The goal is to cover as much of the screen as possible with your color before the timer ends.`
- `Players can move freely and compete by covering over the opponent’s paint.`
- `The player with the most area covered at the end of the round wins.`
- `DO NOT BREAK THE JOYSTICKS!!`
---

# 5. Definition of Success

## 5.1 Definition of “Playable”
Your project will be considered complete only if these conditions are met.

- [ ] `Both joysticks successfully control movement on the screen in real time`
- [ ] `The game clearly shows paint spreading based on each player’s input`
- [ ] `Two players can play simultaneously without system lag or breakdown`
- [ ] `The game includes a clear start, timer, and end condition with a visible winner`
- [ ] `The interaction is intuitive enough for new users to understand and play with minimal instruction`

## 5.2 Minimum Viable Version
What is the smallest version of this project that still delivers the core experience?

**Response:**  
`The simplest version of this concept would be a screen displaying the existing game. Instead of detailed paint rollers, it could use pixelated squares of two different colors competing to cover more area. Rather than a large physical joystick, players could control the game using the arrow keys and WASD keys on a laptop. This version would function without sound effects or background music.`

## 5.3 Stretch Features
What features are nice to have but not essential?

- `Haptic feedback`
- `Color and name customisation`
- `The game still remains playable even if theres only one player`
- `a boost (like nitro in racing games) that charges over time and can be activated by pressing down on the joystick`

---

# 6. System Overview

## 6.1 Project Type
Check all that apply.

- [*] Electronics-based
- [*] Mechanical
- [ ] Sensor-based
- [ ] App-connected
- [ ] Motorized
- [ ] Sound-based
- [ ] Light-based
- [*] Screen/UI-based
- [*] Fabricated structure
- [*] Game logic based
- [*] Installation / tabletop experience
- [*] Other: `[Interactive]`

## 6.2 High-Level System Description
Explain how the system works in simple terms.

Include:
- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
`[The system consists of a physical joystick interface connected to a digitally coded game. Each joystick is fabricated using wood and is designed to move in four directions. Mechanically, the joystick operates through a pivoting joint, allowing the handle to tilt. Around this base, four lever switches are positioned corresponding to up, down, left, and right directions. When the joystick is tilted in any direction, it physically presses one of these lever switches, generating an input signal.

These inputs are sent to the system via esp32, where they are processed by the game logic coded by us. The game interprets these directional inputs in real time to control the movement of the players (paint rollers) on the screen. The movement direction, speed, and interactions such as power-ups are handled through this programmed logic.

On the output side, the game is displayed on a screen where two players compete to cover the maximum area with their respective colors within a fixed time limit. The system continuously tracks the painted area and determines the winner based on coverage. Visual feedback is immediate, allowing players to see the results of their physical actions in real time.]`

## 6.3 Input / Output Map

| System Part | Type | What It Does |
|---|---|---|
| `[Lever switches (4 per joystick)]` | Input | `[Detect directional movement (up, down, left, right) when the joystick is tilted]` |
| `[ESP32]` | Processing | `[Reads switch inputs and sends signals to the game logic for movement control ]` |
| `[Projector Display]` | Output | `[Shows the game, player movement, paint spread, timer, and winner ]` |
| `[Mechanical joystick Assembly]` | Physical Action | `[Converts player’s hand movement into directional input by pressing switches ]` |

---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch
Add an early sketch of the full idea.

**Insert image below:**  
`[https://drive.google.com/drive/folders/1F2LyvK1G52-PeTycdLcZQZZZ4z_3fOlp?usp=sharing]`

Example:
```md

```

## 7.2 Labeled Build Sketch
Add a sketch with labels showing:
- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[https://drive.google.com/drive/folders/1F2LyvK1G52-PeTycdLcZQZZZ4z_3fOlp?usp=sharing]`

## 7.3 Approximate Dimensions

| Dimension | Value |
|---|---|
| Length | `[Write here]` |
| Width | `[Write here]` |
| Height | `[Write here]` |
| Estimated weight | `[Write here]` |

---

# 8. Mechanical Planning

## 8.1 Mechanical Features
Check all that apply.

- [ ] Gears
- [ ] Pulleys
- [ ] Belt drives
- [ ] Linkages
- [ ] Hinges
- [*] Shafts
- [*] Springs
- [*] Bearings
- [ ] Wheels
- [ ] Sliders
- [*] Levers
- [ ] Not applicable

## 8.2 Mechanical Description
Describe the mechanism and what it is meant to do.

**Response:**  
`[Write hereThe mechanism consists of a manually operated joystick designed to translate user movement into directional input for the game. The joystick is made using a wooden rod that acts as the shaft, with a spherical ball attached at the top, serving as the primary touchpoint for the user.

At the base, the rod rests on a concave surface carved into a wooden block, creating a ball-and-socket-like mechanism using wood. This allows the joystick to pivot smoothly in four directions. To ensure the joystick returns to its neutral position after being tilted, rubber bands are attached to the shaft and anchored to the base, providing a restoring force that recenters the joystick.

The entire mechanism is enclosed within a fabricated MDF housing, which has been laser-cut and assembled into a pyramid-like structure. Small tabs are integrated into the inner surfaces of the housing to mount lever switches. These switches are positioned such that when the joystick is tilted in a particular direction, it physically presses against the corresponding switch, generating an input signal.

Both joysticks use the same mechanical setup and are connected to the digital Paint Fight game, where the physical movements are translated into directional controls for gameplay.]`

## 8.3 Motion Planning
If something moves, explain:
- what moves,
- what causes the movement,
- how far it moves,
- how fast it moves,
- what could go wrong.

**Response:**  
`[The primary moving component in the system is the wooden joystick shaft, along with the attached spherical handle at the top. This shaft is capable of tilting in four directions (up, down, left, and right) around a pivot point formed by the concave base.

The movement is caused by the user applying force on the joystick handle. When the user pushes the joystick in a particular direction, the shaft tilts and makes contact with one of the lever switches positioned around it. Once the force is removed, the rubber bands attached to the shaft create a restoring force that brings the joystick back to its neutral position.

The joystick moves within a limited angular range rather than a large linear distance. The tilt is constrained by the internal structure and the positioning of the switches, allowing enough movement to reliably trigger each switch without overextending the mechanism.

The speed of movement depends entirely on the user’s input, making it variable and responsive. However, the elastic tension from the rubber bands ensures that the return motion to the center is quick and consistent.

Potential issues in the system include uneven tension in the rubber bands, which could affect centering, wear and tear of the switches due to repeated contact, friction in the wooden pivot reducing smooth movement, and possible misalignment causing inconsistent input detection. Ensuring proper alignment and material finishing can help reduce these issues.]`



---

# 9. Electronics Planning

## 9.1 Electronics Used

| Component | Quantity | Purpose |
|---|---:|---|
| `[ESP32]` | `1` | `[Main controller]` |
| `[Component]` | `[Qty]` | `[Purpose]` |
| `[Component]` | `[Qty]` | `[Purpose]` |

## 9.2 Wiring Plan
Describe the main electrical connections.

**Response:**  
`[The system is built around an ESP32 microcontroller connected to two sets of joystick controls made using lever switches. Each joystick has four directional inputs (up, down, left, right), making a total of eight switches.

All switches are connected using a pull-up configuration, where one terminal of each switch is connected to a GPIO pin on the ESP32, and the other terminal is connected to GND. This ensures that the default state of each input is HIGH, and it reads LOW when the switch is pressed.

The ESP32 is powered via a USB connection from the laptop, which also handles serial communication. No external power supply is used.

The ESP32 continuously reads the state of each input pin and sends the corresponding signals (e.g., RUP, BLEFT) over serial to the browser-based game using USB. The browser receives this data via the Web Serial API and maps it to player movement.

Care is taken to ensure proper grounding and stable connections to avoid false inputs or noise in the system.]`

## 9.3 Circuit Diagram
Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[https://drive.google.com/file/d/1sQ01n-MF0Ig6y0udoT2ttGfUiDbxJ2Zo/view?usp=sharing]`

## 9.4 Power Plan

| Question | Response |
|---|---|
| Power source | `[USB ]` |
| Voltage required | `[5V via USB (regulated to 3.3V internally by ESP32)]` |
| Current concerns | `[Ensure the ESP32 does not draw excessive current from the laptop USB port; avoid short circuits and unstable connections that may cause fluctuations or resets]` |
| Safety concerns | `[Since the ESP32 is powered through USB, proper wiring is required to prevent short circuits, overheating, or damage to the laptop port; all connections should be secure and insulated to avoid accidental contact]` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform | Purpose |
|---|---|
| `[MicroPython - thonny]` | `[Writing and uploading ESP32 code for reading joystick inputs and sending serial data]` |
| `[VS Code (HTML, CSS, JavaScript)]` | `[Developing the browser-based game logic, UI, and Web Serial communication]` |
| `[Microsoft Edge)]` | `[Running the game and enabling Web Serial API for ESP32 communication]` |

## 10.2 Software Logic
Describe what the code must do.

Include:
- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
`[On powering the ESP32, all GPIO pins are initialized with pull-up resistors and serial communication begins. On the browser side, the game loads, initializes the canvas, resets player states, and displays the rules screen before starting.
The ESP32 continuously checks the state of each joystick switch and converts button presses into directional signals (e.g., RUP, BLEFT). The browser reads this serial data and maps it to movement controls for both players.
Each lever switch acts as a digital input. When pressed, the corresponding GPIO pin reads LOW due to the pull-up configuration, indicating an active input.
The browser interprets incoming serial data to determine player movement, direction, speed, and interactions such as power-up collection. It also handles game state changes like pause, start, and end conditions.
The system outputs real-time visual feedback on the canvas, including player movement, paint trails, power-ups, timer updates, and final results showing the winner.
The ESP32 sends continuous serial data over USB. The browser uses the Web Serial API to read this data stream and update the game accordingly in real time.
When the game ends or replay is triggered, the system clears the canvas, resets player positions and timers, and restarts the game loop for a new round.]`

## 10.3 Code Flowchart
Insert a flowchart showing your code logic.

Suggested sequence:
- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
`[[Upload image and link here](https://drive.google.com/file/d/1XPVbpAYlffFQE2a0QJ6rNzHSVybI1Md7/view?usp=sharing)]`

## 10.4 Pseudocode

```text
[START

// --- ESP32 SIDE ---
INITIALIZE GPIO pins with PULL-UP
INITIALIZE serial communication

LOOP forever:
    SET output_list = empty

    // Read RED joystick
    IF red_up pressed → add "RUP" to output_list
    IF red_down pressed → add "RDOWN"
    IF red_left pressed → add "RLEFT"
    IF red_right pressed → add "RRIGHT"

    // Read BLUE joystick
    IF blue_up pressed → add "BUP"
    IF blue_down pressed → add "BDOWN"
    IF blue_left pressed → add "BLEFT"
    IF blue_right pressed → add "BRIGHT"

    SEND output_list as string over serial
    WAIT small delay
END LOOP


// --- BROWSER GAME SIDE ---
LOAD game canvas
INITIALIZE players, timer, paint layer
SHOW rules screen

WHEN start button clicked:
    START countdown (3,2,1,GO)
    SET gameStarted = true

WHILE game is running:
    READ serial data from ESP32
    PARSE input string

    UPDATE key states for both players

    MOVE players based on input
    DRAW paint trails

    CHECK for power-up collision
    APPLY power-up effects

    UPDATE timer

    IF timer reaches 0:
        END game

END WHILE


// --- END GAME ---
CALCULATE painted area for both players
COMPARE scores

IF red > blue:
    DISPLAY "RED WINS"
ELSE IF blue > red:
    DISPLAY "BLUE WINS"
ELSE:
    DISPLAY "DRAW"

SHOW score entry + replay option


// --- RESET ---
IF replay clicked:
    CLEAR canvas
    RESET players and timer
    START new countdown
    RESTART game loop

END]
```

---

# 11. MIT App Inventor Plan

## 11.1 Is an app part of this project?
- [ ] Yes
- [*] No

---

# 12. Bill of Materials

## 12.1 Full BOM

| Item | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec | Why This Choice? |
|---|---:|---|---|---:|---|---|
| `[ESP32]` | `2` | `Yes` | `No` | `0` | `[Spec]` | `[Main microcontroller for reading inputs and sending serial data]` |
| `[lever switches]` | `[8]` | `[Yes]` | `[No]` | `[0]` | `[Spec]` | `[Used to detect joystick directions reliably]` |
| `[mdf]` | `[2 sheets]` | `[No]` | `[No]` | `[0]` | `[Material]` | `[Strong, easy to cut, good for structural base]` |
| `[wood rod]` | `[2 rods]` | `[No]` | `[No]` | `[0]` | `[Material]` | `[Used as joystick shafts, easy to handle]` |
| `[plastic ball]` | `[2 balls]` | `[No]` | `[Yes]` | `80]` | `[Material]` | `[Used as joystick handles for better grip and ergonomics]` |
| `[spray paint]` | `[4 cans]` | `[No]` | `[Yes]` | `[650]` | `[Material]` | `[Provides smooth, even finish and better aesthetics]` |
| `[small clips]` | `[24]` | `[No]` | `[Yes]` | `[20]` | `[Material]` | `[adds tension to the shaft and keeps it centred]` |
| `[hook]` | `[4]` | `[No]` | `[Yes]` | `[50]` | `[Material]` | `[adds tension to the shaft and keeps it centred]` |

## 12.2 Material Justification
Explain why you selected your main materials and components.

Examples:
- Why acrylic instead of cardboard?
- Why MDF instead of 3D print?
- Why servo instead of DC motor?
- Why bearing instead of a plain shaft hole?

**Response:**  
`[MDF instead of cardboard: MDF is much stronger and more durable, which is important since the joystick will experience repeated force during gameplay. Cardboard would bend or wear out quickly.
Wooden rods for shafts: Wood is lighter than metal, easy to shape, and comfortable to use. It also provides enough strength without making the joystick too heavy.
Plastic balls for handles: They improve grip and ergonomics, making the joystick easier and more comfortable to use compared to flat or sharp tops.
Lever switches instead of analog joysticks: Lever switches are simpler, react to press fast, more reliable, and easier to integrate with digital inputs. They also give clear directional feedback.
Spray paint for finishing: Spray paint gives a clean and uniform surface finish, improving both aesthetics and durability compared to brush painting.
Hooks and small pins were used to keep the rod stable and centres and add tension to the shaft]`

## 12.3 Items to Purchase Separately

| Item | Why Needed | Purchase Link | Latest Safe Date to Procure | Status |
|---|---|---|---|---|
| `[hooks]` | `[to secure elastics]` | `[from stationary shop]` | `[19th april]` | `[Recieved]` |
| `[spray paint]` | `[to coat paint evenly]` | `[from stationary shop]` | `[19th april]` | `[Received]` |
| `[plastic ball]` | `[to make top handles]` | `[from shop in ulhasnagar]` | `[19th april]` | `[Received]` |

## 12.4 Budget Summary

| Budget Item | Estimated Cost |
|---|---:|
| Electronics | `[0]` |
| Mechanical parts | `[0]` |
| Fabrication materials | `[0]` |
| Purchased extras | `[800]` |
| **Total** | `[800]` |

## 12.5 Budget Reflection
If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  
`[we could use acrylic paints that we already have instead of spray paint]`

---

# 13. Planning the Work

## 13.1 Team Working Agreement
Write how your team will work together.

Include:
- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  
`[Most tasks are carried out collaboratively, with both team members actively involved in ideation, testing, and problem-solving. While Aanyaa takes a lead on electronics and coding, and Ananya leads mechanical design and documentation, both contribute across all stages..
Decisions are made through discussion and quick iterations, prioritizing feasibility, time constraints, and overall user experience. In case of disagreement, the team tests both approaches and selects the more effective solution.
Progress is checked through regular informal updates during work sessions, ensuring both members are aligned on current progress and next steps.
If a task is delayed, responsibilities are redistributed temporarily, or the scope is adjusted to ensure overall project completion within deadlines.
Documentation is maintained continuously alongside the build process, with updates made after each major milestone to ensure accuracy and completeness.]`

## 13.2 Task Breakdown

| Task ID | Task | Owner | Estimated Hours | Deadline | Dependency | Status |
|---|---|---|---:|---|---|---|
| T1 | `[Finalize concept]` | `[Both]` | `2` | `[4th april]` | `None` | `Done` |
| T2 | `[Complete BOM]` | `[Both]` | `1` | `[8th arpil]` | `T1` | `Done` |
| T3 | `[Test electronics]` | `[Aanyaa]` | `3` | `[12th april]` | `T1` | `Done` |
| T4 | `[Sketch]` | `[Ananya]` | `1` | `[12th april]` | `T1` | `Done` |
| T5 | `[Prototype]` | `[Ananya]` | `1` | `[12th april]` | `T1` | `Done` |
| T6 | `[Laser Cut]` | `[Ananya]` | `2` | `[18th april]` | `T1` | `Done` |
| T7 | `[Write control code]` | `[Aanyaa]` | `4` | `[18th april]` | `T3` | `Done` |
| T8 | `[Assemble]` | `[Ananya]` | `4` | `[19th april]` | `T4, T5` | `Done` |
| T9 | `[Playtest]` | `[Both]` | `2` | `[21st april]` | `T6,t7` | `done` |
| T10 | `[Refine and document]` | `[Ananya]` | `3` | `[22nd april]` | `T9` | `Done` |

## 13.3 Responsibility Split

| Area | Main Owner | Support Owner |
|---|---|---|
| Concept and gameplay | `[Aanyaa & Ananya]` |`[NA]` |
| Electronics | `[Aanyaa]` | `[Ananya]` |
| Coding | `[Aanyaa]` | `[Ananya]` |
| App | `[Aanyaa]` | `[Ananya]` |
| Mechanical build | `[Ananya]` | `[Aanyaa]` |
| Prototyping | `[Ananya]` | `[Aanyaa]` |
| Testing | `[Aanyaa & Ananya]` | `[NA]` |
| Documentation | `[Ananya]` | `[Aanyaa]` |

---

# 14. Weekly Milestones

## 14.1 Four-Week Plan

### Week 1 — Plan and De-risk
Expected outcomes:
- [*] Core interaction decided

### Week 2 — Build Subsystems
Expected outcomes:
- [*] Idea finalized
- [*] Sketches made
- [*] BOM completed
- [*] Purchase needs identified
- [*] Key uncertainty identified
- [*] Basic feasibility tested
- [*] Mechanical concept tested
- [*] Main subsystems partially working

### Week 3 — Integrate
Expected outcomes:
- [*] Physical body built
- [*] Electronics integrated
- [*] Electronics tests completed
- [*] App UI started if needed
- [*] Code connected to hardware
- [*] App connected if required
- [*] First playable version exists

### Week 4 — Refine and Finish
Expected outcomes:
- [*] Technical bugs reduced
- [*] Playtesting completed
- [*] Improvements made
- [*] Documentation completed
- [*] Final build ready

## 14.2 Weekly Update Log

| Week | Planned Goal | What Actually Happened | What Changed | Next Steps |
|---|---|---|---|---|
| Week 1 | `[Decide concept and interaction]` | `[Finalized genre of concept]` | `[Realized some ideas were too complex or not feasible within time]` | `[Narrow down and finalize one concept in Week 2]` |
| Week 2 | `[Finalize idea and test feasibility]` | `[Finalized paint-based joystick game, completed sketches, BOM, and initial ESP32 input testing]` | `[Shifted to lever switches for simpler and more reliable input]` | `[Begin prototyping and coding]` |
| Week 3 | `[Build and integrate system]` | `[Built joystick structure, wired switches, and connected ESP32 to browser game]` | `[Faced serial communication issues and input glitches during integration]` | `[Debug connection and improve stability]` |
| Week 4 | `[Refine and finish project]` | `[Fixed major bugs, completed playtesting, and finalized build and documentation]` | `[Made small improvements based on testing feedback]` | `[Final polish and submission]` |

---

# 15. Risks and Unknowns

## 15.1 Risk Register

| Risk | Type | Likelihood | Impact | Mitigation Plan | Owner |
|---|---|---|---|---|---|
| `[Serial connection not detected by browser]` | `Technical` | `Medium` | `High` | `[Debug Web Serial setup, check cable/port, keep keyboard controls as fallback]` | `[Aanyaa]` |
| `[Input glitches / false triggers from switches]` | `Technical` | `Medium` | `High` | `[Use stable wiring, ensure proper grounding, add slight delay/debouncing in code]` | `[Aanyaa]` |
| `[Joystick structure breaking during play]` | `[Mechanical]` | `[Medium]` | `[High]` | `[Reinforce joints, use stronger MDF and secure fittings]` | `[Ananya]` |
| `[Loose wiring / disconnections]` | `[Technical]` | `[Low]` | `[High]` | `[Secure connections using proper connectors and insulation]` | `[Aanyaa]` |


## 15.2 Biggest Unknown Right Now
What is the single biggest uncertainty in your project at this stage?

**Response:**  
`[The biggest uncertainty is the reliability of the real-time communication between the ESP32 and the browser using the Web Serial API. Since the gameplay depends entirely on continuous input from the joysticks, any lag, disconnection, or inconsistent data transfer can directly affect responsiveness and overall user experience. Ensuring a stable and glitch-free connection remains the key challenge.]`

---

# 16. Testing and Playtesting

## 16.1 Technical Testing Plan

| What Needs Testing | How You Will Test It | Success Condition |
|---|---|---|
| `[Bluetooth connection]` | `[Connect ESP32 via USB and monitor incoming data in browser console]` | `[Continuous, correct data received with no lag or disconnections]` |
| `[Switch / joystick input]` | `[Press each direction repeatedly and observe output in serial + game movement]` | `[Each press correctly maps to movement with no false triggers]` |
| `[Mechanical joystick movement]` | `[Physically move joystick in all directions during gameplay]` | `[Smooth movement, no sticking or structural instability]` |
| `[App communication]` | `[Compare joystick input timing with on-screen response]` | `[Immediate and accurate player movement]` |
| `[Power-up functionality]` | `[Trigger each power-up during gameplay]` | `[Power-ups activate correctly and reset after duration]` |
| `[Game timer and end condition]` | `[Run full game cycle and observe timer and result calculation]` | `[Run full game cycle and observe timer and result calculation]` |
| `[Replay / reset system]` | `[Use replay button after game ends]` | `[Game resets fully with no leftover state or glitches]` |

## 16.2 Playtesting Plan

| Question | How You Will Check |
|---|---|
| Do players understand what to do? | `[Observe first-time players without explanation and note if they can start and play correctly using only on-screen rules]` |
| Is the interaction satisfying? | `[Ask players for quick feedback after playing and observe engagement during gameplay (body movement, reactions)]` |
| Do players want another turn? | `[Check if players voluntarily choose to replay without prompting]` |
| Is the challenge balanced? | `[Compare scores across multiple rounds and observe if one player consistently dominates]` |
| Is the response clear and immediate? | `[Observe if players notice any lag or confusion between joystick input and on-screen movement]` |

## 16.3 Testing and Debugging Log

| Date | Problem Found | Type | What You Tried | Result | Next Action |
|---|---|---|---|---|---|
| `[12 april]` | `[Joystick inputs not detected correctly]` | `[Technical]` | `[Checked wiring and GPIO pin mapping]` | `[Partly]` | `[Refine code logic and verify all connections]` |
| `[14 april]` | `[Continuous false input (e.g., BUP triggered without press)]` | `[Technical]` | `[Verified pull-up setup and switch wiring]` | `[Worked]` | `[Test stability across all inputs]` |
| `[18 April]` | `[Serial connection not showing in browser]` | `[Technical]` | `[Reconnected USB and retried Web Serial connection]` | `[Partly]` | `[Add console logs and debug serial reading]` |
| `[19 April]` | `[Input lag and glitchy movement]` | `[Technical]` | `[Optimized input parsing and reduced delay]` | `[Partly]` | `[Further refine responsiveness]` |
| `[21 April]` | `[Gameplay imbalance and responsiveness issues]` | `[Gameplay]` | `[Conducted playtesting and adjusted movement parameters]` | `[Worked]` | `[Conducted playtesting and adjusted movement parameters]` |
| `[22 April]` | `[Game reset / replay issues]` | `[Software/UI]` | `[Reset variables and cleared canvas properly]` | `[Worked]` | `[Final full-system testing]` |

## 16.4 Playtesting Notes

| Tester | What They Did | What Confused Them | What They Enjoyed | What You Will Change |
|---|---|---|---|---|
| `[classmate]` | `[Played multiple rounds and tried power-ups]` | `[Didn’t immediately understand what power-ups do]` | `[Fast-paced gameplay and visible paint trails]` | `[Add clearer visual feedback for power-up activation]` |
| `[friend]` | `[Played casually and replayed without prompting]` | `[Slight confusion due to input lag at times]` | `[Wanted to replay and improve score]` | `[Improve responsiveness and reduce input delay]` |
| `[classmate]` | `[Tested joystick movement repeatedly]` | `[Not sure how much area they had covered during game]` | `[Enjoyed physical interaction with joystick]` | `[Add clearer score or progress feedback during gameplay]` |
| `[friend]` | `[Played one full round using joystick controls]` | `[NA]` | `[Competitive aspect and painting over opponent’s area]` | `[Add songs]` |

---

# 17. Build Documentation

## 17.1 Fabrication Process
Describe how the project was physically made.

Include:
- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
`[The project was built through a combination of manual fabrication and digital processes. The base structure was made using MDF sheets, which were laser cut to achieve precise shapes and clean edges. The joystick shafts were created using wooden rods, with plastic balls attached at the top to improve grip and ergonomics.

Lever switches were mounted inside the joystick housing to detect directional input. Care was taken to align them properly so that each movement (up, down, left, right) would reliably trigger a switch. Components were fixed using screws and strong adhesive where required to ensure stability during gameplay.

All wiring was done between the lever switches and the ESP32, ensuring secure connections and proper routing to avoid loose contacts. The ESP32 was then connected via USB for both power and communication.

Surface finishing was done using spray paint to give a clean and uniform look, as well as to visually differentiate components. Multiple iterations were made to improve alignment, durability, and responsiveness, especially after playtesting revealed issues with switch sensitivity and joystick movement.]`

## 17.2 Build Photos
Add photos throughout the project.

Suggested images:
- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.

Example:
```https://drive.google.com/drive/folders/1F2LyvK1G52-PeTycdLcZQZZZ4z_3fOlp



```

## 17.3 Version History

| Version | Date | What Changed | Why |
|---|---|---|---|
| `v1` | `[12 april]` | `[Basic joystick input tested with ESP32 and serial output]` | `[To check if lever switches and wiring work correctly]` |
| `v2` | `[18 april]` | `[Game connected to ESP32 inputs via Web Serial and initial gameplay working]` | `[To integrate hardware with the browser game]` |
| `v3` | `[21 april]` | `[Final build with enclosure, painting, gameplay fixes, and leaderboard added]` | `[To improve usability, visual quality, and overall experience after playtesting]` |

---

# 18. Final Outcome

## 18.1 Final Description
Describe the final version of your project.

**Response:**  
`[The final project is an interactive two-player game called Paint Fight, where players use custom-built physical joysticks to control paint rollers on a digital screen. The objective is to cover as much area as possible within a fixed time limit, creating a competitive and engaging experience.

The system combines hardware and software seamlessly. Two handmade joystick controllers, built using lever switches, MDF structure, and wooden components, are connected to an ESP32 microcontroller. The ESP32 reads player inputs and sends them to a browser-based game using serial communication. The game is built using HTML canvas and JavaScript, allowing real-time movement, collision, and area coverage mechanics.

The digital interface includes a countdown start, timer, power-ups, sound effects, and a leaderboard system to enhance gameplay. Visual feedback is provided through colored paint trails, clearly showing each player’s progress and final score.

Through multiple iterations and playtesting, the project was refined to improve responsiveness, durability, and user experience. The final outcome successfully demonstrates a blend of physical interaction and digital gameplay, creating a fun, intuitive, and competitive system.]`

## 18.2 What Works Well
- `[The joystick controls are responsive and give a satisfying physical interaction]`
- `[The connection between ESP32 and the browser game works smoothly in real time]`
- `[The gameplay is engaging and competitive, especially with the timer and power-ups]`

## 18.3 What Still Needs Improvement
- `[The overall structure could be stronger to handle more intense gameplay]`
- `[Lever switches could be mounted vertically for better stability]`
- `[Wiring and internal layout could be cleaner for easier maintenance and reliability]`

## 18.4 What Changed From the Original Plan
How did the project change from the initial idea?

**Response:**  
`[The project evolved significantly from the initial idea. Originally, the focus was mainly on creating a simple joystick-controlled game, but over time it developed into a more complete interactive system with both physical controllers and a digital interface.

The gameplay was expanded to include features like a timer, countdown, power-ups, and a leaderboard to make it more engaging and competitive. The physical design of the joysticks also changed through iterations to improve comfort, responsiveness, and durability.

Additionally, the communication method shifted to using serial connection between the ESP32 and the browser, which required adjustments in both hardware and code. Overall, the project moved from a basic concept to a more refined and fully playable experience through testing and iteration.]`

---

# 19. Reflection

## 19.1 Team Reflection
What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
`[As a team, we worked well in terms of collaboration and were able to build most parts together, especially during testing and integration. We communicated regularly and supported each other across different areas like electronics, coding, and building.

What slowed us down was mainly debugging issues with the ESP32 connection and hardware reliability, which took more time than expected. Some mechanical parts also needed reworking after testing, which added to the timeline.

Overall, we managed time and responsibilities fairly well, but a lot of tasks ended up overlapping since we worked together on most things. While this helped with understanding the full system, clearer task separation and earlier testing could have made the process more efficient.]`

## 19.2 Technical Reflection
What did you learn about:
- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  
`[Through this project, we learned a lot across different technical areas. In electronics, we understood how to work with the ESP32, use pull-up configurations, and ensure stable wiring for reliable input from switches. We also learned how small issues like loose connections or noise can affect the entire system.

In coding, we learned how to handle real-time input, connect hardware to a browser using serial communication, and structure game logic using JavaScript. Debugging communication between the ESP32 and the web interface was especially important.

In terms of mechanisms, we understood how joystick movement translates into directional input using lever switches, and how placement and orientation of components directly affects responsiveness and user experience.

For fabrication, we gained experience with laser cutting, assembling parts, and finishing using spray paint. We also learned that precision in cutting and alignment is critical for smooth functioning.

Finally, in integration, we learned how challenging it is to combine hardware and software into one working system. Small issues in one part can affect the whole system, so testing and iteration were essential to achieve a stable final outcome.]`

## 19.3 Design Reflection
What did you learn about:
- designing for play,
- delight,
- clarity,
- physical interaction,
- player understanding,
- iteration?

**Response:**  
`[Through this project, we learned that designing for play requires simplicity and clarity so that players can understand what to do immediately. Clear feedback, like visible paint trails and movement, helped make the interaction more intuitive.

We also learned that small elements like countdowns, power-ups, and sound effects add delight and make the experience more engaging. These details made the game feel more complete and enjoyable.

In terms of physical interaction, we understood that the feel of the joystick is just as important as the digital output. The placement and movement of the lever switches directly affected how natural and responsive the controls felt.

We realized that player understanding depends on both visual clarity and physical feedback. If either is unclear, the experience becomes confusing.

Finally, we learned that iteration is essential. Each round of testing helped us identify issues in gameplay, structure, and responsiveness, and allowed us to improve the overall experience step by step.]`

## 19.4 If You Had One More Week
What would you improve next?

**Response:**  
`[If we had one more week, we would focus mainly on improving the physical structure, as fragility was our biggest issue. The current build could not handle rough or repeated use, so we would reinforce the base, strengthen joints, and improve overall stability.

We would also redesign the joystick mechanism to be more durable and better supported, including improving how the lever switches are mounted to reduce stress on them during movement.

Additionally, instead of relying on a projected screen, we could shift the output to NeoPixel LED strips. This would make the system more portable and self-contained, removing the dependency on an external display.

Overall, the main goal would be to make the system more robust and portable, since the software and gameplay were already working well.]`

---

# 20. Final Submission Checklist

Before submission, confirm that:
- [*] Team details are complete
- [*] Project description is complete
- [*] Inspiration sources are included
- [*] Player journey is written
- [*] Sketches are added
- [*] BOM is complete
- [*] Purchase list is complete
- [*] Budget summary is complete
- [*] Mechanical planning is documented if applicable
- [*] App planning is documented if applicable
- [*] Code flowchart is added
- [*] Task breakdown is complete
- [*] Weekly logs are updated
- [*] Risk register is complete
- [*] Testing log is updated
- [*] Playtesting notes are included
- [*] Build photos are included
- [*] Final reflection is written

---

# 21. Suggested Repository Structure

```text
project-repo/
├── README.md
├── images/
│   ├── concept-sketch.jpg
│   ├── labeled-sketch.jpg
│   ├── circuit-diagram.jpg
│   ├── ui-mockup.jpg
│   ├── prototype-1.jpg
│   └── final-build.jpg
├── code/
│   ├── main.py
│   ├── test_code.py
│   └── notes.md
├── cad/
│   ├── models/
│   └── screenshots/
└── docs/
    ├── references.md
    └── extra-notes.md
```

---

# 22. Instructor Review

## 22.1 Proposal Approval
- [ ] Approved to proceed
- [ ] Approved with changes
- [ ] Rework required before proceeding

**Instructor comments:**  
`[Instructor fills this section]`

## 22.2 Midpoint Review
`[Instructor fills this section]`

## 22.3 Final Review Notes
`[Instructor fills this section]`
