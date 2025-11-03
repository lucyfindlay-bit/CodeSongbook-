**Project Overview**

Code Songbook is a creative coding project made in TunePad using Python. It generates short songs entirely through code rather than using any pre-recorded sound.

The idea began as a bigger project called Mood 2 Music, which aimed to generate playlists that changed based on a listener’s mood. After experimenting, I realised that was too advanced for TunePad and my current coding skills, so I re-scoped the idea into something simpler and achievable.

Code Songbook recreates three familiar melodies: Twinkle Twinkle Little Star, Ode to Joy, and Greensleeves — using short Python scripts built from loops, variables, and timing logic. The project focuses on learning how musical structure can be expressed through programming, and how repetition, timing, and logic combine to make sound.

**Technologies and Tools**

Python 3 (TunePad browser environment)

TunePad built-in functions (playNote(), setTempo())

Python’s random module for variation and human-like timing

No external libraries or installations required

**Features**

Three separate songs coded note by note using Python functions

Clear structure with dedicated melody and chord sections

Adjustable variables for tempo, cycles, and note speed

Subtle randomisation to make playback sound more natural

Full commenting throughout for clarity and readability

**Running the Project**

This project runs directly in TunePad, so there’s no installation process.



Head to tunepad.com and sign in.

Create a new Python project.

Copy the full code from this repository into your TunePad editor.

Press the Run button at the top of the screen.

If everything works, you’ll hear Twinkle Twinkle Little Star first.

To play another song, scroll to the end of the code and switch functions like this:

# play_twinkle()
# play_ode()
# play_greensleeves()

If no sound comes through, make sure your browser tab isn’t muted and that the correct instrument (“Keys”) is selected. TunePad handles all sound output automatically.

**How the Code Works**

Each song is created through its own Python function, which plays notes in order using playNote().
Lists of MIDI note numbers define the melodies and chord progressions.

You can adjust variables like:

speed – controls how long each note plays

cycles – how many times the song repeats

velocity – how loud or soft each note is

Example:

play_twinkle(cycles=2, speed=0.6)


This repeats Twinkle Twinkle Little Star twice at a slower pace. Changing these values demonstrates how code can control rhythm, structure, and expression.

**Purpose and Learning**

The main aim of Code Songbook is to develop code literacy through experimentation. It’s less about perfect sound and more about understanding how digital logic creates structure.

The project connects directly to coursework materials such as:

The ARM1 Simulation (James et al., 2015) - understanding data flow and logic signals.

Sampling Sound Visualisation (101Computing, 2017) - seeing how digital systems translate sound into numbers.

By linking those concepts to TunePad, I learned how programming can act as a creative tool rather than just a technical skill.

**Current Project Status**
Code Songbook is complete and runs smoothly in TunePad. Each song plays correctly with clean timing and variable control. The code includes full comments, clear function design, and reusable components that demonstrate solid understanding of Python basics.

Future Improvements

If developed further, Code Songbook could:

- Include user input for tempo or scale selection

- Add visual feedback to show notes being played

- Introduce more complex melodies and harmonies

- Return to the original Mood 2 Music idea with machine learning once technical skills improve

References and Acknowledgements

This project was created for Working with Data & Code at the University of Technology Sydney.

**References**

Morrison, G., & Ahn, J. (2020). TunePad Documentation and Tutorials.

Roads, C. (1996). The Computer Music Tutorial. MIT Press.

Nierhaus, G. (2009). Algorithmic Composition: Paradigms of Automated Music Generation. Springer.

Kostka, Payne, & Almén. (2013). Tonal Harmony. McGraw-Hill.

James, Silverman, & Spittles. (2015). ARM1 Simulation. visual6502.org.

101Computing. (2017). Sampling Sound Visualisation. 101computing.net.

Acknowledgements
Special thanks to my tutor and classmates for feedback and guidance while testing each piece of code.
