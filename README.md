# Semantic CSS

## Intro
Semantic CSS is sets of principles which help you to build and maintain clean and easily understandable code for your app.

### Why Semantic CSS?
Because it always endup in huge mess. It's naive to think that you can design HTML/CSS in way that it will be perfect. What you actually have to do is prepare nice, clean and understandable HTML and isolate the mess into small chunks in CSS. Clean and understandable HTML is crucial because that's the point where Frontend developers (HTML/CSS) and Full Stack guys (JavaScript) meet.

Goal is to have as simple as possible HTML structure, where every element has cristal clear meaning without knowledge of specific visual styles or functional behavior. And just from reading HTML you should always now, where to find specific styles for that view or element.

Building app is long process from early prototypes to final tune app. And as app evolve so HTML and CSS. But the HTML should have been as stable as possible. All those changes should be mainly in CSS (if you change styles) or in Java Script (if you change behavior).

All those methodologies create big bloat of classes, which for new comers to project is hard to understand. Also it's very hard to refactor those code, because you small knowledge about which class and wrappers are needed. Goal of Semantic CSS is not allow you to quickly styled some view. The primary goal is to produce code, which will be easy to refactor later even with different person than you. Easy to style is secondary goal.

### What is Semantic CSS?
It's not about how it should look in the end, it's about principles you should follow during development. App is never finish so code is never finish too. The primary goal of this methodology is keep HTML/CSS easy to refactor. In the beginning you don't know how exactly will the app looks like and from which part in will be consist of in one year from now. The main thing you need to worry about is that when after one year some new Frontend guy come in, he will quickly understand basic principles and when he starts refactor he will not be scared change or remove stuff, which are no longer necessary, because he will now what's going on there.

### Basic principles

1) You don't know how the app will looks like in one year same as you don't have idea how the code will looks like. Let the best architecture emerge from bottom up approach, where continues refactoring play key role.

2) HTML/CSS will always end up in mess. Focus on having clean HTML structure with clear meaning. HTML is the place where Frontend and Full stack developers meet. It's like living with roommates. You can have a mess in your room, but if you want to live together happilly, share spaces like kitchen and bathroom needs to remain clean.

3) Isolate the mess into small CSS chunks. The code should be structured in way that frontend guys quickly know where to find the issue. Then is for him really easy to locate the actuall issue and fix it.  


## Custome elements as modules

* Use native elements inside costum elements, because they are generic.
* Module: `app-header`, submodule `app-header--logo`

## Classes as a state and modifiers
* using `is-` and `has-`
* 

## Project structure


## Local vs Global
* 

## Mixins for enheritence

## Variables
