                                     Introduction 


Roadmap ->

0.1-> Node js, js 
0.2 -> Vanilla frontend -> HTML,CSS,JS / DOM/BOM.
0.3-> Vanilla backend -> NODEJS,SQL
0.4-> Frontend With React
0.5-> Backend in MERN
0.6-> Good to go-> AWS, LAMDA, DURBAN, cloud


Invented in 1995-96 by braindan eich and used to add functionality in web pages
Our browser engine is wrapped inside c++ so it is fast


## In eyery language there are 5 things to do every time 
  i/p , o/p , condition, loop , variable and datatype



## !1 -> js is high level ,most popular,Dynamicly typed,  oops, scripting language, async, single threaded(single call stack)


used to give functionality to our website
IN 1995 by braindan eich and became ECMA std in 97
simple to learn
biggest community
use in frontend and backend also
good performance
free for all present in our computer browsers
can manupulate html like (create element, delete, change style, state behaviuour) etc using dom

It is the same script that I write for youtube channels 
script is java script and actors are HTML elements 
java is compiled and js is interpreted


Computer execute instruction and this instruction called statememts (vale operator expression, keyword and comments)


1. O/p is done using :- with this we can print in next line-> fior next line we use string
0.---->Console.log, innerHTML, window.alert or alert, document.write()

2. Java is static typed and js is dynamically typed // Mtlb js mai datatype declear karna nahi padta

JS is the single threaded language and syncronus 
sync - > Line by line 
Single headed means in a specific order
it is used to print in console 
only we can see it not user 


!1. Value -> Fixed(literal) ---> 10,20,"hello".
2. variable --> let a = 10; const x = 3.14;

2. Operator -> + - * % / < > == etc 
3. X + y --> expressipn
4. Comments //
5. identifiers -> calemCalse



## !Varianble ->
let const var -> all are local or bloclk scope inside a funxtion

var -> Global scope means inside block like if else loop also it can be used outside 
let and const -> Outside block they dont exise measn they are new inside a block 
if dont give value to them they are undefine

Let -> Redeclear not allow
let or var or const s = 10;
let s = "hello" // not allowed 

var 
var // allowed

hosting also not allowed

x = 10 ;

let x ;


const - > Block scope 
redeclear not allowed also reassign vaue also not allowed 
we can change array object u=but not fully array or object

!Datatype
Number, string, array, boolean, object, undefined 
JS compiler read from top to down left to right and it is a dynamicallu typed language 


If there is no js then no website will behave normally
Supported by all browser


## working

every browser have its js engine like crome- v8 ms-edge has chakra
whenever user access any file for the first time js comes from server to our computer 
then when user access it second time onwards it comes form chache memory  so that it woild not take time

Data comes from server to client now in html css js form, our machine understand binary so it convert in form of binary by compilation process

1. Data comes and all the unnecessary part remove in preprocessing process(white space and comments)
2. Goes to Lexuical analysis and streams of char follow particular pattern convert to tokens 
3. this token send to parser and parser convert it to parse tree parally information stored in symbol table and all errors also been detected
4. Parse tree send to sementix analysis and anoted parse tree created by adding actions with each node of tree using Syntax directed tree 
5. This SDT send to intermediate code generation which convert it to code use on any machine it is called intermediate code, made using DAG,AST or 3 adress code mainly
6. Intermediate code sent to code optimization code on baises of basic block(wether local or global block) is has been optimized using techniques like peephole optimization(redunant store, strength reduce, simplify alzebric expression, deadcode elemination, replace high with low,constant folding and binding, move code, loop fusion etc)
7. This optimize code send to machine code generator to generate machine code 

once data comes from server or cache it is in form of binary 
by byte stream decoder decode it to tokens and this token send to parser 
parser  - pre and parser 
pre-parser parse nunecessry code at that time 
parser parse code that is necessary at that time 
parser generate node based on tokens and create abstract syntax tree 

js is an interpreted language so it interpreted AST and generate byte code
This is slow so byte code and type feedback send to optimizing compiler
which generate highly optimized machine code 


## 3-> DOM - Document Object Model 

1. Whenever we make website , structure - HTML (Document).
2. we style it (Document).
3. JS add functionality to our document 

Document - HTML 
OBJECT - HTML Elements (h1,div,p).
Model - this whole model

                document = HTML ---------> root tag
                head     = body --------> child tag of root
                title    = h1 -----------> child tag of body
                         = p -----------> child tag of body

using this DOM js can manupulate the HTML and add functionality to it 
 
## 4-> Datatypes

So whatever data we are storing has some type called data type 
datatype are of different type - Number(1234..) , String ("Piyansh"), boolean(true false), Undefined , Null , Bigint(1234456n)

5-> variable 

var CEO_Name = "priyansh sharma"

1. var  - An container created (variable whose value can be vary)
2. name - container name as CEO_Name 
3. "priyansh sharma" - Stored in that container

let name = "Priyansh sharma" // here it is string 
name = 10; // here it is int 
name= true; // now here it is boolean

CEO_Name  = "Shreyansh Sharma"

and now value change

var name = "priyansh sharma" // its upperfunction is  constructor Function()
name.length // this proves this is an object and it contain different methods like length,touppercase,tolowercase
note -> every primitive datatype is an object (immutable object)

!Var is Global scope 
When delcelar insode a block it can be use outside and the value reflact on programe until use inside a function
If value of same variable inside a block change it will be changed throught programe

var a = 10 ; 
var a = 'piyu'; 
*allow here

!Var is hosted means 
name = 'priyansh shamrma';
var name;  // this is allowed

!let it is a block scope means if delcear inside a block it cant be use outside it 
let cant be redeclear and must be declear before use
let x = 10 
var x = 2 or let x = 20 // not allow 

!name = 'piyu';
var name;
not allow 

!COnst use for const value just like a  let

Cant change this value


! Function -> Set of instruction inside a comtainer, been used when we call it 
every time call new activation record created 
*(Whenever function has been called an new actiovation been creared in stack memory
*this activation record have multiple things like temp variables, access and control flow, actual params, return value, machine code statue.)

! function can return value and this can be recived at calling end


**!Object** 
object are like real world object have state and behaviour 
car -> state -> color, number of seats, type, doors
functionality -> applyBreak(), run(), 

const person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};

this represent object (thatparticular instance)
this.firstName = Jhon in this example.

!or 

var a = new String() this is also an object 


**!Events**
When we click or hover or visit basically perform some sort of actions, any event happens 
we can give event inline inside a tag 

<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>

Note

**-> Compare js object always return false**

**! String -> Array of character is string defined in single or double quote String metjods** 
1. Slice(start, end) -> return new string and also take -ve values
2. substring(start,end) ->   same as slice in this -ve value taken as 0
3. substr(start,how mant to slice length)
4. replace('word to replace','new word')
5. upper lower case and t1.concate(" ", t2)
6. trim , trim the additional space
7. Split return new array of char

**Search in string** 
1. indexOf()
2, search()
3. lastIndexOf()
4. includes(searchword, starts indx)
5. starts with and end wirth

**!Number is 64 bit floating point niumber**
+ -: Addition and also concate
- * / is same 
object always return false when COmpare
different methods like parseInt, valueOf, Minvalue Max value

**!( "Use Strict" )**
This just help you to write cleaner code avoide errors 
just place "use strict" on top of variable or function it will give you error if it is not decleared

**!Remember points**
Remember basics 
Use console.log to detect error
Use const in object and array declear to avoide mistake changes 
Use local over global and declear variable at top of block 
Always initlize variable array objects functions


**!Object**
!In js almost everything is object (string,number and boolean with new keyword)

Onjects are variable contain many values 
let priyansh = {
    name : Priyansh shamra,
    enro : 0808CS191147,
    age : 20 // primitive values which is hardcoded (number string bool undefine bigint null)
    study : function()
}

! or 
let name = new onject();
name.FullName = Priyansh sharma
name.age = 20
!Property 
Value associate with object (variable name inside the object)
name.Fullname 
name["FullName"]
name.en = 191147
name.workout = ()=>{
    return 1
}
delete name.en 

**!Nested**
  const myObj = {
    name: "John",
    age: 30,
    cars: [
      {name:"Ford", models:["Fiesta", "Focus", "Mustang"]},
      {name:"BMW", models:["320", "X3", "X5"]},
      {name:"Fiat", models:["500", "Panda"]}
    ]
  }

  let myValue = myObj.cars[2]["models"][1]
  console.log(myValue)

**! Methods** 
const person = {
  firstName: "John",
  lastName: "Doe",
  id: 5566,
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};


console.log(person.fullName())

**!Display**
1. person.name + "," + person.age + "," + person.city;
2. For in loop 
3. const myArray = Object.values(person);
4. let myString = JSON.stringify(person);

**!Constructor**
function Person(first, last, age, eyecolor) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eyecolor;
  this.name = function() {
    return this.firstName + " " + this.lastName;
  };
}

const piyu = new Person("priyansh","sharma",20, "black-brownish")

**!Note**
Use string literals "" instead of new String().

Use number literals 50 instead of new Number().

Use boolean literals true / false instead of new Boolean().

Use object literals {} instead of new Object().

Use array literals [] instead of new Array().

Use pattern literals /()/ instead of new RegExp().

Use function expressions () {} instead of new Function().

**! Prototype** 
It is parent of all the objects allow you to add new property or method to js constructor

function Person(first, last, age, eyecolor) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eyecolor;
  this.name = function() {
    return this.firstName + " " + this.lastName;
  };
}

Person.Prototype.gender = "Male";
Person.Prototype.run = ()={
    return this.fname + " " + "runs at 60km/hr"
}

**! Sets are object with unique values** 
let planet = new Set();
planet.add("mercury")
planet.add("venus")
planet.add("earth")

**! Map = Store value in key value pair** 
let class = new Map();
class.set("priyansh sharma",191147)
class.get("priyansh sharma")
we have size,clear,delete,typeOf(object),has(return true is exist)
Direct iteration 
class.forEach((key,value)={
  txt += key + " = " + value 
})

use for(let i in class.entries(for value) clss.key(for keys))

can use object as key 


**!Function -> Set of instruction inside a container  when call can be used**

funciton add(a,b){
    return a+b;
}

**!Expression - anymonous func**
const x = function (a, b) {return a * b};
let z = x(4, 3);

!((a,b)=>{
    return a*b;
})() // self invloktion funciton 

!typeof -> object 

**!Hosting is default property of function**

**!Call in js func**

const person = {
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
}
const person1 = {
  firstName:"John",
  lastName: "Doe"
}
const person2 = {
  firstName:"Mary",
  lastName: "Doe"
}

! This will return "John Doe":
person.fullName.call(person1);

**!Call with args** 
const person = {
  fullName: function(city, country) {
    return this.firstName + " " + this.lastName + "," + city + "," + country;
  }
}

const person1 = {
  firstName:"John",
  lastName: "Doe"
}

person.fullName.call(person1, "Oslo", "Norway")

**!Apply -> takes args as array form**

person.fullName.call(person1, ["Oslo", "Norway"])

!bind method is used to bind methods from one obj to other 
let fname = person.fullName.bind(person1)


**!Notes -> Closure**

If a bariable created withot a decleratrion then it is global 

**! Callback function** 

Function take i/p of function
const app = ['zoom', 'youtube', 'facebook', 'instagram']

app.forEach((value)=>{
  return value;
})
! This is callback functiuon
Function which run in background which dont block the flow of the programe
It can be sync or async also


5.2 -> Input in js ->
let args = process.argv;
console.log(args);
args is an array in which 
at 0 -> Node 
at 1-> Input.js (Location of file-name)
at 2-> Input value(10)


int i = args[2];
op-> 10

this is how we take input 


**6-> Naming Rule** 

Use camelCase  - Start lower and then follow by uppercase
use underscore for space
=


**7-> length function** 
length = var.name = gives you length of string


**8 -> include script in our cod**e 
async - It is used when we want to run script imediatily and be independent

defer - If your script need to wait for other to run we use defer  


**9- > Slice function** 

var name = priyansh 
name.Slice(0,1) ---- > slice from 0 to 1 (not inclkuded)  upperbound - lowerbound = total character we get 



**10 --> toUppercase and toLowerCase**
name.toUppercase(); for uppercase and lower case for lower 



**11-> operator --->  (+, - , * , / , % )**
it follow same rules as mathamatics.
== used to check
=== strict check (means also datatype)
!=
!==
<=
>=


**12--> inc dec operator** 

var a = 5;
var b = 3;

a++ // 6
b-- // 2 

a +=b //a = a+b // 8


**12 --> Functions  ---> Used to store functionality (Instructions) into contanier such that we can use it where**


series of instruction writen in curly braces are called function 
Ex --> Creating Function 
    function jainKeDukan(){
        console.log(leave house);
        console.log(100s eteps tojain ke dukan);
        console.log(back to home);
    }
All the instructions are stored inside container.
Function ----> a container created 
JainKeDukan ----> name to function 
Inside curly braises ----> inside container 

**------> Calling Function**     

                 getjainKeDukan();

                 return all the instructions 

**------------------>Parasmeterized Function-------------------------**
 Now this is where we can take input in function ,
 we have variable in paramaeter whos value vary from condition to condition
we call function to perform specific task but if we wanna perform specific instruction inside function according as we need we can specify paremeter or a variable 

declearing function
function jainKeDukan(flavour){
    console.log("I want this"+ flavour+ "ice cream");
}
main{
    jainkedukan("chocolate"); // calling function 
}

**---------------------return function ----> return output**

function jainKeDukan(money){
    return money * 1.5;
}

function main(){
    var cost= jainkedukan(4);
}

we can declear function inside a function 
which is return function 



note ---> In string to convert number to string ---> use numbertostring();
and to convert string to number ---> number (string name)

templates leterls --->`${variable name + varibale name} is a nice peron and his name is ${name} `


**--Intermediate--**
1----> Random number 

Math.random --> to generate random number 
create random 0-0.9 (not one)
this random is psucodo random means it repeat itself after few iterations
we can use floor to make it absolute value

use - 
--------------math.random() ---- > 0.356----------

n = n*14; ------> between 14---->12.44332342
math.floor()-------> 12



2---> 
if else elseif switch wala statement

**3--->collections - array---------------**
collection of similar type of elements is called array    
used to store elements of same type inside an variable and we can access it useing subscript index


var egg = [eeg1,e2,e3,e4];

var meraEgg = egg[3];

we have functions like 
arr.length ---> for array length 
arr.includes(3)--->boolean
arr.push to push element to array
arr.pop to pop 

array is also a object have key value pair called key- index , valie ["hello","id"]


**methods - >**

push - > add element at end 
unShift -> add at start and return new length 
pop -> delete last value and return 
shift -> remove first element and return 
change index = a[0] = 10;
indexOf("priyansh sharma") =  return index
indexOf("priyansh sharma",2) =  return index and start form 2
include("Priyansh") // return bool if true 
include("Priyansh",2) // return bool if true  start form 2


**find ->** 

let we have an objet 

var channels = 
    [
    { name : "priyansh sharma",
         subscribers: 31
    },
    {
        name: " pooname cookingshala",
        subscribers : 280
    }
    ]


console.log(channel.find(function(element){

    return element.subscribers===280;
}))


**Arrow function =**

console.log(channel.find((event =>{
    return element.subscribers===280;

})))

**concate - >**

add two arrays 
console.log(name1.concate(name2));

we can also use slice

**spread ->** 
var name3 = [...name1 , ... name2];

**join ->**
let name=['s','i','v','u'];
console.log(name.join(" "))
split - 
console.log(name.split(" "))

**Loop**
**-----------------while loop------------**

var count = 1; ------> initluze value ,  start  
while(count<=200)------>Condition  , end 
{
    console.log(count);
    count++; -----------> Increment , change
}

for and do-while same as java
**for in loop -------->**

note ---> use for in iteration and while in checking the state


**----------------object-----------------**
let animal={
    name : zebra;
    leg : 4;
}
for(let key in animal){
    console.log(key,animal[key])
}

**---------------arrays------------------**

let name = ['rishab','saabi];
for(let i in name){
    console.log(name[i]);
}

**for-of**
for(let naam of names){
    console.log(naam);
}

name.for-each(function(name,index){
    console ( name,index)
})

----------------------------------------------------

**conversion - implicit and explisit** 

we can convert 
number, string, boolean into each other 

string(123) = '123'
boolean (1) = true 
number("123") = 123

Note  -> compiler start form top to bottem
so ->

"number" + 1 + 5 = number15 because compiler see first string so it comvert 1 and 5 into string 
1+5+"number" = 6 number , compiler see number first it add all  