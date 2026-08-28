# Tic-Tac-Toe: My React Learning Journey Edition

> *Learning React one component, state change, and bug at a time.*

This is my journey into learning **React** by actually building something from scratch. Instead of only reading about concepts, I am following the React Tic-Tac-Toe tutorial (https://react.dev/learn/tutorial-tic-tac-toe) to understand what was happening behind the code.

By the course end of building this project, I opt to create a simple button that displayed an **X** to building a complete Tic-Tac-Toe game with:

* Interactive squares
* Turn-based gameplay
* Winner detection
* Game history
* The ability to jump back to previous moves
* A better understanding of how React components and state work together

This README documents my **6 day journey** including the concepts I will be learning. The challenges I will face and the moments where React finally makes sense will be documented.

-----

# What I Learnt

The aim is to build this game step by step, learn how React works by breaking an interface into small pieces and managing how data changes between them.

Some of the main concepts i will archeive:

* Components
* JSX
* Props
* State
* `useState`
* Event handling
* Conditional rendering
* Lifting state up
* Immutability
* Rendering lists with `.map()`
* React keys
* Derived state
* Component communication

---

# Journey Timeline

## Day 1 — First React Component

### Aim

Understand the basics of React components, JSX, and props.

### What I Built

I started with a very simple component called `Square`.

At first, it was just a button that displayed an **X** on the screen.

Something as simple as this:

```jsx
function Square() {
  return <button className="square">X</button>;
}
```

It introduced me to one of the most important ideas in React:

> **The user interface can be built from reusable components.**

### What I Learned

* What a React component is
* How JSX works
* How React combines JavaScript and HTML-like syntax
* Why components are useful
* How `className` is used instead of `class`

### My First "Aha!" Moment 

Seeing something that looked like HTML inside JavaScript was confusing.

Then it started to make sense:

> *" JSX allows me to describe what my UI should look like directly inside my component."*

My first intro to thinking the React way.

---

## Day 2 - Making the game interactive

coming soon :)

---


# Project Structure

```text
tic-tac-toe/
│
├── src/
│   ├── App.js
│   │   └── Main game logic
│   │
│   ├── styles.css
│   │   └── Game styling
│   │
│   └── index.js
│       └── Application entry point
│
├── public/
│   └── index.html
│       └── HTML template
│
└── package.json
    └── Project dependencies
```

---

# Running the Project

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

# Move into the project
cd YOUR_REPOSITORY

# Install dependencies
npm install

# Start the development server
npm start
```

The application should then run locally in your browser.

---

# 📚 Resources That Helped Me Learn

The main resource I used was the official React documentation and tutorial.

* React Tic-Tac-Toe Tutorial
* React documentation
* React guides on components and state
* React guide on sharing state between components

The biggest lesson I learned from following the documentation was that I should not just copy the code.

I needed to stop and ask:

* What does this line do?
* Why is the state stored here?
* Why are we creating a copy of the array?
* What happens if I change this?
* Can I explain this code without looking at the tutorial?

That approach helped me learn much more than simply completing the project.

---

# What I Want to Build Next

What I would like to explore next woulld be:

* Add an AI opponent
* Build a multiplayer version
* Add animations and transitions
* Improve the design
* Add a score system
* Create more React projects

---

# Note To Self


### 1. Don't Rush

Understanding one concept properly is better than quickly finishing a tutorial without knowing what happened.

### 2. Type the Code Yourself

Writing code yourself helps you notice patterns.

### 3. Break Things

Understanding something is to change it and see what happens.

### 4. Read the Errors

Many of them tell you exactly where the problem is.PLZ READ ~_~

### 5. Refactor When You Understand More

Your first solution does not have to be your final solution.
As you learn more, your code can improve too.

---

## About Me

I am in my learning web development phase and exploring modern technologies by building projects.

This Tic-Tac-Toe game is one of my first serious React projects, and I created this README to document not just the final result, but the learning process behind it.

I hope that when I look back at this project in the future, I'll be able to see how far I've come :)


---

**Built with React, curiosity, persistence, and probably too much coffee**

> *"The best way to learn is to build. The best way to understand is to keep asking why."*
