








## 3.12 Hacks

##### Procedure:
- A procedure is a piece of code that is made to have accomplish a certain goal (like a function)

##### Parameter:
- A parameter is a variable that allows data to be imported into a function. 
    - A parameter can look like "a" and "b" in random.randint(a,b)

##### Return Value:
 - A return value is a value that returns to a procedure using a return statement
    - Python to continues executing the program and returns a certain value (Return Value)
    - Using a return statement 

##### 
### Quiz Score
![]({{site.baseurl}}/images/ProcedureQuizScore.png)



### Vocabulary

- **Modularity** - the practice of breaking a complex program into smaller, independent parts or modules that can be used and reused in different parts of the program
- **Abstraction** - the practice of hiding the details of how a particular code or system works and exposing only the essential features or functions that are necessary for other parts of the program to use
- **Duplication** - having multiple duplicate code blocks, often decreasing readability and efficiency
- **Logic** - the sequence of steps and operations that a computer follows to execute a program, including the specific instructions and decision-making processes built into the code


### 3.13 Vocabulary

- <font color="#ffffc2" style="font-weight: bold">Procedure</font> - a module of code that is created to complete a certain task, this is basically a function
- <font color="#ffffc2" style="font-weight: bold">Procedure Name</font> - the name that is given to a function/procedure
- <font color="#ffffc2" style="font-weight: bold">Parameters</font> - a variable that is used in a function to allow for data to be imported into a function
- <font color="#ffffc2" style="font-weight: bold">Arguments</font> - a way to provide information to a function, usually defined outside a function and then imported into a function with parameters

### 3.13 Questions

```javascript
function compare(a,b) {
    if(a>b) {
        console.log("a is greater than b")
    } else if (a<b) {
        console.log("a is less than b")
    }
}

// How do you call to this function?

```

#### what are the parameters?
- a and b

#### What is the output?
- "a is greater than b" or "a is less than b"

#### what are the arguments?
- (a,>b), (a< b)