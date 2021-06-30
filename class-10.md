
# JavaScript

![javascript](https://miro.medium.com/max/1800/1*5eV1xmJs2-sJ4DdejfdnQA.png
)

## **Error Handling & Debugging**

### Execution context

In JavaScript, execution context is an abstract concept that holds information about the environment within which the current code is being executed. Remember: the JavaScript engine creates the global execution context before it starts to execute any code.

*Every statement in a script lives in one of three execution context:* 

1- global context:
there is one global context in any page ( code that is in the script but not in a function) 

2- function context:
code that is being run within a function 

3- eval context (not shown):
text is executed like code in an intrnal function called eval()


![javaerr](https://www.learnsimpli.com/wp-content/uploads/2020/02/4-6.png)


### Variable Scope

Scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. 

***The two types of scope:***

1- Global scope

if a variable is declared out side a function it can be used anywhere because it has global scope.

2- Function level scope

when a variable is declared within a function it can only be used within that function (because it has function level scope).


### Error objects

Error objects are thrown when runtime errors occur. The Error object can also be used as a base object for user-defined exceptions. **error object can help us find the where is the mistake are and there are tools in the browser to help us read them.**


when an error object created it will contain the following properties:

1- name : type of execution 

2- message : description 

3- file number : name of the JS file

4- line number : line number of error

***if there is an error we can see all of this properties in the console of the browser***


![javaerrors](https://miro.medium.com/max/866/1*aadFSicd8Hr8nIer_5bZsg.png)


### Types of build error object in JS

1- error : generic error (the other error are all based opon this error ) 

2- syntaxError : synatx has not been followed 

3- referenceError : tried to reference a variable that is not declared 

4- typeError : an unexpected data type that cannot be coerced 

5- rangeError : number not in acceptable range 

6- URIError : endcodeURI() , decodeURI() and similar methods used incorrectly 

7- evalError : eval() function used incorrectly

### What is debugging JavaScript?

The debugger statement stops the execution of JavaScript, and calls (if available) the debugging function. Using the debugger statement has the same function as setting a breakpoint in the code. Normally, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

### How to deal with error?

![javaer](https://uploads.sitepoint.com/wp-content/uploads/2016/04/1496946239error.jpg)


1- debug the script to fix errors

if someone report a bug , we need to debug the code track down the source of the error and fix it

2- handle errors gracefully

we can handle errors gracefully using try , catch throw and finally statements


**For more info and learn more about JS visit this *[link](https://slack-files.com/files-pri-safe/TNGRRLUMA-F025KUGCBD1/javascript_and_jquery_interactive_jon_du.pdf?c=1624216453-2d17e5b1f6a263c9)* 
to download the book online**

HI ... my name is Ola 23 years old i'm a Nutritionist and my computer operating system version number is windows 10 and i'm so excited for this course because i want to learn something very important to me 

click on the [link](https://github.com/olaaltaslaq) to find my GitHub

