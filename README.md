# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Your challenge is to build out this order summary card component and get it looking as close to the design as possible.
You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

### Screenshot

![image](https://github.com/Cjmoye30/Frontend-Mentor-Projects/issues/1#issue-1005726127)

### Links

- Live Site URL: [Add live site URL here](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox (Bootstrap v5.1)

### What I learned

What took me the longest time was trying to figure out how to get the items within the "selectedPlan" vertically aligned.
I was finally able to find what I was looking for on Bootstrap, and that was the biggest hurdle I had to get over.

```html
<div class="card selectedPlan">

  <div class="row align-items-center">
    <div class="col">
      <img class="icon-music" src="images/icon-music.svg" alt="">
    </div>

    <div class="col-6 plan-info">
      <h5>Annual Plan</h5>
      <p>$59.99/>year</p>
    </div>

    <div class="col">
      <a class="change-link" href="#">Change</a>
    </div>

  </div>
</div>
```

### Continued development

I want to continue working through and completing all of the Frontend Mentor Newbie projects, and submit them for review.
Coding has always been something on the back of my mind, and I am wanting to take some solid steps towards this career path to see where it leads.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Udemy - The Complete 2021 Web Development Bootcamp - Dr. Angela Yu](https://www.udemy.com/course/the-complete-web-development-bootcamp/?src=sac&kw=)
- Website - [Skillshare - Responsive Web Design Essentials - HTML5 CSS3 Bootstrap - Daniel Scott](https://www.skillshare.com/classes/Responsive-Web-Design-Essentials-HTML5-CSS3-Bootstrap/236553264/projects)

## Acknowledgments
