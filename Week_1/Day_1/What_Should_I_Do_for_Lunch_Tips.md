### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.


```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log("Still not hungry. Let's keep working.");
  } else if (hungry === true) {
    if (availableTime < 20) {
      console.log("Pick something up and eat it in the Lab/kitchen. Broaden your horizons, chat with your classmates.");
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("Look at you go. Take a break you go getter, you deserve it. Why not try something in Gastown.");
    } else if (availableTime > 30) {
      console.log("Wow!! Give your self a break. Go grab a bite to eat. Just remember you are still in bootcamp, and should probably reconsider taking a break over 30 minutes.");
    }
  }
};