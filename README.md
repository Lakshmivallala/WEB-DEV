# reactjs
reactjs documentary
***Documentation in markdown syntax***

[For more markdown syntaxes](https://guides.github.com/features/mastering-markdown/)

What is Web Design ?

         Creating  a website(Static or Dynamic) based on requirement is known as Web Design.
         
What is Web Development ?

           Maintaining the website is known as Web Development(able to perform all DataBase operations).
           
Software Requirements for our project :

                                        1. Text Editor (Sublime Text, Visual studio)
                                        2. Git and Github
                                        3. Chrome
                                        4. Nodejs software
                                        
Importance of Git and Github in our project:

                Github is an distributed version control system which maintains the versions of our project.
                
Advantages of Github :

                          1. We are able to deploy our project, whenever we want able to get back to previous code by using snapshots
                          2. We can also contribute with other's project 
                          3. open source and also works as social network
                          
To create a Github Account Official url for Github

What is Git ?

              Git is a tool which manages the snapshots of or project and able to handle small or very large projects effictvely
Github uses tool Git to manage the snapshots of the project

Installation of Git tool official website for Git tool

Create a Empty Repository in Github :

                                        1. To create a repository at top-right there is a "+"  dropdown button select that button
                                        2. Select "New Repository" option
                                        3. Name your repository (Repository name should be unique)
                                        4. Make your repository as public (Anyone on the internet are able to see your repository)
                                        5. Initialize your repository with readme file (readme file is completely used for documentation)
                                        6. select option "create repository"
                                        
Readme.md file importance:


                        Readme.md file is used for documentation in Github repository by using Markdown syntax
                        
Documentation in Markdown format official url for Mastering Markdown
Commands in gitBash :

git config --global user.name "username" : This command is used to configure our username into git tool

git config --global user.mail "mailid" : This command is used to configure our mailid into git tool

pwd : This command is used to check the path (pwd stands for present working directory)

cd Desktop : This command is used to change our directory to DESKTOP.

git init : This command will initialize a git repository

Cloning a Repository from Github Account to local system :

                                                             1. We have to clone(copy) our repository to local system where we are going to perform our necessary operations to our project
                                                             2. Cloning a repository will create a folder in localsystem with same name of repository.
                                                             
How to clone a Repository :

                                1. open the repository and then select clone option
                                2. Copy the url
                                3. open the gitbash
                                4. check the path again if you are not in DESKTOP change your path to DESKTOP.
                                
Commands to clone a repository using gitBash

git clone paste the url : This commands clone a repository from github and creates a folder in our local system.

ls : This command is used to display the list of files.

cd foldername : This command is used to enter into cloned repository

mkdir css : This command is used to create a folder

mkdir image : This command is used to create a image folder

mkdir js : This command is used to create a js folder.

touch index.html : This command is used to create a index.html file.

Commands to push the changes from local folder to Github repository
git status : This command is used to check the status of the git (If the file is in red color i.e. untracked file,if the file is in green color i.e. tracked file)

git add . : This command is used to add all the files from untracking area to tracking area.

git commit -am "commitmessage : This command is used to save all the changes with a commit message

git remote : This command is used to check the remote (by default we have "origin" remote)

git push origin master : This command is used to push the changes to github repository.

Important note if we want to push the changes again(?second time) we have to fetch and pull


git status : Shows the details of the modified files.
git add <filename | .> : Add the file / files that you want to push to GitHub.
git commit -m"<message>" : Add a message for the commit.
git push : Push the commit to GitHub
         
         
         

git fetch origin : This command is used to fetch the changes to remote.(Here the default remote name is origin)

git pull origin master : This command is used to pull the repository in Github.

git push origin master : This command is used to push the chnages from localfolder to Github Repository.

Day 03:

Introduction to Html5:

                     Html5 stands for Hyper Text MarkUp language used to create web pages and the version is 5.
                     Generally web page is divided into 3 parts:
                     
                                   1. Head part(title,Navigation,Meta)
                                   2. Body part(content)
                                   3. Foot part
                                   
                     Html5 uses series of elements to display the content,these elements are enclosed with tags.
                     SYNTAX: <STARTTAG> Content </ENDTAG>
                     
Different types of Elements in Html5:

                                      1. Block-level Element 
                                          1.1 All heading tags(h1 to h6)
                                          1.2. paragraph tags(p)
                                          1.3. All Semantic Elements
                                          
                                      2. Inline Elements
                                          1.1. span tag
                                          1.2. All navigation Elements
                                          1.3. Image tag
                                          1.4. All form-controllers
                                          
                                      3. Navigation Elements(a,href)
                                         1.1. Inbound Navigation(able to navigate to the content in the same page)
                                         1.2. Outbound Navigation(able to navigate to content present in another file)
                                         1.3. mailto(used to send a mail)
                                         1.4. tel(able to call particular person)
                                         
                                      4. Semantic Elements:
                                      Semantic Elements are similar to <div> tags but it contains some description.
                                         1.1. section
                                         1.2. article
                                         1.3. aside
                                         1.4. nav
                                         1.5. header
                                         1.6. footer
                                         
CSS (Cascading Style Sheets) : Add Beautification to our web page
Syntax:

Selector{Property: value;}

Selector is used to select a tag where we want to apply styles.

Types of Selectors:

(All selectors use style attribute in the head part)

                    1. Universal Selector(*): By using Universal selector we are able to apply styles to the entire body part.
                    
                    2. Identifier Selector(#): To use identifier Selector we have to mention a id with name in the tag,identifiers are unique.
                    3. Class Selector (.): To use class Selector we have to mention class with name in the tag,we can use any number of identifiers in a single class(class mostly used in External Css)
                    4. Descendant Selector: Descendant Selector is used we are able to apply style to the tag present in the child and the child present in the parent class
                        .parent>#child(h2)
                    5. child combiner : Child combiner and Descendant Selector are same but different in the syntax only
                        .parent #child(h2)
Types of css:

                 1. Inline css : Inline css is used to apply style within a tag (without using any selector)
                 2. Internal css : Internal css is nothing but we are able to apply styles within a page.
                 3. External css 
                 
JAVASCRIPT:

         1. For dynamic behaviour of a website
         2. Called live script initially (ECMA script also, named after a European company ECMA)
         3. It is an inerpreter based language
         4. For the implementation of high end javascript modules, we need to focus on `ES-6`      
         
         DATA TYPES:
         
                  1. Number
                  2. String
                  3. Boolean
                  4. Function
                  5. Object
<<<<<<< HEAD
                  6.null
                  7.undefined                  
=======
                  6. 
                  
>>>>>>> 48912ac88ac6e89370bab4d2f1502a6d6baa2ad3

```js script
    var d=1+2+"3"
 ```
>undefined
 
         >d
         <"33"
         
         >typeof(d)
         <"string"
         
         >var e=[1,2,3,4]
         typeof(e)
         <"object"
         
         >var fa=false;
         typeof(f)
         <"boolean"
         
         >var g=function()
         {};
         typeof(g)
         <"function"
         
         >var h=/()/;
         typeof(h)
         <"object"
         
         >z=1
         typeof(z)
         <"number"
         
         >var u
         u
         <undefined
         
         >typeof(u)
         <"undefined"
         
         >var v=null;
         v
         <null
         
         > typeof(v) //null value is treated as an object
         < "object" 
         
         >var array=["Mark zed","Jack dfk","Tim","Jack Ma"];
         for(i=0;i<array.length;i++){
         console.log(array[i])
         }
         <Mark zed
         Jack dfk
         Tim
         Jack Ma
         undefined
         
         >function add(){
         var a=2;
         var b=3;
         console.log(a+b)
         }
         >add()
         <5
         
         >function subtraction(x,y){
         return x-y;
         }
         subtraction(5,3)  
         <2
         
         >num1=prompt("Enter value 1")
         num2=prompt("Enter value 2")
         typeof(num1)
         typeof(num2)
         console.log(Number(num1)+Number(num2))
         <9.5
         
         >num3=prompt("Enter the number")
         console.log(parseInt(num3)) //If you give an input pf 3.54, you will still get the output as 3
         <3 
         
         >num4=prompt("Enter")
         console.log(parseFloat(num4))
         <3.45 

Convertion functions

1. Number()
2. parseInt()
3. parseFloat()

Alerts in JavaScript

alert()
```js script
    alert("Hi");
 ```
  

    
prompt()

```javascript
    prompt("Enter your name");
```
confirm()

<<<<<<< HEAD
```javascript 
 confirm("Are you sure?");
```

Example

```javascript 
=======
 ```javascript 
 confirm("Are you sure?");
```
Example: 

  ```javascript 
>>>>>>> 48912ac88ac6e89370bab4d2f1502a6d6baa2ad3
if(confirm("Are you sure?")==true)
{ console.log("Clicked on okay"); }
else { console.log("Clicked on cancel"); }
```

<<<<<<< HEAD
### Console statements
* console.log()
```javascript
    console.log("This is for displaying an output");
```
* console.info()
```javascript
    console.info("This is also for displaying the output");
```
* console.warn()
```javascript
    console.warn("This is a warning");
```
* console.error()
```javascript
    console.error("Oops! this is error2");
```

### Functions:
* Functions without parameters (static functions):
```javascript
    // defining a function
    function add(){
        var a=1;
        var b=2;
        return a+b;
    }

    //Calling the above function
    add()
```
* Functions with parameters (Dynamic functions)
```javascript
    function multiply(x,y){
        return x*y;
    }

    multiply(2,3)
```
* Function without name (**Anonymous functions**)
```javascript
    var object=function(a,b){
        return a*b;
    }

    object(3,4)
    _______
    Output: 12
```
* Arrow functions
```javascript
    var multiply=(x,y)=>{
        return (x*y)
    }

    multiply(5,6);
    ______
    Output: 30
```

