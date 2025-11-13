# JS Functions 
- It is a block of code which does a specific task
   - syantax
      - function functionname(parameters){...}

  `Shortest code in js is a emoty code becoz it access a window and follows the execution contex and also allocates a memory`

    ## Difference between undefined and not defined
  | undefined | not defined |
  | --------- | ----------- |
  | it is place holder in memory which locks or provide some space for the variable to hold its value or parameters in memery | it is a error when the variable or parameter is not initialises |
  | ex : var a = 1 ; in memery phase of execution contex it shows undefined after reaching code executon it allocates the space and hows 1 | ex: if we not intilisevar a = ? it shows a is not defined |

  ### What is Scope ?
  `when a compiler access a specific variable or funtion in code`


  **what is lexical environment**
  it is a local memory along with the lexical environment of its parent
  ex: function a(){
         var b = 2
         function c(){
         }
      }
  **in this example a is lexical parent of c, and global reference is lexical parent of a**

  **Define lexical**
  it is a hierchy or sequence or a order in js
  for above example function c is lexical of a

  **scope chain**
  the chain of all lexical environment & the parental references_

