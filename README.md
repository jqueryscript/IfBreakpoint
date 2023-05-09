# If Bootstrap 5/4/3 Breakpoint do something
Detect Bootstrap 5/4/3 breakpoints to run conditional scripts and functions

Bootstrap 5
`<script src='if-b5-breakpoint.min.js'></script>`

Bootstrap 4
`<script src='if-b4-breakpoint.min.js'></script>`

Bootstrap 3
`<script src='if-b3-breakpoint.min.js'></script>`


### Are you extra-small?
```
// update onload
$(document).ready(function(){
  // update onload
  $("h2").text( breakpoint ); 
  
  if ( xs == true ) { 
    alert("mobile first");
  }

  // Update on window resize
  $( window ).resize( function(){
    $("h2").text( breakpoint ); 
  }); 

});
```
