# Introduction to javascript

-`javascript is a synchromous single thread language also called as line by line exception mode.`

## execution contex
- It contains two phase 
   - memory creation phase
   - code execution phase
  
**Memory creation phase**: *It is a phase where each variable  provided by a memory for exectution for variable ,it provides a special keyword "undefined" it is not a error a special key in js.
for funtion it provides whole code as in memory.*
### code example
var x= 10
function star (num){
     var ans = num * num;
     return ans;
}
var star2=star(x);

| memory | code |
|------- | ---- |
| x= undefined | x=10 |
| star = {...} | star = function{..} |
| star2=undefined | star2=10*10 |

**Code execution phase**: where the variables changes the value line by line provide by compiler.

**Call stack**:it is a function which handles everything to manage 
executuion contex like creation,deletion,and control.

**Hoisting in JavaScript** is a behavior where declarations of variables,
functions, and classes are conceptually moved to the top of their current scope during the compilation phase, 
before the code is executed.
