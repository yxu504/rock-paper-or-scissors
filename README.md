# rock-paper-or-scissors
codecademy JS 

<DOCTYPE html>
<html>
<head>  
<title> codecademy rockpaperscissors</title>
</head>
<body>
<script>

/*var userChoice = prompt("Do you choose rock, paper or scissors?");
var computerChoice = Math.random();
if (computerChoice < 0.34) {
	computerChoice = "rock";
} else if(computerChoice <= 0.67) {
	computerChoice = "paper";
} else {
	computerChoice = "scissors";
} console.log("Computer: " + computerChoice);*/

var userChoice = prompt("Do you choose rock, paper or scissors?");
var computerChoice = Math.random();
if (computerChoice < 0.34) {
computerChoice = "rock";
} else if(computerChoice <= 0.67) {
computerChoice = "paper";
} else {
computerChoice = "scissors";
} console.log("Computer: " + computerChoice);

var compare = function(userChoice, computerChoice) {
if(userChoice === computerChoice) {
return "The result is a tie!";
}
else if(userChoice === "paper"){
if (computerChoice === "rock"){
return "paper wins";
}
else {
return "scissors wins";
}
}
else if (userChoice === "scissors") {
if (computerChoice === "paper"){
return "scissors wins";
}
else {
return "rock wins";
}
}
};
</script>
</body>
</html>
