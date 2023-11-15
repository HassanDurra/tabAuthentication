# tabAuthentication
This is a plugin to show error on pages if they are opened more then one time and also will calculate how many times the tab is opened except the current page.
using jquery.
User manual 

if you want to initialize the plugin must use this function name

tabCounter() // it requires to paramters one for showing the container class or id and other to where show the countings 

for example : 
let errorContainer = $(".error-container");
let counterContainer = $(".counterContainer");

tabCounter(errorContainer , counterContainer); // first paramter must be the error container variable and the other should be the counter container .
