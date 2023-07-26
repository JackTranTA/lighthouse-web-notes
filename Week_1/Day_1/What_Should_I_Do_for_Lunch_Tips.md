### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === false) {
    console.log("I will skip lunch today.");
  } else if (availableTime < 20) {
    console.log("I should grab a snack or a ready to eat meal.");
  } else if (20 < availableTime && availableTime < 30) {
    console.log("I should cook something healthy.");
  } else if (availableTime > 30) {
    console.log("I might not want to spend so much time during this busy schedule on cooking.");
  }
};
```