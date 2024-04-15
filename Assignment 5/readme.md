## 1) Write short notes on string methods with code examples
### * toLowerCase()
### * toUpperCase()
### * substring()
### * replace()
### * trim()
### * split()
### * slice()

## Ans:  toLowerCase() method is used to Convert uppercase to lowercase.
## toUpperCase() is used to convert lowercase to uppercase
## let text1="Hello World"
## let text2=text1.toLowerCase()
## let text3=text1.toUpperCase()
##
## subString() method extract characters, between two positions from a string and return the substring.
## let arr="apple,orange,kiwi"
## let arr2=arr.subString(7,13)
##
## replace() method replaces a specified value with another value in a string. 
## let text="hello world"
## let newText=text.replace("hello","welcome to")
##
## trim() method removes whitespaces from both sides of a string.
## let text1="   hello  "
## let text2=text1.trim()
##
##  A string can be converted to an array with the split() method.
## text.split(",")
##
## slice() extreact a part of astring and returns the extracted part in a new string.
 ## let text="red, blue , black";
## let sliced=text.slice(5,9)
##
##
## 2) create a simple app that takes the user’s name and greets him/her after capitalizing the first letter of the user’s name and changing the rest of the letters into lowercase (toUpperCase(), toLowerCase(), slice(), length property, string concatenation)
## Ans:let name = prompt("Enter Name")
## let fistletter=name.slice(0,1)
## let uppercased=fistletter.toUpperCase()
## let balanceletters=name.slice(1,name.length)
## let lowercased=balanceletters.toLowerCase()
## let addedName=uppercased+lowercased

## console.log(addedName)