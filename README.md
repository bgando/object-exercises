# [eFarmony Data Structures: Objects as Data Models](id:pt1)
[Back to Home](https://github.com/bgando/JS102)

In this section we will explore how to represent our eFarmony data as a JavaScript object.

**You will be placing all your code into the scripts.js file.** 

---

### [Step 1: Animal User Model](id:model) 
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

Loops
- Loop through the properties of your animal object. 
- Count everytime it loops to keep track of the number of properties on your object
- Write an if/else statement in your loop
  -   If the key is `username`, console.log('Hi my name is ' + <username>) //fill in with object's username value
  -   If the key is `tagline`, console.log('I like to say ' + <tagline>) //fill in with object's tagline value
-   What happens if you return 'Hi my name is ' + <username> instead of console.log() inside the loop?
