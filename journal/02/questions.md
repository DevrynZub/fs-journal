# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > Var, Let, Const

02. What is the definition of a function?

    > A subprogram designed to run a particular task, a block of code we can also run manually as much as we need. functions allow us to see if javascript is running a particular set of data the way we want it too.

03. What are the `SOLID` principles?

    > I was unsure of where to find this, may have overlooked it but didnt know

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > 

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > you.friends.push(them), them.friends.push(you)

06. Give an example of a JavaScript `Conditional`:

    > conditionals are if or else statements or true/false. A good example would have been during lecture wednesday making the restaurant we used a conditional to see if the customer was ready to check out or now. 

07. What is the main difference between `parameters` and `arguments`?

    > parameters are what we set in a function to  determine what is passed down. Where an argument is the value of something we are passing down. 

08. Instead of writing everything to the console, what is a better way to debug your code?

    > you can use debugger in your code or console.log as you are going through to see if your code has errors. 

09. What is the difference between a `primitive` value and a `reference` value?

    > primitive references integers or numbers where as reference would deal more with arrays and objects

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for (let i = 0, <= 100, i++ )
console.log(i)