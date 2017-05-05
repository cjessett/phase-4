## Friday

### Advanced Topics in JavaScript: `node`, `npm`, and ReactJS

### Core

- Demo
  - Show the app
  - Show your beautiful tests!
  - Show your beautiful `git log --graph` so we can see your mastery of git workflow

----

## Beginning Advanced Topics in JavaScript: `node`, `npm`, and ReactJS

## Goal

After this day, students will be able to:

* Build, from scratch, a Node-based environment for doing work with JavaScript in a shell context
  * Define "Node" and "NPM"
  * Verify installation of Node and NPM binaries (`node`, `yarn`)
  * Use Node's FileSystem API for manipulating the filesystem
  * Re-implement basic Unix utilities e.g. (`ls`, `cat`) in JavaScript
* Extend JavaScript code by utilizing packages provided by NPM
* Build, from scratch, a JavaScript-based unit test framework in which to
  run ES6-crafted unit tests so as to increase their familiarity with the
  language

## Importance

### Node and NPM

As mentioned in the overview, the expansion of JavaScript into the back-end
context has been one of the most interesting changes of JavaScript over the
last 10 years. More and more employers are looking for this skillset in itself.
So, it's good for interviewing.

Also, certain technologies e.g. Rails have come to recognize the maturity of
the `node` and `npm` ecosystem. As of Rails 5.1, Rails will delegate management
of JavaScript assets to `webpack`, a tool for JavaScript preparation provided
by `npm` and executed by `node`. This trend will likely continue. So learning
`node` and `npm` will set you up for "integration-style" changes such as these.

`npm` provides a rich system of packages, like Rubygems. As such you can
leverage the work of others in many situations. For example, the basic tool for
scaffolding React applications that we'll be using, `create-react-app`,  is
delivered as an `npm` module. The `npm` collection of packages recently became
the largest shared-code repository in the world. The ability to leverage this
asset will allow you to ship more-ambitious applications faster.

Lastly, `node` excels at certain types of application. The way it handles
multiple, persistent activites is every efficient and is called "non-blocking."
The same asynchronous behavior that makes working with AJAX calls tricky leaves
the computer millions of opportunities where it, instead of waiting idly for a
response, can toss work into a background queue and _do other work_. Building
applications that maintain many, long-term, frequently-idle connections is more
efficiently done with `node` as the back end. In similar comparisons to Python,
Ruby, or Java, `node` benchmarks as much as _3-times more efficient_! The
trade-off for that efficiency is applying the patterns of thought and
programming we learned from JavaScript in the browser, to the operating system.

Applications where `node` initially made big splashes was in creating chat
servers that worked with browsers. Given that a chat server would manage *many,
long-term, frequently-idle (web-)sockets*, it was a natural fit. Since `node`
grew up in the shadow of Rails, it wasn't long before it was used to build a
full-stack web server since, after all, a web server maintains *many,
long-term, frequently-idle (web request) sockets*.

At the highest level `node` runs JavaScript code to do things in the shell
environment. That's it. The `python` program runs Python code to do things in
the shell; the `ruby` program runs Ruby code to do things in the shell; the
`node` program runs JavaScript code to do things in the shell. Ruby leverages
gems from `rubygems`; Python leverages the `pip` system; `node` uses `npm`.
While Ruby used a `gem` command to work with packages, we'll use a command
called `yarn` for working with `npm`.

After this session you should be able to deliver basic command-line tools such
as seen in DBC's Ruby Phase 1.

### Conquering "The Black Screen"

Many new developers freeze up when they are presented with a big, empty
terminal window. "How do I get started?" is a common refrain. To set you up for
facing and conquering this fear we will drill setting up a basic environment by
starting from scratch multiple times. Being able to start an app from scratch
will provide you an immense sense of comfort. Please resist the desire to copy
/ repurpose old directories. Make sure your fingers know how to get going and
your fear of "The Black Screen" will dissolve.

### Utilizing ECMAScript 6 Features

More and more JavaScript being written is being written in ES6. Most React
examples are presented in ES6. Just as understanding Node and NPM is required
to understand the React development environment, understanding ES6 is required
to understand the idioms presented in React example code.

## Tasks

By being able to execute the following tasks, you will have learned the
material for the day and can corroborate your learning.

* Task 1: Use `node` to execute a file of JavaScript; to run a REPL
* Task 2: Configure a directory ready for using Node and NPM
* Task 3: Discover documentation in Node docs for working with filesystem
* Task 4: Build a simple Unix-based utility using Node + NPM and JavaScript
* Task 5: Extend a simple Unix application with an NPM-based package
* Task 6: Construct Node-driven test sandbox in which to run failing tests
* Task 7: Use ES6 to remediate failing unit tests and are introduced to several structures of ES6

## Lecture 1 (~ 60m) (mid-morning)

* **Q&A**
* Task 1: Use `node` to execute a file of JavaScript; to run a REPL
* Task 2: Configure a directory ready for using Node and NPM
* Task 3: Discover documentation in Node docs for working with filesystem
* Task 4: Build a simple Unix-based utility using Node + NPM and JavaScript
* Task 5: Extend a simple Unix application with an NPM-based package

## Lecture 2: Q&amp;A : Construct Node-driven test sandbox in which to run failing test (~30m)

* Task 6: Construct Node-driven test sandbox in which to run failing tests
* Task 7: Use ES6 to remediate failing unit tests and are introduced to several structures of ES6

**Challenges**

**Core**

* [Boustrophedon Challenge](../../../../boustrophedon-challenge)
* [NodeJS Sandbox and TDD Understanding of ES6](../../../../nodejs-sandbox-and-tdd-es6-model-challenge)

**Stretch**

Continue exploring the [ES6 and ES6 feature list][es6f] and build toy
applications to test your understanding. Developers do this **all the time**
when learning new technology. You now have the skills to run pretty much any
Phase 1 or Phase 2 challenge in the [NodeJS][] universe (although figuring out
an ORM to talk to Postgres might be a challenge, it's certainly possible!).

If you're looking to stay in the stretch zone you might consider:

* Implementing a Unix command in Node (e.g. `tree` or `ls -l`)
* Re-implement your Sudoku solution in Node. Perhaps display the board at the
  end of each "pass" where "given" numbers are colored one way,
  solved-last-pass numbers are colored another and square we're trying to solve
  is colored another. Ultimately inventing hurdles to provide you opportunity
  to create mastery is what will guarantee your career longevity in tech!

**Weekend**

We're almost to final projects. This is a weekend to make sure you're ready to
take on a serious programming assignment. Be sure to read the
[weekend](./weekend.md) guide. You want to know you can build a CRUD back end
with Ruby and Rails and that you can start a Node+NPM project. If you're solid
on those two topics, you're going to be ready for our final, intense week of
teaching.

**Next Week**

# THE NEXT TWO SESSIONS ARE VERY INTENSE: ARRIVE ON-TIME, WITH NOTEBOOK, READY TO GO

**Resources**

* [NodeJS][]
* [NodeJS Standard Library Docs][Node Stdlib]
* [NPM][]
* [ES6 Feature List][es6f]
* [React ES6-ES5 and React-Ruby](http://panw.weebly.com/programming/translation-for-react-es5-es6-and-if-react-was-in-ruby)

[NodeJS]: http://nodejs.org
[NPM]: https://www.npmjs.com
[Node Stdlib]: https://nodejs.org/dist/latest-v7.x/docs/api/
[es6f]: http://es6-features.org
[ECMAScript 6]: https://en.wikipedia.org/wiki/ECMAScript
