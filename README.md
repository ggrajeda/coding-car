# Coding Car

## Table of Contents
 * [Description](#description)
 * [Usage](#table-of-contents)
 * [Discussion](#discussion)
    * [Pros](#pros)
    * [Cons](#cons)
 * [Link](#link)

## Description
I created the Coding Car project in summer 2016, when I was a rising junior in high school. The point of the project is to introduce kids to coding in a more entertaining way. When the project was up and running, students would visit [this website](https://ggrajeda.github.io/coding-car/) (looks best on Chrome) and learn to program a remote-controlled car at three different levels: **Play**, **Learn**, and **Get Coding!**. Note that I uploaded the project in 2020, years after the project ended, and so the buttons on the website do not do anything anymore. Finally, I could not find the code for the Particle Photon microcontroller on the car, so the only piece of the project that remains is the website.

## Usage
In _Play_, kids would press buttons to control the car. The buttons are labelled in pure English (no programming syntax yet), with each button belonging to a group of car controls (e.g. Direction, Headlights). It's important to note that you don't control the car with a joystick, but with buttons. The point of the _Play_ section is not just for students to play around with the controls as they would with a normal remote-controlled toy car, but for them to develop an intuition for subdividing routines. For example, to make a full loop around an oval track, you need to go forwards for a while, turn left for a bit, go forwards again for a while, and then turn left once more. While this seems obvious, we found that kids benefitted from learning to break larger tasks (like completing a lap around a track) into smaller subroutines.

In _Learn_, kids familiarized themselves with coding syntax. There are a set of parentheses and a semicolon after every command. Moreover, the _Learn_ section builds upon the _Play_ section. Whereas buttons may have been organized into groups before, commands are now listed together. Students are supposed to have built an intuition about which commands are useful in a subroutine and which are not.

In _Get Coding!_, kids write full-length programs to control their car. Note that the leap from _Learn_ to _Get Coding!_ is larger than that from _Play_ to _Learn_. Students must now plan out a program with the syntax introduced in the previous section. While _Play_ and _Learn_ offer students real-time interaction with the car, the _Get Coding!_ section only allows students to pass in one block of code at a time. To get the car to make laps around a track, students must invest time in planning out the course, performing trial runs, and editing their program. To allow for easier coding, a `wait(double ms)` function is introduced, to keep the car in a certain state (e.g. driving straight, turning, or beeping) for a certain number of milliseconds.

## Discussion
### Pros
I think the main draw of this project is that it can help young students learn to code&mdash;especially students who may initially seem disinterested in programming. One of the central issues in trying to promote computer science education to youth is that kids can find programming boring, especially when the subject is taught through the wrong lens. I have found, unsurprisingly, that coding becomes fun when it is presented to children as a game or a puzzle.

I am proud of the project's aesthetic. The color scheme is interesting, and the font is kid-friendly and easy on the eyes.

### Cons
This was my first attempt at coding in HTML, CSS, and Javascript. It was a lot to learn over a single summer, and so there were some things that I would have liked to develop more. The first is a way to provide feedback when the user has errors in their code. Watching the car stop moving halfway through a routine because you forgot a semicolon is not a fun experience. The second is that I would like to have developed a nicer text editor in the _Get Coding!_ section. Maybe the color of the text could change green for function names, white for parentheses and semicolons, and red for unrecognized terms.

Because I was learning HTML, CSS, and Javascript all at once, I sacrificed code design for code functionality. In other words, I wanted to get working code&mdash;not beautiful code. This means that the source code is quite messy, which I regret, as it is difficult to edit the project many years later. But perhaps this messiness can be excused by the fact that I hadn't yet taken any formal computer science classes at the time.

Finally, the website only worked with my personal car. If I had made more cars, I could have assigned each one a key to be passed in before entering the website.

## Link
[https://ggrajeda.github.io/coding-car/](https://ggrajeda.github.io/coding-car/)
