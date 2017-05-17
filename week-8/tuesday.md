## Tuesday

### React as a JavaScript MVC Framework

## Goal

After this day, students will be able to:

* Process a mock-up into a `React.Component`--based JavaScript Site
  * Process a mock-up into a static page
  * Process a static page into a a collection of `React.Component`s
  * Explicitly "pull-up" state to share data between Components
  * Explicitly pass event handling logic up a nested-`React.Component` hierarchy

## Importance

As we saw in yesterday, our Widget architecture is not "enforced." It's a
practice that leads to scalable UIs, but there's little error checking to
ensure people follow that architecture. Facebook has built a framework that
enshrines the Widget approaches of Day 2 and adds some nice features that
reduces the amount of typing.

As we swap our the DBC "Pre-React" (Preact? Tee-hee) methodology for full
React, we'll continue to experience that we've seen the problems React solves
and now we're just changing our syntax.

We'll also take advantage of the Node + NPM ecosystem to get a React skeleton
up and running quickly (Day 1). We'll be writing the React code in ES6 (Day 1).
We're pulling together the first three days to make writing React as simple as
possible.

## Tasks

By being able to execute the following tasks, you will have learned the
material for the day and can corroborate your learning.

Task 1: Install and use a global NPM package: `create-react-app`
Task 2: Name steps in mockup, static, `React.Component` design strategy
Task 3: Identify atomic `React.Component`(s) from a mockup and create
Task 4: Establish centralized, unidirectional data flow for communication between `React.Component` thus "composing" them
Task 5: Articulate virtues of React based on experience
Task 6: Use Lifecycle Methods to Retrieve Data
Task 7: Build a React Component around a Form
Task 8: Iterate through a collection in JSX


## Lecture I: Implementing Widget-based Architectures with React

* Task 1: Install and use a global NPM package: `create-react-app`
* Task 2: Name steps in mockup, static, `React.Component` design strategy
* Task 3: Identify atomic `React.Component`(s) from a mockup and create
* Task 4: Establish centralized, unidirectional data flow for communication between `React.Component` thus "composing" them
* Task 5: Articulate virtues of React based on experience

## Lecture II: Topics in React

* Task 6: Use Lifecycle Methods to Retrieve Data
* Task 7: Build a React Component around a Form
* Task 8: Iterate through a collection in JSX

**Challenges**

**Resources**

* [Component Creation Guidelines](../resources/component_creation_process.html)

**Core**

* [Translator Widget in React](../../../../number-base-converter-react-challenge)
* [Lil' Twitter](../../../../lil-twitter-react-challenge)

**Note**

Lil Twitter is an extremely difficult challenge. It brings together React,
Rails, CRUD, ActiveRecord &mdash; everything! You might expect as much from a
challenge that's coming at the end of your DBC experience.

Remember to follow the mockup, static, Component process. Proceed by making
small changes and verifying things work. Don't think that you can "see it all"
in the code. Very small errors in a big pile feel impossible while small errors
found singly feel like minor bumps in the road.

You should not expect to finish LilTwitter in one afternoon. Its work will
extend over into tomorrow. In Day 4 we'll do a live-code of the "Timeline" in
lil Twitter. Give it your best effort and we'll share what we've learned
tomorrow.

**Feedback**

Please complete this feedback before end of day so that we may tune our
delivery for tomorrow.

https://goo.gl/forms/ZZihuELidYT9lQL32
