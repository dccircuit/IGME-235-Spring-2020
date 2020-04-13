# Project 3 - Web-based Game or Experience

***Except for the details about the rubrics at the end, this is updated for Spring 2020's asynchronous format***

## I. Overview
*Using PixiJS and/or the Browser DOM, create an Interactive Game or Rich Media "experience"*:

- For this project you (and, potentially, a partner) are creating a JavaScript-driven game or experience.
- You will be proposing an idea and describing it on a nicely formatted web page which will include the elements described below:
    - If you work with a partner, only one proposal web page between you will need to be created. 
- If you would like to see examples of previous projects, take a look back at the [Past Project exploration Exercise from Week 1](https://github.com/dccircuit/IGME-235-Fall-2019/blob/master/exercises/projects.md).

You will use **ONE** of these technology stacks:
- **JavaScript & PixiJS** (which wraps WebGL): 
    -  [About this PixiJS Tutorial Series](https://github.com/tonethar/IGME-235-Shared/blob/master/tutorial/pixi-js-0.md) has links to the [Circle Blast!](HW-circle-blast-1.md) exercise and other demos that can get you started **OR**
- **JavaScript & the Browser DOM** - these exercises will give you an idea of what is possible, and also represent some nice "starter" code:
    - [DOM Adventure!](https://github.com/tonethar/IGME-235-Shared/blob/master/tutorial/HW-adventure.md) is a tile-based game that uses arrow keys for movement, and simple sound.
    - [DOM Chibi Matching](https://github.com/tonethar/IGME-235-Shared/blob/master/tutorial/HW-chibi-matching.md) is a card matching game that uses CSS animations.
    - [DOM Life](https://github.com/tonethar/IGME-235-Shared/blob/master/tutorial/HW-life.md) is a tile-based game that explores simple [cellular automata](https://en.wikipedia.org/wiki/Cellular_automaton).
    - [Magentic Poetry](https://github.com/tonethar/IGME-235-Shared/blob/master/tutorial/HW-magnetic-poetry.md) uses CSS transforms and absolute positioning, and mousemove events.

- **IMPORTANT: YOU MAY NOT USE THE CANVAS 2D DRAWING API FOR THIS PROJECT - DOING SO WILL RESULT IN A GRADE OF ZERO**

- **IMPORTANT: THIS PROJECT NEEDS TO BE _YOUR WORK_:**
    - If you are using *Circle Blast!* or another game we gave you as a template, be sure to "change it up" and go well beyond what we gave you in the start code. Think about changing the game genre, control system, and how the opponents behave. We are only going to give you credit for the code you wrote, so if 90% of your submission is the same as one of our in-class exercises, you are going to get very little credit for the coding and functional sections of the rubric.
    - You must change the fonts, graphics, spritesheets, and sounds from what we gave you in the starting exercises. If you simply reuse what we gave you, points will be deducted in the design and interaction section of the rubric.
    - One reason for the above is that we want you to have a potential portfolio piece that you can show employers, and if your project just looks like the in-class exercises that everyone else is showing them, then you will likely not get the position.


## II. Goal
- Your goal is to use one of the tech stacks above to create an interactive media experience or game that is easy to use, functional, and aesthetically pleasing.

- Ideally the experience will run in all modern browsers, but at a bare minimum it must run in recent versions of Chrome.

- You will be evaluated on:
    - your creativity
    - the quality of the experience you create
    - the soundness of your programming in your chosen tech stack
        - don't miss the requirement to include an ES6 `class` somewhere in your project
    - how far you went beyond what we did in class, as described below

## III. Requirements

### A. Functional
- You will use one of the above tech stacks above as your underlying graphics engine
- Your game or app should do something useful, and be easy to use
- The functionality goes beyond what we have done in similar in-class examples
- There will be no JavaScript errors or exceptions thrown by the app

### B. Design & Interaction
- Pleasing graphic design
- Widgets are well labeled
- User should be able to figure out how to use the app with minimal instruction (and be sure to provide instruction and tooltips if necessary!), and user errors are handled gracefully
- While it doesn't need to be responsive, it should look good on a range of displays; don't design it just to work on your huge screen at home. If a 1024 x 768 display can't show the whole layout, it's a problem

### C. Media
- Images are properly optimized for web delivery - e.g. cropped and scaled to appropriate dimensions, and saved as a JPEG or PNG
- Sound is used to enhance the experience
- you have changed the fonts, graphics, spritesheets, and sounds from what was provided in the in-class examples

### D. HTML/CSS
- Reasonably Valid HTML5 - https://html5.validator.nu/
- Reasonably Valid CSS - https://jigsaw.w3.org/css-validator/
- Most CSS is in an external style sheet
- Use HTML5 semantic and structural elements where practical

### E. Code Conventions
- Utilize at least one ES6 `class` of your own creation
- `let` and `const` (no `var`!)
- `querySelector()` and `querySelectorAll()` for DOM traversal (DO NOT use the older methods)
- D.R.Y. - Don't Repeat Yourself. Repeated blocks of nearly identical code should be factored out and placed in a separate function.
- Separation of Concerns. Similar to how the *Circle Blast!* HW was structured, have a separate .js file for your classes, utility functions, and main code. If you have more than 3 CSS rules, then put them in an external stylesheet
- Variable and function names must begin with a lowercase letter
- Well-commented code. Each and every function gets a comment indicating what it does
- Delete or comment out your `console.log()` calls

## IV. Milestones
- Proposal: Post a simple web page anywhere in your banjo account that provides the information described above about what you plan to create for your game. - see myCourses dropbox for submission info & the due date
- Checkpoint: Create a working draft of the project. Post it to the #project-3-critiques channel in our Discord server - see myCourses dropbox for the due date
- Final project deliverable is due final exam week - see MyCourses dropbox for the due date and submission instructions. Be sure to post the project to the web, and put the link in the comments field of the myCourses dropbox. 
    - Part of the final deliverable includes a demonstration of your game.  You may do this in one of two ways:
        1. You may create a short video demo by recording your computer screen while using a tool such as OBS.  http://obsproject.com
 Submit this video by uploading it to YouTube as an unlisted video.  Ideally, you should explain your project with a voice-over, however if you do not wish to do that, you can upload your description as a separate file to the dropbox.
        1. You may schedule a Zoom or Discord chat with the professor on either May 4th or May 5th.

## V. Documentation
- Add your documentation to the same web page that you previously created for your proposal. Include your process for this project, cite any sources, tell me where to find anything special you want me to see, and also explain how you met the requirements
- If you worked in a pair, explain what each team member did. Remember, everyone is responsible for contributing throughout the project, not just to one aspect

## VI. Video Demonstration
During final exam week, you will present your project in a brief demo. Plan to show us:
- What you made.
- How it works.
- What's cool, and what you think is "above and beyond"
- How you overcame any serious challenges.
- Resources utilized (for libraries, tutorials, etc.), if you used any.

**You have two alternatives for how to deliver this demo as described above in the Milestones section.**

## VII. Grading
- *Both* partners must contribute equally to the project. This is NOT a project where team members are allowed to specialize into "Art Director" and "Software Developer" roles! Both team members shall be "Artist/Coders" (doing both) for this project.

### Your project grade will be split into two parts.
- 1/2 of your overall score will be assessed based on the video demo that you provide.
- 1/2 of your overall score will be assessed separately based on your required file submission.

Still working below this line:
-------------

#### The Rubric for the Presentation Day can be found in myCourses soon (if not already -- choose the new "Rubrics" menu item next to "Grades" and click on the "Preview" item in the pull-down next to the Project 3 rubric(s))

#### The Second Rubric is in development but will contain the following list of criteria:
- Additional HTML5 technology is present
- Includes at least one ES6 Class of your own creation
- Related HTML & CSS are reasonably valid
- Prevents and handles errors well
- Images are optimized.
- Proposal was updated on time.
- Prototype was available for critique.
- Documentation.

