```
const whatToDoForLunch = function(hungry, availableTime) {
  if(hungry === false) {
    console.log("Go back to work");
  } else if ((hungry === true) && (availableTime < 20)) {
    console.log("Order door dash and eat quick!");
  } else if ((hungry === true) && (availableTime >= 20) && (availableTime <=30)) {
    console.log("You got time to go out and eat!")
  } else {
    console.log("take a 10 minute walk and get back to bootcamp!") 
  } 
}




console.log("I'm hungry and I have 20 minutes for lunch.");
whatToDoForLunch(true, 20);
console.log("---");

console.log("I'm hungry and I have 50 minutes for lunch.");
whatToDoForLunch(true, 50);
console.log("---");

console.log("I'm not hungry and I have 30 minutes for lunch.");
whatToDoForLunch(false, 30);
console.log("---");

console.log("I'm hungry and I have 15 minutes for lunch.");
whatToDoForLunch(true, 15);
```
