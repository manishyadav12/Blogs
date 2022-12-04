# How JavaScript Works


# OVERVIEW

 Javascript is scripting language that runs on the client's machine (user system) in the web browser.

 To run javascript, the browser should be javascript enabled, which means the browser have javascript engine.
     Google Chrome has javascript engine known as V8.

>                           Edge     -   Chakra
>                           Safari    -  Javascript core
>                           Firefox  -  Spidermonkey

It is the javascript engine that understands the code and runs it.

Javascript is an interpreted language that means it gets executed in line by line manner.

Javascript engine runs the code line by line instead of whole program once.


# STEPS INVOLVE IN THE EXECUTION OF JAVASCRIPT CODE



![Screenshot 2022-10-12 114703.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665555450682/p8pMS6ep9.png align="left")



## PARSER

First, the code goes through parser, which checks for syntactic errors line by line.

If error is detected, it throws a kind of error and stops the execution of the code.



## ABSTRACT SYNTAX TREE (AST)

If the code does not have any errors, it creates abstract syntax tree.

Example:
          

              
```
function foo(d) {
  d += 3;
    return d+999
}
function bar(d) {
    return d*100

``` 

Abstract syntax tree for the above javascript code :


![Screenshot 2022-10-12 122102.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665557550800/_J4899MEY.png align="left")
 


## CONVERSION TO MACHINE CODE

After the creation of Abstract syntax tree (AST), the javascript engine converts the javascript code to machine code.



## MACHINE CODE

After the javascript program is converted to machine code/byte code, the byte code is sent to the system for execution.

Then the byte code is run by the engine.



sources:
[Javatpoint](https://www.javatpoint.com/how-does-javascript-work)
[Stackoverflow](https://stackoverflow.com/questions/16127985/what-is-javascript-ast-how-to-play-with-it)








