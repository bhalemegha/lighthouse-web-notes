# [Megha]'s Notes
# H1 header (largest)
###### used in H6 header (smallest)

## Summary 

This repository contains all of the notes taken by [Megha](https://github.com/bhalemegha/lighthouse-web-notes.git) for the [Lighthouse Labs](https://www.lighthouselabs.ca/).

* [Week 1](/Week_1)  
  *[Day 1](/Week_1/Day_1)


```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry && (availableTime < 20)) {
    console.log("I'm hungry and I have " + availableTime + " minutes for lunch.\nI don't know what to do!");
  } else if (hungry && (availableTime >= 20 && availableTime <= 30)) {
    console.log("I'm hungry and I have " + availableTime + " minutes for lunch.\nI don't know what to do!");
  } else if (hungry && availableTime > 30) {
    console.log("I'm hungry and I have " + availableTime + " minutes for lunch.\nI don't know what to do!");
  } else {
    console.log("I'm not hungry and I have " + availableTime + " minutes for lunch.\n I don't know what to do!");
  }
};


whatToDoForLunch(true, 20);
whatToDoForLunch(true, 50);
whatToDoForLunch(false, 30);
whatToDoForLunch(true, 15);
```