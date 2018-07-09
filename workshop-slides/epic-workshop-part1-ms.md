footer: ©Carol Willing, 2018.
slidenumbers: true
build-lists: true
theme: Next, 2


# Interactivity
## in Computer Science

### EPIC Middle School Workshop
### July 2018

---

# :wave: Hi :wave:

## I'm Carol

---

# Why Computer Science?

- Applications for people
- Life skill
- Empowering

---

# Why Interactive?

- Creative
- Expressive
- Fun

---

# Programming Languages

## JavaScript

:snake:

## Python
---

# My Goals for this workshop

* Hands-on
* Explore JavaScript and Python
* Inspire to do more
* Share

---

# What do we need today?

* Computer (or Smartphone or Tablet)
* Browser (Chrome)
* Web
* **You**

---

# :alarm_clock: Schedule :alarm_clock:

| Time      | Project    |
|-----------|-------------|
| *1:10 pm* | People      |
| *1:20 pm* | Careers     |
| *1:30 pm* | Design at Google |
| *1:45pm*  | p5.js       |
| *2:30 pm* | Jupyter and mybinder.org |
| *2:45 pm* | Next steps  |

^ Time for interest
Less work or more work
bump to 15 minutes

---

## Project 1

# :smile: People & Teams :smile: 

^ Pacing: 1:10 pm

---

# Who uses computer science?

![](images/luz.png)
![](images/diygirls.png)
![](images/uber-jesus.png)

^ add a table with photos of all

---

### Task
## Choose someone who you would:

- want on your team
- like to meet
- like to ask a question

---

# Luz Rivas

## [California 39th District, Assembly](https://www.luzforassembly.com/)
## [DIY Girls, Founder](https://www.diygirls.org/founder/)

![right, fit](images/luz.png)

![left, inline](images/diygirls.png)

---

# Jesus Medrano

![right, fit](images/uber-jesus.png)

## [Uber Eats, Software Engineer](https://eng.uber.com/android-eats/)

---

# Omoju Miller

## GitHub, Data Scientist

[About Omoju](http://omojumiller.com/about/)

[“On learning AI: The myth of innate ability in tech.”](https://youtu.be/BFWVHSeakkg?t=7s)

![left, fit](https://youtu.be/BFWVHSeakkg?t=7s)

---

# Limor Fried
# Ladyada

## [Adafruit](https://learn.adafruit.com), Founder and CEO
## Electrical Engineer

![right, fit](https://youtu.be/V4WtPv0yWek)

---

# Ana Ruvalcaba

![right, fit](images/ana.jpg)

## [Project Jupyter](https://jupyter.org), Operations Manager

---

# Bryan Liles

![right, fit](images/bryan.png)

## Heptio, Engineer

[Cognitive Bias Talk](https://www.youtube.com/watch?v=fYCoEsc4aaE)

[GitHub - Bryan Liles](https://github.com/bryanl)

---

# You

![right, fit](images/you.jpg)

---

## Project 1

# People & teams

- Teamwork is important
- Find a role model
- Ask questions

## :tada: Completed :tada:

---

## Project 2

# Computer Science Careers

## :school: :construction: :airplane: :office:

^ Pacing: 1:20 pm

---

Coding is one of many CS careers.

---

# If you like ... here's a job for you.

Here's a job for you.


---

### Task
## What interests you?

Circle any careers that interest you.

![right](https://youtu.be/lHC10q_a7Nc)

---

## Project 2

# Computer Science careers

- Find your interests
- Learn which career you may like
- Understand many careers in CS beyond coding  

## :smile: Completed :smile:
---

## Project 3

# Design at Google

## :video_game: :musical_score: :musical_keyboard: :art:

^ Pacing: 1:30 pm

---

# Google Doodles

![inline](images/google-doodle.png)

See the [Google Doodles](https://www.google.com/doodles) page.

---

# Step 1: Try the Doodles

[Fischinger doodle](https://www.google.com/doodles/oskar-fischingers-117th-birthday)

[Hip Hop](https://www.google.com/doodles/44th-anniversary-of-the-birth-of-hip-hop)

[Snake Game](https://www.google.com/search?q=snake+game)

![inline, left](images/fischinger.png) ![inline, center](images/hiphop.png) ![inline, left](images/snakegame.png)

---

# Step 2: Design/UX Review

**Choose a Google Doodle.**
- What things were *interactive*?
- How did it *start*?
- How did it *end*?
- What do you *like* best?
- What would you *change*?


:bulb: **UX** = **U**ser E**x**perience :bulb:

---

# Step 3: Sketch a new doodle

- Sketch
- What would be interactive?
- Theme/Subject of doodle
- Share with someone

![right](images/hiphop-sketch.png) 

---

# Extra: Inspect the doodles

Explore doodle web page with Chrome Developer tools.

- Menu: View -> Developer -> View source
- Menu: View -> Developer -> JavaScript Console
- Menu: View -> Developer -> Developer tools

[Google Web documentation](https://developers.google.com/web/)

[:eyes: JavaScript documentation from Mozilla :eyes:](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## Project 3

# Design at Google

Skills used:
- Product research
- User Interface and UX
- Computer Human Interactions

## :art: Completed :art:

---

## Project 4

#  Get started with JavaScript

---

# p5.js

## [https://p5js.org/](https://p5js.org)

![](images/p5-js-home.png) 

---

# Learn about p5.js

### [https://hello.p5js.org/](https://hello.p5js.org/)

---

# Explore

### [Reference](https://p5js.org/reference/) | [Referencia](https://p5js.org/es/reference/)

![right, fit](images/referencia.png)

---

# Try the editor

### [https://alpha.editor.p5js.org/](https://alpha.editor.p5js.org/)

---

![fit](images/editor.png)

---

![fit](images/editor-examples.png)

---

![fit](images/wavemaker.png)

---

# Interact

### Move mouse over image
### Change | Run | Change | Run

---

## Project 4

#  Get started with JavaScript

- Use a new language
- Help with Reference
- Try the editor
- Run an example

## :sparkles: Completed :sparkles:

---

## Project 5

# Drawing

---

```javascript
function setup() {
  // put setup code here
}

function draw() {
  // put drawing code here
}
```

---

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0>
    <style> body {padding: 0; margin: 0;} </style>
    <script src="../p5.min.js"></script>
    <script src="../addons/p5.dom.min.js"></script>
    <script src="../addons/p5.sound.min.js"></script>
    <script src="sketch.js"></script>
  </head>
  <body>
  </body>
</html>
```

---

### Draw an ellipse on the screen

```javascript
ellipse(pixelsFromLeft, pixelsFromTop, width, height)
```

ellipse( :arrow_right: , :arrow_down: , )             
pixelsFromLeft | ---> |
pixelsFromTop | : )

**Example**

```javascript
ellipse(50, 50, 80, 80);
```

---

```javascript
function setup() {
  // put setup code here
}

function draw() {
  // put drawing code here
}
```

---

ellipse(50, 50, 80, 80);

---

## Project 6: Movement

---

## Project 7: Interactivity

---

## EXTRA - Styling for the web

Codepen

---

# More real world

---


## Python


https://python.org

---

## Jupyter and Binder

https://jupyter.org

https://try.jupyter.org

https://mybinder.org

----

# What's next?

----

## Research new applications

---

### AI and Machine Learning Examples

https://experiments.withgoogle.com/ai/ai-duet/view/

https://experiments.withgoogle.com/ai/sound-maker/view/

---

## High school classes

---

## Tutorials

http://hello.p5js.org/

---

# What we did

---

## Accomplishments

---

# Thank you

---
