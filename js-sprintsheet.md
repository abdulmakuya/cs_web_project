(Comment - Please lets start with date here)
java script
var,datatype,function,

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

```javascript
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
