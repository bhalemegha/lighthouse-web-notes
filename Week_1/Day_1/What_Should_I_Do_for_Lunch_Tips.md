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
