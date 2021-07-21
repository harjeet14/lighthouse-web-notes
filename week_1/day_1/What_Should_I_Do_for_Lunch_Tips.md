### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```const whatToDoForLunch = function(hungry, availableTime) {
if (!hungry) {
    console.log("Get back to work");
  }else {
    if (availableTime < 20) {
      console.log("You pick up a snack.");
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("You deserve a break and should take time to cook a tasty meal.");
    } else {
      console.log("We're in a bootcamp.");
    }
  }
};
```
