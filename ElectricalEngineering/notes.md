# Summer Seminar

## Welcome

Welcome to Intro to Electrical Engineering

How many of you took Intro to Digital Design with me yesterday?  What'd you think?

Everyone else:
How's Summer Seminar so far?  Getting a feel for what life is like as a cadet?  Still want to come here?  My job today is to give you a little taste of academics at USAFA and what we do in the Electrical and Computer Engineering Department.

Set the tone: Relax.  I'm not assessing you.  My goal is that you have fun, learn some cool stuff, and leave her excited to learn more about Electrical Engineering.

On that note: YouTube videos with electrical engineer that hurts himself.

- Electricity Can Kill You - https://www.youtube.com/watch?v=DQJ8JX17J58
- ESD - https://www.youtube.com/watch?v=RtlYi1yLTVQ
- Proper Wiring Connections - https://www.youtube.com/watch?NR=1&v=vRwIrbK8KDI&feature=endscreen
- Capacitors - https://www.youtube.com/watch?v=rr7bPmGTQUk

## Intros

- Instructor Introduction
- Student Introductions
    - Name, hometown, school

Why'd you sign up for this class?  Why engineering?  Why electrical?  Allow for volunteers.

Why I think this stuff is cool.
My interest lays more on the computer engineering / computer science things side of things.  But EE is the foundation of it all.  It's very important to have a strong foundation in the low-level stuff in order to understand the higher level stuff.  It's also practical.  In order to build cool things with embedded devices, you need to know how analog electronics work.  Need to know how to power your devices without frying them, etc.

We're not going to take the entire time - only 3 hours.  And I'll do my best to keep it interesting / engaging.

Block structure:

- Intro to Circuits
- Tour
- Soldering

## General Background Knowledge

Get them to grab their DMMs - we're going to be using them the entire class.  DMM is a tool to measure a variety of circuit variables.

Introduce circuit variables - using water analogy

- Voltage (V, Volts) - how hard we're pushing water through the pipe.  Our water pressure.
    - show them power supply on desk.
    - have them turn it on, turn to 5V on the meter, measure it with the DMM.
    - when we push electrons through a device, we use some of that pressure.  That's why we say there's a voltage drop ACROSS a device.
- Resistance (R, Ohms) - the diameter of our pipe.  Higher resistance means smaller pipe - it's harder to push water through there.  Harder to push current through.
    - have them grab a 1k resistor out of the desk
    - introduce them to the plugboard, have them plug the resistor in
    - show how to measure resistance with DMM
    - maybe talk about why the resistance is not exactly the printed value
- Current (I, Amps) - the actual water flowing through the pipes.  The electrons flowing through our circuit.
    - current flows through a device

- Introduce Ohm's Law
    - V=IR
    - simple equation that shows how all of these variable are related
    - if we hold voltage constant, as resistance goes down, what should happen to current?  It should increase!

Current can only flow if there's a path for it to flow through.  So let's give it one.

Let's make our first circuit - simple series circuit with 5V source and 1k resistor.  Wires are in bottom drawer of desks.

- Use DMM to measure voltage, make sure it's 5V.
- Remember, current is measured through a device.  In a circuit like this, current can only flow through one path - so the current will be the same throughout the circuit.
- What should we expect the current to be?  Should be 5mA.
- When we measure current, we have to break the circuit and make current flow through our DMM to measure it.  Show them how.
- Cool, it matches!

Let's talk about some other circuit rules:

- KVL
    - The sum of the voltages in a loop is 0.  Or voltage rise equals voltage drop in a loop.
    - What's a loop?
    - Identify loops on the board.
    - Validate with simple circuit, DMM.

How many loops in our simple circuit?  Based on KVL, what should the voltage drop be across our resistor?  That's right, all 5V!  Add series resistor to circuit.  How many loops?  Measure voltage across each, show they add up to the full 5V.  
Add resistor in parallel.  How many loops now?  Voltage across each?

Another rule:

- KCL
    - The sum of the currents at a node is 0.  Or current entering equals current leaving a ndoe.
    - What's a node.
    - Identify nodes on the board.
    - Validate with simple circuit, DMM.  Show that current coming in from source equals sum of currents flowing out.
    - Notice that current follows **the path of least resistance**

Combining resistors.  Resistors are a great way to model devices, like computers, lightbulbs, hair dryers, etc.  
When resistors are in series (meaning all current through one flows through the other), we can combine by adding.  Allow them to validate with DMM.

When resistors are in parallel (meaning they share two nodes), we combine by 1/Req = 1/R1 + 1/R2 + ...  Allow them to validate with DMM.

We can use this to simplify circuits!

When we plug devices in to plugs in our house, we're adding devices in _parallel_.  [Draw simple circuit on the board].  
What is a short circuit?  It's when we create a path through the circuit with little or no resistance.  If we add a short to our home wiring system, all of the current will flow through that element of the circuit.  Remember V=IR?  What happens when R approaches 0?  Current goes way up!  If current is sufficiently high, wires can't handle it and can start electrical fires - which is a bad thing.

How do we protect against that?  Fuses!  
[Demo: 10 Ohm resistor to 6V source - gives 0.6A, burns resistor.  This resistor can't handle that much _power_.  Show that resistance of fuse is close to 0.  Plug in series to new resistor, show how resistance goes up if current goes up - fuse burns out.  We've lost the fuse, but the device is protected.  That's how fuses and circuit breakers work - protect our devices / wiring.]

Power - how much work we do in a circuit, measured in Watts
P = IV

## ECE Facilities Tour
- UAS Lab
- Power Lab
- Anechoic Chambers
- Elevator up to 6th floor to check out solar panels
- Take them into the garage and show them the electric car.  Let them drive it around the parking lot - that was a big hit.

## Soldering
Electronic Bagpipes

- Kits are in front of classroom
- Lab tech will have all stations set up in back of 2G6
- Lab tech will give instruction on kits, soldering
- Batteries availble in lab of 2G6
- Good to bring an extra kit to cannibalize in case students fry any components.
