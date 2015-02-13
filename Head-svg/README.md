# head-svg.js

Chrome cheats.  
It does not render scripts into runnable code in a predictable sequence.  
So checking for resources via a dependency tree can be done with head.js and some lines of javascript.  
For Firefox pauseBetweenLoads can be set around 10.  
For Chrome, this has to be bigger, sometimes 200.  
Chrome looks faster and actually is as long as the js loading is simple.  
With significant js resources, Firefox might actually be faster as the pauseBetweenLoads is not 'averaged' at a higher value.  
  
Licenses are inherited from originals.  
Pull request withheld due to head being in redesign.  
