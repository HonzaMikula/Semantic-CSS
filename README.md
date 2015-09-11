# Semantic-CSS
Semantic CSS methodology

## Intro
Semantic CSS is sets of principles which help you to build and maintain clean and easily understandable code for your app.

### Why don't use OOCSS, SMACSS, SUITCSS or Atomic CSS?
Because it always endup in huge mess. It's naive to think that you can design HTML/CSS that will be perfect. What you actually have to do is prepare nice, clean and understandable HTML and isolate the mess into small chunks in CSS. Clean and understandable HTML is crucial because that's the point where Frontend developers (HTML/CSS) and Full Stack guys (JavaScript) meet.

Goal is to have simple as possible HTML structure, where every element has cristal clear meaning without knowledge of specific visual styles or functional behavior. Building app is long process from early prototypes to final tune app. And as app evolve so HTML and CSS. But the HTML should have been as stable as possible. All those changes should be mainly in CSS (if you change styles) or in Java Script (if you change behavior).

All those methodologies create big bloat of classes, which for new comers to project is hard to understand. The 

## Costume elements as modules

* Use native elements inside costum elements, because they are generic.
* Module: `app-header`, submodule `app-header--logo`

## Classes as a state and modifiers
* using `is-` and `has-`
* 

## Local vs Global
* 

## Mixins for enheritence

## Variables
