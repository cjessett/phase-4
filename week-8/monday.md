## Monday: Writing Complex JavaScript Front-Ends in ES6; "The Why of React"

## Goal

After this day, students will be able to:

* Process a mock-up into a Widget-based JavaScript Site
  * Process a mock-up into a static page
  * Process a static page into a a collection of JavaScript classes ("Widgets")
  * Explicitly "pull-up" state to share data between Widgets
  * Explicitly pass event handling logic up a nested-Widget hierarchy

## Importance

When beginning to program, code content is small, thus how the code is
organized makes very little difference. Prompting the user for a name and then
printing "Hello" to that name on screen is sufficiently simple that _how_ we
write the code won't greatly impair its readability or maintainability.

However, as code grows more complex, we learn to section work into procedures
or functions and then collect functions, now called methods, and state into
classes. This is how Object-Orientation (classes and their instances
interacting) evolves naturally from Procedural programming (run this function,
then this one, then update this, then do that).

As we noted in Day 1, early JavaScript uses in the DOM were largely eye-candy
or validation. They did not require systems of organization or disciplined
practices in order to stay readable and maintainable.  However with front-end
JavaScript programs having become increasingly complex (GMail, the Facebook
"wall", etc.) new practices are needed to help the programmer *both* organize
and produce the code needed to meet the complexity of the requested feature.

Today we will introduce you to a series of problems that you will tackle using
plain JavaScript (ES6 permitted!) and your Node + NPM environments. Having
learned to _see_ the problems and having coded solutions by hand in native
JavaScript, you will be amused and / or thankful that React saves you some
typing or provides some consistent practice &mdash; _but the framework's
purpose and goals will have already been understood_ and coded by you! Our
goal, then, is to discover for ourselves "**The Why of React**."

By doing so, you'll be able to speak about React and its design, consider what
*all* JavaScript frameworks (Angular, Ember, Elm) have as core problems to
solve, and sleep confidently knowing you have a profound depth of understanding
of React's design decisions. You won't be "in the restaurant" in terms of
React, you'll be "in the kitchen" around _all_ JavaScript MVC frameworks.

Amazingly enough, many of these concepts event port to iOS development as well
where you literally drag screen elements ("Widgets") onto a canvas and then
wire up the events to a central controller. So, by absorbing this module,
you'll be ready to appreciate how both React and iOS approach building complex
interfaces.

It's an intense day chocked-full of value.

## Tasks

By being able to execute the following tasks, you will have learned the
material for the day and can corroborate your learning.

* Task 1: Name steps in mockup, static, widget design strategy
* Task 2: Identify atomic widget(s) from a mockup and create
* Task 3: Establish centralized, unidirectional data flow for communication between Widgets thus "composing" them

## Morning Breakout

* **Q&A on Video Content:**
  * Task 1: Name steps in mockup, static, widget design strategy
  * Task 2: Identify atomic widget(s) from a mockup and create

## Afternoon Breakout

* Gemsy Talks
* Task 3: Establish centralized, unidirectional data flow for communication between Widgets thus "composing" them

**Challenges**

**Resource**

* [Handout: Creating Widgets](../resources/widget_creation_process.html)

**Core**

* [Translator Widget](../../../../number-translator-widget-challenge)
* [Translator Widget with Shared State ](../../../../number-translator-widget-shared-state-challenge)

# THE NEXT SESSION IS VERY INTENSE: ARRIVE ON-TIME, WITH NOTEBOOK, READY TO GO

**Prepare for Tomorrow**

- **React**
  - Read [Thinking in React](https://facebook.github.io/react/docs/thinking-in-react.html)
  - Read React intro [blog](https://blog.risingstack.com/the-react-way-getting-started-tutorial/)
  - Watch [intro to JSX](https://frontendmasters.com/courses/react-intro/#v=mc66igcb45)
