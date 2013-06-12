# Summer Seminar

## Welcome

Welcome to Intro to Digital Design.

How's Summer Seminar so far?  Getting a feel for what life is like as a cadet?  Still want to come here?  My job today is to give you a little taste of academics at USAFA and what we do in the Electrical and Computer Engineering Department.

Set the tone: Relax.  I'm not assessing you.  My goal is that you have fun, learn some cool stuff, and leave her excited to learn more about Computer Engineering.  
On that note: YouTube videos with electrical engineer that hurts himself.  

Electricity Can Kill You - https://www.youtube.com/watch?v=DQJ8JX17J58
ESD - https://www.youtube.com/watch?v=RtlYi1yLTVQ
Proper Wiring Connections - https://www.youtube.com/watch?NR=1&v=vRwIrbK8KDI&feature=endscreen
Capacitors - https://www.youtube.com/watch?v=rr7bPmGTQUk

## Intros

- Instructor Introduction
- Student Introductions
    - Name, hometown, school

Why'd you sign up for this class?  Why engineering?  Why digital?  Allow for volunteers.

Why I think this stuff is cool.

We're not going to take the entire time - only 3 hours.  And I'll do my best to keep it interesting / engaging.

Block structure:  
- General Background Knowledge
- Digital Design
- Intro to Microcontrollers and Embedded Programming
- Soldering

## What's an engineer?

## General Background Knowledge
**I stuck with the outline used in past years for all of this**

- Analog vs Digital

- Numbering Systems
    - Decimal - base 10, 0-9
    - Binary - base 2, 0-1
    - Hex - base 16, so group binary into groups of 4
    - Octal - base 8, so group binary into groups of 3

- Vocabulary
    - Bit - a single piece of information, one value of 1 or 0
    - Byte - a grouping of 8 bits
    - Nibble - half of a byte, a grouping of 4 bits
        - Importance due to prevalence of hex
    - Word
        - Standard data size of a computer architecture
        - the data size a given architecture is comfortable operating with
        - modern computer word size is 64-bit

- Introduce Boolean Algebra
    - AND gate
        - Truth Table
        - Draw it
        - Equation
    - OR gate
        - Truth Table
        - Draw it
        - Equation
    - NOT gate
        - Truth Table
        - Draw it
        - Equation

- Introduce CADET Board
    - **There was confusion on this.  Take your time, use overhead projector to get this right**
    - Show where 5V and ground are, how to wire them up
    - Discuss how pins on protoboard are connected
    - Show how to insert NOT chip
        - Diagram in student handout
        - Show where 5V and ground are connected - **many students burned chips by wiring incorrectly, emphasize this**
        - show how to hook input up to switch, output to light to test
    - **Introduce Logic Probe**
        - Give them their take-home gift now, allow them to use it during the remainder of the class
- Introduce AND chip as mystery chip
    - Show them which pins correspond to input/output, but don't tell them what kind of gate it is
    - Have them figure out gate
    - Have them perform same analysis on OR chip

[BREAK!]

- Introduce Cadet Tracker problem
    - Walk through truth table
    - Introduce Product of Sums as way to derive equation from truth table
    - Build logic circuit from truth table
    - Have cadets build circuit - verify it works with switches, LEDs
    - **Completion times will vary**  If a cadet gets done early, expand exercise by having them sound the buzzer when the situation is "not ok"

- Show how Cadet Tracker could be simplified to NAND - you don't need such a complex circuit
    - How do we simplify?
        - Notice that A + 'A = 1
        - So B'A + BA is the same is saying A
        - We can use this to simplify circuits

- Address zoo problem
    - Work through truth table
    - Create equation with Product of Sums
    - Reduce using technique above
    - If you are moving really quickly, have them implement the circuit

That's cool, but so what?!  What really useful things can we make out of this?  
Say we wanted to add binary numbers together.  [Draw, walk through truth table, operation of half-adder, full-adder]  
This is the basis of addition inside of your computer!

By combining these basic elements into useful components, we can begin to do more and more complex tasks.

## Soldering
To this point, we've been dealing with combinational logic

- Combinational Logic
    - Output is determined by inputs

The decision stick kit uses sequential logic.

- Sequential Logic
    - Output is determined by inputs and previous state
    - Sequential logic circuits have memory!

Your decision stick kit will use sequential logic to count upward until it reaches a max - then starts over.

- Decision Stick Kit
    - Kits in front of room, give to cadets before they walk in
    - Lab tech will be there to set up stations, walk through kit, give soldering tutorial
    - Good to bring extra kit in case of fried components
    - Batteries in lab
