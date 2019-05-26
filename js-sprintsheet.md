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

console.log("my name is "+ name +
           " I live at " + adress);
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
      getPassportDetails : function(){
        return "Person's detail is " + this.firstname +
               "lives at " + this.adress;
      }
    };
    console.log(mm.firstname);
    console.log(mm.profession);
    console.log(mm.getPassportDetails());
    console.log(mm.getPassportDetails);
