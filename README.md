#  Lesson 2 Practice Hands-On

# Directions

     For your Lesson 2 Practice Hands-On, you will be working with your knowledge on TypeScript classes and generics. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page. Follow the below steps for setup.

#                                               Setup
                  Open up your terminal/command prompt.
                  Navigate to your desktop in your terminal.
                  cd Desktop
                  Next, navigate to the FullStackWeb directory in your terminal.
                  cd FullStackWeb
                  Then, navigate to the FEFAngular directory in your terminal.
                  cd FEFAngular
                  Create a new project folder named L02HandsOn located within the FEFAngular folder in your terminal.
                  mkdir L02HandsOn
                  Once the process is complete, navigate into the L02HandsOn directory:
                  cd L02HandsOn
                  Run the following to open your new project in VS Code (or you can open the folder within VS Code directly):
                  code .
                  Create a file named package.json and add the following code:
                  {
                  "name": "lesson-two-handson",
                  "version": "1.0.0",
                  "description": "lesson 2 hands on for the Angular course",
                  "main": "index.js",
                  "scripts": {
                        "start": "tsc && node index.js"
                  }
                  }
                  Create a file named index.ts
                  Within your command prompt/terminal (make sure you are within the L02HandsOn directory), run the following to create a tsconfig.json file:
                  tsc --init
                  Run npm start to create the index.js file.

##                         Part 1
                  To begin, add the following code into your index.ts file:
                  interface Person {
                  firstName: string;
                  lastName: string;
                  birthday: Date;
                  }
                  Create a new class named Entry.
                  This class should implement the Person interface above.
                  Add the following values into the Entry class:
                  a firstName value.
                  a lastName value.
                  a valid date for birthday.
                  Create a new instance of the Entry class with the name of newPerson. This new instance should include the following values as the correct types:
                  Albert, Einstein, 5/14/1879
                  Hint! You will need to use new Date()

                  Console.log the values of newPerson so the output looks like the following:
                  First Name: Albert, Last Name: Einstein, Birthday: Wed May 14 1879 00:00:00 GMT-0700 (MST)

###                                                   Part 2
                  Create an array named numbers including the following elements:
                  'twelve'
                  'one-hundred'
                  'sixteen'
                  'forty-four'
                  'seventy-three'
                  'three-million'
                  Create a generic function named sortArray with the type of <S>.
                  This function should take in an array and sort the elements in alphabetical order.
                  Hint! You will need to use .sort() function

                  Add two console.logs:
                  One should console.log the array before it is sorted
                  One should console.log the array after it has been sorted
                  Hint! You will need to call the sortArray generic function

                  The output should be similar to the following:
                  Array before sorting: twelve,one-hundred,sixteen,forty-four,seventy-three,three-million
                  Array after sorting: forty-four,one-hundred,seventy-three,sixteen,three-million,twelve
                  Example
                  When finished, your project should look similar to the following:

                  l2 handson

