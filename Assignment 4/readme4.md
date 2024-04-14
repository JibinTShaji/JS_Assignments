## Q1) Write a chained if / else if statement to fill in the following conditions
## val <5 => tiny
## val<10 => small
## val<15 => medium
## val<20 => large
## val>=20 => huge

## Ans: let val=prompt("Enter a value")
## if(val<5){
##   console.log("Tiny")
## }
## else if(val<10){
##        console.log("Small")
## }
## else if(val<15){
##        console.log("Medium")
## }
## else if(val<20){
##        console.log("Large")
## }
## else if(val>=20){
##        console.log("Huge")
## }
##
## Q2) Use the switch case and create an application with the following roles.
## admin => gets full access
## subAdmin => gets access to create and delete courses
## testPrep => gets access to create and delete tests
## user => gets access to consume contents

## Ans: let a=prompt("Choose any numbers: 1.Admin 2.SubAdmin 3.testPrep 4.user")
## switch(a){
##     case "1":
##         alert("gets full access")
##         break
##     case "2":
##         alert("gets access to create and delete courses")
##         break
##     case "3":
##        alert("gets access to create and delete tests")
##         break
##     case "4":
##         alert("gets access to consume contents")
##         break
##     default:
##         alert("invalid input")
## }
    