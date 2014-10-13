# [eFarmony Data Structures: Objects as Data Models](id:pt1)
[Back to Home](https://github.com/bgando/JS102)

In this section we will explore how to represent our eFarmony data as a JavaScript object.

**You will be placing all your code into the scripts.js file.** 

---

###[Animal User Model](id:model) 

This object will be the model of a single animal user. Extra points if you get the pun in the last sentence.

##### Object
An object to hold our data model...

- Create a variable, name it `animal`, and assign it an object literal.

With Dot Notation…

- Add a property called `username` and assign it a value.
- Ensure that your `username` property exists in animal by inspecting it in the console.

With Bracket Notation…

- Add a property called `tagline` and give it a value.
- Check that your property exists in the animal object by inspecting it in the console.
- Create a variable called `noises` and assign it an empty array `[]`
- Add the `noises` array to your object.
- Inspect your handiwork! Your object should look something like this:
``` 
  { username: 'DaffyDuck', tagline: 'Yippeee!', noises: [] }
  ```

##### Loops
- Loop through the properties of your animal object. 
- Count everytime it loops to keep track of the number of properties on your object.
- Write an if/else statement in your loop:
  -   If the key is `username`, console.log('Hi my name is ' + ___) //fill in with object's username value.
  -   If the key is `tagline`, console.log('I like to say ' + ___) //fill in with object's tagline value.
-   What happens if you return 'Hi my name is ' + ___ instead of using console.log() inside the loop?

##### Review
Let's go over some concepts:

- What are the different ways you can add properties and values to objects? 
- Which of these methods would you use if you wanted to add a property to an object that had a weird symbol (think '&')?
- What about if the property is a variable, how does that change the syntax?
