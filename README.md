# T3A1-Workbook-
 ## 1. Provide an overview and description of a standard source control process for a large project 

The standard source control process refers to the process of tracking and managing of code within a project. 

This process is beneficial because it allows users to edit code stored on their personal computer while the same code remains unaltered in their repository.

 Large groups utiliizng standard source are best served using the Gitflow design which consists of a branching system where the master and develop branch are the central branches and the supporting branches are the feature, release, and hotfix branches. This workflow works well because n

 The master branch's reflects the official release history of the project. 
 
 The development branch is a complement to the main branch that reflects the latest changes of a project. A member from the project would create this branch, and the rest of the team would individually clone this branch and make appropriate changes.  The creation of the development branch is needed so the original code in master branch can remain untouched and depoloyable and  developers can expirement with the development branch. 
 
The feature branch is the child branch off of the latest develop branch.  Feature branches do not   directly interact with the master branch and are only merged into the develop branch when a feature is complete. 

After the feature branch receives a sufficient amount of features required for release. a release branch is then forked from the develop branch. The release branch is essentially to support preparation of a new production release. Tasks related to production release such as bugh fixes and documentation generation go into this branch. By making the feature branch a a dedicated production release branch,  


The hot fix branch is used in prpeparation of new production releases and forks directly off of the master branch. When bugs are identified, a hot branch is created so a team can quickly fix and patch the bug and merge the branch back into master. By creating a dedicated branch for bug fixes, a team can handle big fixes without interfering with the Git workflow.


 


Source: 
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow 

https://nvie.com/posts/a-successful-git-branching-model/
 

## 2. What are the most important aspects of quality software? 

The seven aspects of quality software are:
Reliability
Understandibility
Modifiability
Usability
Testability
Portability
Eficiency

These aspects are key in order for any software program or source code to be deemed high quality.   

Reliability entails a program should behave as expected, and consistely throughout each use.Software should be reliable and errors should be nonexistent or scarce.Additionally,users should have confidence the product they're using will work correctly.  

Understandibility encompasses the structure of source code. Code should always be clear, well organize, and simple.Most importantly, At first glance, it should be easy to acertain what the code is doing. clear code is a reflection of the users understanding In addition to this, a developers' source code performance should be predictable and not deviate from its original purpose.  



Modifiability refers to the modification of a system. A program should be easy to edit and/or change, and can be done without having to change many lines of code. Plug in points where an application can be used with different elements is also expected. 



Usability entails the use of the software product. The product must be must be easy to set up and use, and users should have a seamless experience when using the program. Users should also be able to navigate through the program without needing outside sources for clarification on functionality. 


Testability of software must be easy and verifiable, and  Testing metrics should be obeservable,controllable and deployable. 


Software should be able to be used in different operating systemns and reused across different programs and environments. Reusability is key. 


Efficiency attests to the speed and efficency of the program. The program must be fast, conscious of memory usage, battery efficient, and self reliant.  


 
Source: 
https://www.silasreinagel.com/blog/2016/11/15/the-seven-aspects-of-software-quality 

 

 
## 3. Outline a standard high level structure for a MERN stack application and explain the components 

The Mern stack is an hierarchy of 4 technologies (MongoDB, Express, React, and Node) that come together to create a full stack application. 


React.js is a powerful Javascript library that allows users to build complex interfaces using simple components. React also updates and renders data in HTML as data in an application is changed.  Essentially, React is the view layer of an MVC application. 


MongoDB is a document database that stores data such as user profiles, comments, uploads, and more.  

Express is a Node.js web application that provides featured for mobile and web applications and also handles HTTP requests and responses. 


Node.js is Javascript runtime environment in which Express is run from.  


React is at the top of the MERN stack tier and handles forms, error handling, events, lists, and more. Baically, the user interacts with React UI components while in the back end,  Express JS runs on Node.js and handles HTTP requests and responses. Any changes made to data is sent through an HTP request to the Express server, which is then acquired from the MongoDB server if necessary. The data is then returned through to the front end side, React, which is then viewed by the user. 



One benefit of the MERN stack is all code across the tiers are written in Javascript which eliminates the need for context switching and has the added bonus of being the sole language user need to learn in order to operate the stack.

Another benefit the Mern Stack is the reusability of React components, the easy scalability of Node js', MongoDBs' powerful data manaagement system, and Express js' flexibility and performance.  

Source: 
https://www.mongodb.com/mern-stack 

https://blog.hyperiondev.com/index.php/2018/09/10/everything-need-know-mern-stack/#:~:text=The%20Benefits%20of%20the%20MERN,no%20need%20for%20context%20switching.
 

## 4. A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project? 

Members of the team must have both hard skills and soft skills in order to succesfully decelop the website for the small business. 

Hard skills, or technical abilities, needed to complete the website are at minimun, HTML, CSS, and Javascript. HTML is the standard markup language used to create pages/page structure in the browser, and CSS is used to style the HTML structures and dictates how HTML should displayed within a page. Javascript is needed to turn the small businesses's website from a static website to a dynamic one. Javascript will allow customers to interact with features such as form validation, and have a smooth experience making bookings, inquiries, and more. 

A front end framework such as Angular, React, or View is a required hard skill if the small business intends to store user information. 


In the Agile methodology, members of a team are expected to work harmoniusly on a project within small incremenets and must have the ability to quickly respond to change. Thus, soft skills such as team work, creativy, adaptability, open communication,  organizational skills, and trust are soft skills required to deliver high quality services to clients within a quick time frame. 

However, there are caveats. If a team is lacking in tech skills such as Javascript, but are creative, they can use certain CSS properties to handle user interaction. Likewise, if creativiy is a lacking soft skill, React components that have been created by other developers can be reused in order to make the application appealing. 

Source:
https://www.atlassian.com/agile/teams 

 


## 5. With reference to one  of your own projects, discuss what knowledge or skills were required to complete your project, and to overcome challenges 
My portfolio assignment was a project that required knowledge of CSS and HTML. Knowledge of JS was optional, as the portfolio website only needed to be a static website that rendered CSS and HTML to the screen. HTML was used to build the basic page, along with the structure, and CSS was used to style elements and dictated how HTML should displayed within the portolio page. 

In order for the project to successfully finish within the deadline, soft skills such as time and project management, creativity, and adaptability, and creativity, and communication were crucial. 

Time and management skills were necessary because I needed to finish my project before the deadline and needed to allocate a certain amount of to dedicate to each tech stack as well as documentation required for submission. Without these soft skills, I could have easily spent too much time on one area of my project such as CSS, while failing to complete documentation needed for a passing grade. 

Adaptability is a soft skill which complemented the time and management skills. Once the deadline became close, I needed to adapt my expectations and abandon additional styling so that I could focus on docunentation and code organiation. Had I not been able to adapt, the deadline would not have been met. 

Creativity was needed in order to create a portfolio that was orginal and reflective of my personal brand. 

Lastly, open communication was vital when navigating through hurdles and roadblocks I faced when coding. I needed to be able to openly communicate with my instructor as well as cohort when I needed help so that I could use my time wisely instead of spendig large amounts of time solving a problem.  
 

## 6. With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project, and suggest changes or improvements for future projects of a similar nature 

For my rails application, hard skills neeeded to succesfully build out my application was   Ruby, HTML, CSS, and PostgresQL, and Ruby on Rails. 


Knowledge of Ruby on Rails was necessary in order to build and complete the model, view, and controller of the application. The application heavily relied on the MVC model in order to define essential components in the application, display information to the user, and persist data to the database.

Ruby was needed to define classes,methods, forms, string interpolation, and more. 

HTML and CSS were needed in order to design the front end of the application. 

Postgresql or knowledge of of a database was a hard skill needed to be able to create, persist, and retrieve data dfrom a database. 

In reference to soft skills, time and projectment was again essential, perhaps even more so becuase there was a heftier workload to complete. Communication was also important, especially at the beginning of the project becasue of the learning curve necessary to work with Rails. 

Problem solving was a reoccuring and necessary soft skill. Error messages are extremely common within the framework and it would would be next to impossible as well as frustrating to have to get assistance from cohort and my instructor to address each one. Utilizing google, stack overflow, and documentation to problem solve proved beneficial as it was a huge time saver and learning experience.

Changes and improvements made to similar projects of a similar nature would be to build a more solid foundation of CSS prior to the application. The Rails application two way marketplace was less of a static page and encouraged user interaction. In order to accomodate this, more styling of CSS components and use of more CSS properties were needed, especially since Javascript was not introduced. Since I was not yet strong in my CSS skills, it took a week for me to complete the front end of my application, and I was una ble to add more features due time restrictions. Having a more solid foundation of CSS would be a major improvement for future projects of a similar nature.


## 7. Explain control flow, using an example from the JavaScript programming language. 

Control flow refers to the order in which a computer executes statements. Below are examples of control examples from the Javascript programming language. 


Block statemenets are used to group statements and are commonly used in for, while, and if loops.  

Ex: 

let count = 0 
while (count < 10 ) {
    console.log (count)

prints: 0 1 2 3 4 5 6 7 8 9 



If else statement are statements which execute a logical conditon when the if is true,and if false, the else clause is executed. 
Example:
let name "Linda"

if (name) {
    console.log ("It's true")
}   else {
    console.log ("I's false")
}

prints: true

Falsy Values evaluate to fakse when 0, undefined, Nan, false, null, or is an empty string. 

Ex:
if (0) {
    console.log ("It's true)
} else {
    console.log (It's false)
}

Output: It's false



switch statement are another type of if statement that allows users to compare one value to other values. 

Ex:
let favPie = "Pumpkin"

switch
    case "blueberry":
        console.log ("You like blueberry pie.")
    case "pumpkin"
        console.log ("You love pumpkin pie.")
        break  
    default: 
        console.log ("You like some other pie.")
}

prints: You love pumpkin pie. 


Throw statement are used to throw an exception. 

Ex:
 throw { {message: "Oops! Something went wrong!"}


Try catch statments prevent a user's program from crashing 

Ex:
try {
    throw "minor error"
} catch (error) {
    console.log (error)
}

prints: minor error 


Finally block allows the program to execute code following try and catch, and is executed whether or not an error is thrown. 


Source:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling

https://developer.mozilla.org/en-US/docs/Glossary/Control_flow 

 

## 8. Explain type coercion, using examples from the JavaScript programming language 

Type coercion is the conversion of one value type to a different type. 
Some examples of this include:
Converting a string to a number.
Converting a number to a string. 
Converting a boolean to an object. 

When type coercion occurs, Javascript complier coerces one value to another.



Implicit coercion occurs when Javascript automatically  convert between different different data types. This can become problematic since the concept of truthy and falsy may not always yield a predictable result during implicit coercion.   

For example, in Javascript, (10 == "10") would print a true value although the string 10 and number 10 are technically not equal values. However, using the  "triple equals operator (====)" rather than the strict equals (==) can solve this issue. For instance, (10 === "10") would be render a false value which is expected, and more accurate. This occurs because the stricter equality operator does'nt trigger implicit type coercion, while the loose equality operator handles both type coercion and comparison. 


Explicit coercion,or type casting, is when a developer convert chooses to convert between types. Javascript has built in methods available for explicit coercion. parseInt() and parseFloat() are global methods given to convert data types to numbers, the string() global methos is used to convert data types to strings, and the Boolean() global is used to convert data types to true or false values. 



https://www.freecodecamp.org/news/js-type-coercion-explained-27ba3d9a2839/ 

https://medium.com/better-programming/implicit-and-explicit-coercion-in-javascript-b23d0cb1a750
 

## 9. Explain data types, using examples from the JavaScript programming language 



In Javascript, different data types such as 
 strings, booleans, numbers, null, and undefined are made available. 

Null is an explicit value you give to a piece of data when you want it to have no value. 
let myData = null 

Undefined is similar to null and indicates theres no value because it not been given an explicit value yet. 
By default, when we declare a variable, it has a value of undefined. 


Numbers are data types give 


https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures 

## 10. Explain how arrays can be manipulated in JavaScript, using examples from the JavaScript programming language

In Javascript, arrays are obkects 

https://www.freecodecamp.org/news/copying-stuff-in-javascript-how-to-differentiate-between-deep-and-shallow-copies-b6d8c1ef09cd/#:~:text=A%20deep%20copy%20means%20that,into%20how%20JavaScript%20stores%20values. 

 

 

## 11. Explain how objects can be manipulated in JavaScript, using examples from the JavaScript programming language 
JSON (javascript object notation ) is s way of storing and encoding data so it can be transfered back and forth 
from a web site and web server. Stringify is a useful helper method in Javascript that can take oan ne of these objects and convert it into a JSON string 
Example: JSON.stringify() 


JSON (javascript object notation ) - 
A way of storing and encoding data so it can be transfered back and forth 
from a web site and web server when we wanna transfer something like this, we would convert it into 
a string. this is called serialization- process of taking an object and converting it into a string- something thats compact and can be transfered over the internet. 

For example: 

const userJSON = {   
   
   '{
   "name:" "Linda", 
    "profession: "developer",
    isWorking: false, 
    age: 31, 
    hobbies: ("reading", "lifting")

} '

console.log(userJSON)
prints: {"name: "Linda","profession: "developer",isWorking: false, age: 31, hobbies: ("reading, "lifting"}







## 12. Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language 

 JSON can be manipulated using the Javascript helper method JSON.parse. This method takes a string and
convert it to a JS object 

For example: 

console.log(JSON.parse(userJSON) )
gives us the object back 


 https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse 

 

 

## 13. For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and clas 

 
