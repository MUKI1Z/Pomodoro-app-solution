# Frontend Mentor - Pomodoro app solution

This is a solution to the [Pomodoro app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/pomodoro-app-KBFnycJ6G). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

The Pomodoro Technique is a time management method that can be used for any task. For many people, time is an enemy. The anxiety triggered by “the ticking clock”, especially when it involves a deadline, leads to ineffective work and study habits which in turn lead to procrastination. The aim of the Pomodoro Technique is to use time as a valuable ally in accomplishing what one wants to do.


### The challenge

Users should be able to:

- Set a pomodoro timer and short & long break timers
- Customize how long each timer runs for
- See a circular progress bar that updates every minute and represents how far through their timer they are
- Customize the appearance of the app with the ability to set preferences for colors and fonts

### Screenshot
Below is the screenshot of the Pomodoro app 
![image](https://user-images.githubusercontent.com/106115551/185872126-0a6632c1-dc87-4746-83b4-2cb5e7eecab5.png)




### Links

- Solution URL: https://github.com/MUKI1Z/Pomodoro-app-solution.git
- Live Site URL: (https://muki1z.github.io/Pomodoro-app-solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Javascript with (js Libraries)


### What I learned

How to use JQueries, JQuery Event Handlers, etc



```html
    <title>Pomodoro-app</title>
  
```
body {
  color: hsl(226, 100%, 92%);
  background-color: hsl(236, 36%, 18%);
  margin: 0;
  padding: 0;
}

```
```js
$("#jq-pomodoro-up").click(function(){
    settingsMarshall.tPomodoro += 1;
    $("#jq-pomodoro-minutes").text(settingsMarshall.tPomodoro);
})

```



### Continued development

I would also use SASS instead of the normal CSS, for a more organized approach to the styling.


### Useful resources

-Frontend Mentor : For giving me the idea that guided me through the project.
-Freecodecamp : Aided me through some revisions on JQuery Event 

## Author

- MOHAMMED MUKAILA
FACEBOOK PAGE: mohammed.mukaila11



## Acknowledgments

- Freecodecamp.org
- Some youtube videos
- Frontend Mentor




