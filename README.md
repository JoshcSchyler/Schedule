//# Schedule# J.S.C 2-4 week endeavor day 3 -4 5 567891012ODD141516-----90000---//
var myName="Josh Claros";
let camper ="Josh";
//variables under let will only be used once unlike var
let catName= "Oliver";
let catSound= "Meow!";
yup commit here
/*An error will be displayed when there is an attempt to change the const variable*/
const Fav_PET = "Cats"; 
FAV_PET +"Dogs";
/*Declare a Read-Only Variable with the const Keyword; You should always name variables you don't want to reassign using the const keyword. Especially when attempting to reassign a variable that is meant to stay constant*/
//Note: It is common for developers to use uppercase variable identifiers for immutable values and lowercase or camelCase for mutable values (objects and arrays). 
const FCC = "freeCodeCamp"; // Change this line, FCC was fCC, const was var
let fact = "is cool!"; // Change this line, let was var 
fact = "is awesome!";
console.log(FCC, fact); // Change this line, FCC was fCC ( of course due to const retaining immutable values 14mins)

/*Add Two Numbers with JavaScript; Number is a data type in JavaScript which represents numeric data.Use the + symbol as an addition operator (assingment operator presumably?) when placed between two num*/
const myVar = 5+10; 
//myVar now has the value 15.
/*Subtract One Number from Another with JavaScript*/ 
const myVar = 12-6; 
//myVar would have the value 6.
//Multiply Two Numbers with JavaScript (*)
const myVar = 13*13; 
//myVar would have the value 169.
//Divide One Number by Another with JavaScript (/)
const myVar = 16 / 2;
//myVar now has the value 8.

//Increment a Number with JavaScript (++) operator
i++;
//equivalent to 
i = i + 1;
//another ex 
myVar= mmyVar + 1;
myVar++
//Note: The entire line becomes i++;(1st example) eliminating the need for the equal sign.
//Decrement a Number with JavaScript (--) operator 
i--;
//equivalent to 
i = i - 1;
//another ex 
myVar = myVar - 1;
myVar--;
//Note: The entire line becomes i--(1st example), eliminating the need for the equal sign.

//Create Decimal Numbers with JavaScript (floats, floating point numbers )
//If results are not desired due to precision made with decimals, go to freeCodeCamp forum
var myDecimal = 5.7;
//Multiply Two Decimals with JavaScript
const product = 2.0 * 2.5;
//The product now equals 5
//Divide One Decimal by Another with JavaScript
const quotient = 4.4/2.0; 
//The quotient now equals 2.2

//Finding a Remainder in JavaScript
/*In mathematics, a number can be checked to be even or odd by checking the remainder of the division of the number by 2. Even numbers have a remainder of 0, while odd numbers a remainder of 1. Ex:*/
17 % 2 = 1;
48 % 2 = 0;
const remainder = 11%3;
/*Note: The remainder operator is sometimes incorrectly referred to as the modulus operator. It is very similar to modulus, but does not work properly with negative numbers.*/

/*Compound Assignment With Augmented Addition (Right of the = sign is evaluated first with modified variable) */
myVar = myVar + 5;
//there are operators which do both a mathematical operation and assignment in one step ( += operator) 
let myVar = 1;
myVar += 5;
console.log(myVar);
//6 would be displayed in the console. ex below
let a = 3;
let b = 17;
let c = 12;
// Only change code below this line
a = a + 12;
b = 9 + b;
c = c + 7;
//My solution 
a += 12;
b += 9;
c += 7;

//Compound Assignment With Augmented Subtraction (-=)
//Like the += operator, -= subtracts a number from a variable.
myVar = myVar - 5;
//will subtract 5 from myVar. This can be rewritten as:
myVar -= 5;
//examples below
let a = 11;
let b = 9;
let c = 3;
// Only change code below this line
a = a - 6;
b = b - 15;
c = c - 1;
//My solution
a -= 6;
b -= 15;
c -= 1;

//Compound Assignment With Augmented Multiplication (*=)
//The *= operator multiplies a variable by a number.
myVar = myVar * 5;
//will multiply myVar by 5. This can be rewritten as:
myVar *= 5;
//examples below
let a = 5;
let b = 12;
let c = 4.6;
// Only change code below this line
a = a * 5;
b = 3 * b;
c = c * 10;
//My solution 
a *= 5;
b *= 3;
c *= 10;

//Compound Assignment With Augmented Division
//The /= operator divides a variable by another number.
myVar = myVar / 5;
//Will divide myVar by 5. This can be rewritten as:
myVar /= 5;
//Examples below
let a = 48;
let b = 108;
let c = 33;

// Only change code below this line
a = a / 12;
b = b / 4;
c = c / 11;
//My solution 
a /= 12;
b /= 4;
c /= 11;

//Escaping Literal Quotes in Strings (\) Interesting but strict 
//When you wanna quote in quotes you (\) it'll consider it end of string quote 
const sampleStr = "Alan said, \"Peter is learning JavaScript\".";
/*This signals to JavaScript that the following quote is not the end of the string, but should instead appear inside the string. So if you were to print this to the console, you would get:*/
//Alan said, "Peter is learning JavaScript".
//Another example 
const myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line
//I am a "double quoted" string inside "double quotes".
//Seemingly the plan is to stop the double quotes from pairing with one another with a backslash \, also 4 \ and 2 sets of "" were used above 

//Quoting Strings with Single Quotes
//Start and end with the same ' or " you started with
const doubleQuoteStr = "This is a string"; 
const singleQuoteStr = 'This is also a string';
//Example const conversation = 'Finn exclaims to Jake, "Algebraic!"';
/*However, this becomes a problem if you need to use the outermost quotes within it. Remember, a string has the same kind of quote at the beginning and end. But if you have that same quote somewhere in the middle, the string will stop early and throw an error.*/
const goodStr = 'Jake asks Finn, "Hey, let\'s go on an adventure?"'; 
const badStr = 'Finn responds, "Let's go!"';
//badStr will throw an error.
//In the goodStr above, you can use both quotes safely by using the backslash \ as an escape character. Also / is not the same as a \, also <a> tag exists
const myStr = "<a href=\"http://www.example.com\" target=\"_blank\">Link</a>";
const myStr = '<a href="http://www.example.com" target="_blank">Link</a>'; 

//Escape Sequences in Strings (list below)
Code	Output
\'	single quote
\"	double quote
\\	backslash
\n	newline
\t	tab
\r	carriage return
\b	backspace
\f	form feed
*You will need to use escape sequences to insert special characters correctly. You will also need to follow the spacing as it looks above, with no spaces between escape sequences or words.Ex below*/
const myStr="FirstLine\n\t\\SecondLine\nThirdLine";
//Double backslashes \\ not // as well as tight no spacing makes escaping doable 21mins

//Concatenating Strings with Plus Operator (""+"")
'My name is Alan,' + ' I concatenate.'
/*Note: Watch out for spaces. Concatenation does not add spaces between concatenated strings, so you'll need to add them yourself.*/
const ourStr = "I come first. " + "I come second.";
//The string (I come first. I come second.) would be displayed in the console.Ex below
const myStr = "This is the start."+" This is the end."; // 

//Concatenating Strings with the Plus Equals Operator
//By linking together strings, with += you split it into lines removing exagerrated verboaseness (Watch out for space)
let ourStr = "I come first. ";
ourStr += "I come second.";
//ourStr now has a value of the string I come first. I come second..
let myStr= "This is the first sentence. ";
myStr+= "This is the second sentence."

//Constructing Strings with Variables (+myVar, etc)
const myName = "Josh Claros";
const myStr = "My name is"+myName+"and I am well!";

//Appending Variables to Strings (+=)
const anAdjective = "awesome!";
let ourStr = "freeCodeCamp is ";
ourStr += anAdjective;
//ourStr would have the value (freeCodeCamp is awesome!.)  The power of Appending Order of varibales matter too.
const someAdjective = "gorgeous";
let myStr = "Learning to code is ";
myStr+=someAdjective;

//Find the Length of a String (=blahblah.length;)
//You can find the length of a String value by writing .length after the string variable or string literal.
console.log("Alan Peter".length);
// Setup ------
let lastNameLength = 0;
const lastName = "Lovelace";
// Only change code below this line
lastNameLength = lastName.length;
/*For example, if we created a variable const firstName = "Ada", we could find out how long the string Ada is by using the firstName.length property.*/

//Use Bracket Notation to Find the First Character in a String  (=[0];)
/*Most modern programming languages, like JavaScript, don't start counting at 1 like humans do. They start at 0. This is referred to as Zero-based indexing.*/
const firstName = "Charles";
const firstLetter = firstName[0];
//firstLetter would have a value of the string C. In this case firstName "Charles" if Indexed "0 for C" "1 for H" "2 for a"  "0123456" ex agin for below
// Setup
let firstLetterOfLastName = "";
const lastName = "Lovelace";
// Only change code below this line
firstLetterOfLastName = lastName[0]; // Ctl

//Understand String Immutability  (use myStr = "look not myStr[0] = "l" no index for string reassignment)
// Setup
let myStr = "Jello World";
myStr[0] = "H"; // Ctl
//actual below, false above 
let myStr = "Jello World";
myStr= "Hello World"; // Ctl

//Use Bracket Notation to Find the Nth Character in a String [Lastname 012345 etc] or [firstName 3] just keep Zero based indexing in mind
const firstName = "Ada";
const secondLetterOfFirstName = firstName[1];
//secondLetterOfFirstName would have a value of the string d. Another ex. below
const lastName = "Lovelace";
const thirdLetterOfLastName = lastName[2];
//Simply got the variable to be the letter it was preordained with plus the correctly numbered index bracket

//Use Bracket Notation to Find the Last Character in a String firstName[firstName.length-1]
const firstName = "Ada";
const lastLetter = firstName[firstName.length - 1];
//lastLetter would have a value of the string a. casesensitive fyi

//Use Bracket Notation to Find the Nth-to-Last Character in a String (firstName.length-3) >1
const firstName = "Augusta";
const thirdToLastLetter = firstName[firstName.length - 3];
//thirdToLastLetter would have a value of the string s.

//Word Blanks 25 mins (myVar + " ")
const myNoun = "dog";
const myAdjective = "big";
const myVerb = "ran";
const myAdverb = "quickly";
const wordBlanks = "In the forest a " + myAdjective + " " + myNoun + " " + myVerb + " " + myAdverb + "."; 
//spaces should be applied between quotes past the addition operator sequential to the variable 

//Store Multiple Values in one Variable using JavaScript Arrays (= ["peanut butter", "jelly", "bread", 3]) several pieces of data is stored this way
const myArray = ["Italy",1];

//Nest one Array within Another Array
const teams = [["Bulls", 23], ["White Sox", 45]];
//This is also called a multi-dimensional array. ex below
const myArray = [["Guardian", 1],["Rhulk",0]];

//Access Array Data with Indexes (var myData = myArray[0];) keep the brackets tight with the previous letter no spaces 
const myArray = [50, 60, 70];
var myData = myArray[0];
console.log(myArray[0]);

//Modify Array Data With Indexes (myArray[0]=45;)
//Modify the data stored at index 0 of myArray to a value of 45.
const myArray = [18, 64, 99];
myArray[0]=45;
//myArray should now be [45, 64, 99].

//Access Multi-Dimensional Arrays With Indexes (very intriging) (const myData = myArray[2][1];)
const arr = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14]
];
const subarray = arr[3];
const nestedSubarray = arr[3][0];
const element = arr[3][0][1];
//In this example, subarray has the value [[10, 11, 12], 13, 14], nestedSubarray has the value [10, 11, 12], and element has the value 11 .
//Using bracket notation select an element from myArray such that myData is equal to 8. Also no space between array name and brackets
const myArray = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14],
];
const myData = myArray[2][1];

//Manipulate Arrays With push Method (arr1.push(4,5);etc or myArray.push(["dog",3]);)
const arr1 = [1, 2, 3];
arr1.push(4, 5);

const arr2 = ["Stimpson", "J", "cat"];
arr2.push(["happy", "joy"]);
//arr1 now has the value [1, 2, 3, 4, 5] and arr2 has the value ["Stimpson", "J", "cat", ["happy", "joy"]].

//Push ["dog", 3] onto the end of the myArray variable.
const myArray = [["John", 23], ["cat", 2]];
// Only change code below this line
myArray.push(["dog",3]);
//myArray should now equal [["John", 23], ["cat", 2], ["dog", 3]].

//Manipulate Arrays With pop Method  (var removedFromMyArray = myArray.pop(); .pop() last element of array
const myArray = [["John", 23], ["cat", 2]];
var removedFromMyArray = myArray.pop();
Passed:myArray should only contain [["John", 23]].
Passed:You should use pop() on myArray.
Passed:removedFromMyArray should only contain ["cat", 2].
//.pop()function removes the last item from myArray assigning the popped off value to a new variable.

//Manipulate Arrays With shift Method .shift() 1st element of array
const ourArray = ["Stimpson", "J", ["cat"]];
const removedFromOurArray = ourArray.shift();
//removedFromOurArray would have a value of the string Stimpson, and ourArray would have ["J", ["cat"]].
const myArray = [["John", 23], ["dog", 3]];
const removedFromMyArray = myArray.shift();
//myArray should now equal [["dog", 3]].:removedFromMyArray should contain ["John", 23]

//Manipulate Arrays With unshift Method 
const ourArray = ["Stimpson", "J", "cat"];
ourArray.shift();
ourArray.unshift("Happy");
/*After the shift, ourArray would have the value ["J", "cat"]. After the unshift, ourArray would have the value ["Happy", "J", "cat"].*/
//Add ["Paul", 35] to the beginning of the myArray variable using unshift().
const myArray = [["John", 23], ["dog", 3]];
myArray.shift();
myArray.unshift(["Paul",35]);
//myArray should now have [["Paul", 35], ["dog", 3]].

//Shopping List (include quotes for strings, none for numbers)
const myList = [["Milk",15],["Bouquet of flowers",3],["Fushigi ball",10],["Grapes",4],["Box of almonds",6]];

//Write Reusable JavaScript with Functions 
function functionName() {
  console.log("Hello World");
}
functionName();
//another ex below keep case sensitivity in mmind
function reusableFunction () {
  console.log("Hi World");
}
reusableFunction ();

//Passing Values to Functions with Arguments (functionWithArgs)
function testFun(param1, param2) {
  console.log(param1, param2);
}//ex below
function functionWithArgs (a,b) {
  console.log(a+b);
}
functionWithArgs (1,2);
functionWithArgs (7,9);

//Return a Value from a Function with Return (return)
//Create a function timesFive that accepts one argument, multiplies it by 5, and returns the new value.
function timesFive(num) {
  return num * 5;
}
const answer = timesFive(5)
Passed:timesFive(5) should return 25
Passed:timesFive(2) should return 10
Passed:timesFive(0) should return 0

//Global Scope and Functions (Tricky)
/*Variables which are declared without the let or const keywords are automatically created in the global scope. This can create unintended consequences elsewhere in your code or when running a function again. You should always declare your variables with let or const.Using let or const, declare a global variable named myGlobal outside of any function. Initialize it with a value of 10.*/
Passed:myGlobal should be defined
Passed:myGlobal should have a value of 10
Passed:myGlobal should be declared using the let or const keywords
Passed:oopsGlobal should be a global variable and have a value of 5
// Declare the myGlobal variable below this line
let myGlobal = 10
function fun1() {
  // Assign 5 to oopsGlobal here
oopsGlobal = 5
}
// Only change code above this line
function fun2() {
  let output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
//Local Scope and Functions (Visible only within the function )
Passed:The code should not contain a global myVar variable.
Passed:You should add a local myVar variable.
function myLocalScope() {
  // Only change code below this line
var myVar = 10
  console.log('inside myLocalScope', myVar);
}
myLocalScope(myVar);

// Run and check the console
// myVar is not defined outside of myLocalScope
console.log('outside myLocalScope', myVar);

//Global vs. Local Scope in Functions 
Tests
Passed:You should not change the value of the global outerWear.
Passed:myOutfit should return the string sweater.
Passed:You should not change the return statement.
// Setup
const outerWear = "T-Shirt";
function myOutfit() {
  // Only change code below this line
const outerWear= "sweater"
  // Only change code above this line
  return outerWear;
}
myOutfit();

//Understanding Undefined Value returned from a Function (peculiar difficulty)
function addFive (){
sum += 5;
}

//Assignment with a Returned Value indeed
