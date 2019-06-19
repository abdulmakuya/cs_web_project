(Comment - Please lets start with date here)




# Topics covered in this sprintsheet
Where does the cow fit in,var,datatype,function,

Where does the cow fit in.  
Validate web forms before submission
Create cookies to store and retrieve data on a user’s computer for future visits

Variables
```javascript
var name = "makuya";
var adress = "mzambarauni"
var names="Rahila";
var address="Kisauni";

console.log("my name is "+ name +
           " I live at " + adress);
 console.log("My name is "+ names+ " I live at"+ address);          
```
Switch Case 
```javascript
var num = 5;
switch(num)
{
   case 5:
      console.log("num is equal to 5");
      break;
   case 10:
      console.log("num is equal to 10");
      break;
   default:
      console.log("num is: "+ num);
}
```


Methods of linking js sourcecode

```javascript
//1.On page script
<script type="text/javascript">  ...
</script>

//2.Linking to external files
<script src="filename.js"></script>

//Output types
console.log(a);             // write to the browser console
document.write(a);          // write to the HTML
alert(a);                   // output in an alert box
confirm("Really?");         // yes/no dialog, returns true/false depending on user click
prompt("Your age?","0");    // input dialog. Second argument is the initial value

//Edit DOM element
document.getElementById("elementID").innerHTML = "Hello World!";
```

Functions
```javascript

Functions
function addNumbers(a, b) {
    return a + b; ;
    x = addNumbers(1, 2);
}
```


Javascript Objects
IN JAVASCRIPT,OBJECTS ARE KING.IF YOU UNDERSTAND THEM - YOU UNDERSTAND JAVACRIPT

In JavaScript, almost "everything" is an object.

Booleans can be objects (if defined with the new keyword)
Numbers can be objects (if defined with the new keyword)
Strings can be objects (if defined with the new keyword)
Dates are always objects
Maths are always objects
Regular expressions are always objects
Arrays are always objects
Functions are always objects
Objects are always objects

```javascript
//the following example creates a mm object with five properties
var mm = {
    	firstname:"Abdul",
      lastname:"Makuya",
      nickname:"Samid",
      adress:"Ukonga",
      profession: {
        one : "developer",
        two : "designer",
        three : "trainer"
      },
      //languages:[]
      getPassportDetails : function(){
        return "Person's detail is " + this.firstname +
               "lives at " + this.adress;
      }
    };
    
    //printing
    console.log(mm.firstname);
    console.log(mm.profession);
    console.log(mm.getPassportDetails());
    console.log(mm.getPassportDetails);
    
    //alternatively
    
    var me = new Object();
    me.firstName = "Abdulswamad";
    me.lastName = "Makuya";
    me.age = 50;
    person.eyeColor = "black";
    
    //JS Objects are mutable meaning
    var mimi = me;
    mimi.firstname = "Abdulmagid" //name changed in me and mimi object
    
    /*this is a constructor method,note it uses this when defining its variables
    because it doesnt know yet the personal particulars of the person,
    also it can have its method
    Therefore the function can be called by user001.getName();
    */
    function User(firstName, lastName, dateOfBirth) {
    this.firstName = firstName;
    this.lastName = lastName;
    this.dateOfBirth = dateOfBirth;

    this.getName = function(){
      return "User's name: " + this.firstName + " " + this.lastName;
   }
}

var user001 = new User("John", "Smith", 1985);


//Accesing object properties
objectName.property         // person.age
or

objectName["property"]      // person["age"]
or

objectName[expression]      // x = "age"; person[x]
