Intro on JavaScript:-

javascript is a high level programming language for building web application more efficient way.
- javascript works on both client side as well as server side rendering.
- javascript is comes from echms script so we see the latest version of javascript in the form of echma script.
- Now we used javascript version 6 i.e ES6 (echma script 6).
- In another way we called Esg as the vanilla javaScript.
- javascript is mainly used for building logics or functionlity of a web pages.

Variable:-
- variable is a container to store some data.
there are 3 types of variable present in javascript:
1. let :-
-> let is a type of variable which is used to changeing the variable name later.
-> Now these days, most of the cases we used let for creating variable.
-> let is the block scope code so we have been using let for most cases.

2. var:-
-> var is a types of variable which is also used to changing the variable latter stage.
-> var is used in oldest browser so now a days we are dont use var most of the cases.

3. const:
-> const is a types of variable where we can't change our data further.
-> const means constant to store some data like numbers, integer etc...

Rules for creating variable name :-
- variable names are case sensative "a", & "A" is different.
- only letter, digit, underscore & $ is allowed(not even space.)
- only letter, underscore or $ should be the first charecter only.
- reversed words cannot be variable.

data types:-
-> data types is an attribute associated with a piece of data that tells a  computer system how to interpet its value.
-> in data types we used "typeof" operator to know that what types of data it is.
-> mainly in javascript their are 2 types of data types.

1. primitive:- 
   In javascript there are 7 types of primitive datatypes .
   1. Number - Numbers sre the types of data types those it cointain some numeruical value.
   2. Boolean - In boolean data types we get boolean value like true , false.
   3. undefuned - In undefined data types data's are not define so that it will show undefined. 
   4. Null - In this data types we get null for the value means nothing.
   5. bigInt - in bigInt we will get big Integer value.
   6. symbol - in symbol we will get whole symbol as well as the value we get for the data types.
   7. String - String is a type of data 






Operator in js:-
-> operator are the key features to do some task or operate some task.
-> ex. A + B
-> in this above example A,B are the operands & "+" is the  operator.
-> there are 5 types of operator are their in javascript
   1. arithmatic operator
      (+,-,*,/)
      modulus -> %
      exponention -> **

   2. unary operator
      increment (++)
      decrement(--)

   3. assignment operator
      (assign some values to the variables)
      (=, +=, -= , *= , %=, ** =)

   4. comparision operator
      (compair the values)
      it gives the result of thre or false.
      eqal to -> ==
      not eqal to -> != 
      equal to & types -> ===
      not equal to & types -> !==

   5. logical operator
      checks the logic of the operator(true/ false)
      ->logical AND (&&) -> table of logocal AND operator is ->
         cond1      cond2     res(&&)
         T           T           T
         T           F           F
         F           T           F
         F           F           F

      ->logical OR (||) -> table of logocal AND operator is ->
         cond1      cond2     res(&&)
         T           T           T
         T           F           T
         F           T           T
         F           F           F

      ->Logocal Not(!)

   6. conditional  statemetnt:-
      - to implement some condition  in the code.
      - there are 3 types of conditional statement are there
      1. if condition:- 
         - if condition it true then statement is true otherwise falser.
         - Syntax:
           if(condition){
            statement
           }

      2. if-else condition:- 
         - if condition is true then if block is executed otherwise its terminate condition.
         - syntax - 
           if(condition){
            statement
           }  else {
               statement
           }

      3. if-else-if condition:-
         -  if(condition){
            statement
           }  else if(condition) {
               statement
           } else {
              //statement
           }





Loops in js:-

  - loops are used to execute a peice of code again and again.
  1. For loop :-
      syntax:-
        for(initialization; condition;updation) {
            statement
         }
   2. while loop:-
       syntax - 
        while(condition) {
         statement
         updation
        }
   3. Do-while loop:-
      syntax -
        do{
         statement
         updation
        } while (condition)

   4. for-of loop:- it iterate on string & array
   5. for-in loop:- it iterate over objects (key-value) pair.



String in javaStript :-

- String is a sequence of charcters used to represent text.
- create a string -> let str = "web bocket"
- string length -> str.length
- string indexing -> str[0], str[1], str[2]

Template literals in js :-
 - its a way to have embedded expression in string .
 - its denoted on ''.  'i.e today is a great day'

String interpolation :-
 - to create string by doing substitution of placeholders.
 - ex. `string text ${expression} string text`

String symbol :-
- \n - new line
- \t - tab inside a string

String method :-
- these are built in function to manupulate a string

1. str.toUppercase();
2. str.toLowercase();
3. str.slice(start,end);
4. str1.concat(str2);
5. str.trim();
6. str.replace(serachval,newval);
7. str.charAt(idx);

Arrays on js:-
- arrays is a collection of items.
- ex. 
 let heroes = ["irenman" , "huls", "thoer", "batman"];
 let marks = [20,30,90,59];
 let info = ["biswa", "rahulkl"];

- array index starting form "0".
- arr[0], arr[1], arr[2];

- looping over an array :-
 - loops -> iterable
 - syntax :-
 for(let i =0; i < arr.length;i++) {
   //statement
 }

 practice quickly:-

For a given array with marks of students -> [85,97,37,76,60]. find the average marks of the entire class.
for a given array with prices of 5 items of 4 items ->[250, 645,300,900,50]; all items have an offer of 10% off on them. change the array to store final price after appluing offer


array method :-

Push -> add an element to the end.
pop -> delete from end
toString -> converts array to string
concat -> joins multiple arrays & return result.
unshift -> add an element to the starting.
shift -> delete from start
slice() -> returns a piece of the array.
splice() -> change original array (add, remove, replace)


            







Home work:-
1. difference between let & var.
2. difference between var & const.
3. what do you mean by hoastin