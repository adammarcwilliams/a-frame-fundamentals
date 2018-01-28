## A-Frame Fundamentals

### Learning path and example projects for WebVR curriculum at Free Code Camp Manchester


1. [A-Frame School](https://aframe.io/aframe-school)

Start with A-Frames online course, completing the lessons on Glitch.

This is a gentle introduction to A-Frame's Entity Component System that requires no tooling or set-up to get started. 

Have fun experimenting with the basic scenes and be sure to get in the habit of referencing the docs when you get stuck configuring components rather than just looking at the solutions.

NB: When you're asked to add an animation component, use this script tag instead of the one in the A-Frame registery as v4 doesn't seem to work within the remixed Glitch: 

```
<script src="https://unpkg.com/aframe-animation-component@%5E3.2.x/dist/aframe-animation-component.min.js"></script>
```


2. [A-Frame Introduction](https://aframe.io/docs/0.7.0/introduction/)

After completing the school, read through A-Frame's introduction section on their website to re-enforce what you've learned and discover some of the different ways to set-up your own projects in a local developer environment.

All the challenge examples that I provide in this repo will be using the [**Envronment Boilerplate**](https://github.com/envronment/envronment-boilerplate)

> Envronment Boilerplate gives us a simple and modern way to create WebVR applications using [A-FRAME](https://aframe.io/), the Mozilla's web framework for building virtual reality experiences. The boilerplate uses [Babel](https://babeljs.io/) and [Webpack](https://webpack.js.org/) so you are able to write ES6 and make your code reusable.
