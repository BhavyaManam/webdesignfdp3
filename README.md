# webdesignfdp3
This repository created for webdesign using reactjs fdp3


#  Web Design Using React Js


# Day Wise -01 

[Recording video1](https://drive.google.com/file/d/1IBYXYrlL1QKIwrKupau_yzcE21hppRRH/view?usp=sharing)

[Recording video2](https://drive.google.com/file/d/1xH7E7IWtss6nrPshQ6ERX0a-YC4yU9vk/view?usp=sharing)

### Day 01


#### What is Web Design ?
             Creating  a website(Static or Dynamic) based on requirement is known as Web Design.

#### What is Web Development ?
               Maintaining the website is known as Web Development(able to perform all DataBase operations).

#### Software Requirements for our project :
                                            1. Text Editor (Sublime Text, Visual studio)
                                            2. Git and Github
                                            3. Chrome
                                            4. Nodejs software


#### Importance of Git and Github in our project:
                    Github is an distributed version control system which maintains the versions of our project.

  ##### Advantages of Github :
                              1. We are able to deploy our project, whenever we want able to get back to previous code by using snapshots
                              2. We can also contribute with other's project 
                              3. open source and also works as social network

 **To create a Github Account** [Official url for Github](https://github.com/)

 #### What is Git ?

                  Git is a tool which manages the snapshots of or project and able to handle small or very large projects effictvely

 **Github uses tool Git to manage the snapshots of the project**


 ##### Installation of Git tool [official website for Git tool](https://git-scm.com/)


 ##### Create a Empty Repository in Github :
                                            1. To create a repository at top-right there is a "+"  dropdown button select that button
                                            2. Select "New Repository" option
                                            3. Name your repository (Repository name should be unique)
                                            4. Make your repository as public (Anyone on the internet are able to see your repository)
                                            5. Initialize your repository with readme file (readme file is completely used for documentation)
                                            6. select option "create repository"

**Readme.md file importance**: 

                            Readme.md file is used for documentation in Github repository by using Markdown syntax


#### Documentation in Markdown format [official url for Mastering Markdown](https://guides.github.com/features/mastering-markdown/)


## Commands in gitBash :

**git config --global user.name "username"** :  This command is used to configure our username into git tool

**git config --global user.mail "mailid"**   :  This command is used to configure our mailid into git tool

**pwd** : This command is used to check the path (pwd stands for present working directory)

**cd Desktop** : This command is used to change our directory to DESKTOP.

**git init** : This command will initialize a git repository 


##### Cloning a Repository from Github Account to local system :


                                                                 1. We have to clone(copy) our repository to local system where we are going to perform our necessary operations to our project
                                                                 2. Cloning a repository will create a folder in localsystem with same name of repository.


  #### How to clone a Repository : 

                                    1. open the repository and then select clone option
                                    2. Copy the url
                                    3. open the gitbash
                                    4. check the path again if you are not in DESKTOP change your path to DESKTOP.



 ### Commands to clone a repository using gitBash


 **git clone paste the url** : This commands clone a repository from github and creates a folder in our local system.

 **ls** : This command is used to display the list of files.

**cd foldername** : This command is used to enter into cloned repository

**mkdir css** : This command is used to create a folder

**mkdir image** : This command is used to create a image folder

**mkdir js** : This command is used to create a js folder.

**touch index.html** : This command is used to create a index.html file.


### Commands to push the changes from local folder to Github repository 


**git status** : This command is used to check the status of the git (If the file is in red color i.e. untracked file,if the file is in green color i.e. tracked file)

**git add .** : This command is used to add all the files from untracking area to tracking area.

**git commit -am "commitmessage** : This command is used to save all the changes with a commit message

**git remote** : This command is used to check the remote (by default we have "origin" remote)

**git push origin master** : This command is used to push the changes to github repository.

**Important note if we want to push the changes again(?second time) we have to fetch and pull**


**git fetch origin** : This command is used to fetch the changes to remote.(Here the default remote name is origin)

**git pull origin master** : This command is used to pull the repository in Github.

**git push origin master** : This command is used to push the chnages from localfolder to Github Repository.


## Day 02:

[Recording video1](https://drive.google.com/file/d/1JKIAniL8YkqcFCH88nyPCMC1c33mO8zA/view?usp=sharing)

[Recording video2](https://drive.google.com/file/d/1Uc90YyfhbwzpaEFN7sD8soM_zjymo7if/view?usp=sharing)

## Introduction to Html5:

                         Html5 stands for Hyper Text MarkUp language used to create web pages and the version is 5.
                         Generally web page is divided into 3 parts:
                                       1. Head part(title,Navigation,Meta)
                                       2. Body part(content)
                                       3. Foot part
                         Html5 uses series of elements to display the content,these elements are enclosed with tags.
                         SYNTAX: <STARTTAG> Content </ENDTAG>
                         


#### Different types of Elements in Html5:
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
                                         
## Day 03

[Recording Videos](https://transcripts.gotomeeting.com/#/s/ee9f7acf0398ebbeeedae97c307f29bb669e3f63b576daf4150427d699dbd329)

## CSS (Cascading Style Sheets) : Add Beautification to our web page
Syntax: Selector{Property: value;}

Selector is used to select a tag where we want to apply styles.

### Types of Selectors:(All selectors use style attribute in the head part)

                        1. Universal Selector(*): By using Universal selector we are able to apply styles to the entire body part.
                        
                        2. Identifier Selector(#): To use identifier Selector we have to mention a id with name in the tag,identifiers are unique.
                        3. Class Selector (.): To use class Selector we have to mention class with name in the tag,we can use any number of identifiers in a single class(class mostly used in External Css)
                        4. Descendant Selector: Descendant Selector is used we are able to apply style to the tag present in the child and the child present in the parent class
                            .parent>#child(h2)
                        5. child combiner : Child combiner and Descendant Selector are same but different in the syntax only
                            .parent #child(h2)
                        
 ### Types of css:
                     1. Inline css : Inline css is used to apply style within a tag (without using any selector)
                     2. Internal css : Internal css is nothing but we are able to apply styles within a page.
                     3. External css : External css file is nothing but where we can give styles in another file and we are able to apply those styles into our file
                     
                     
                     
## Day 04:

## [Recording Video](https://transcripts.gotomeeting.com/#/s/4b7f38428b080052005b62799197d20c60de55734807a1f596fc82c3ccf49775)



#### Created a Responsive profile using Flex box and metatag,media Queries

##### Posted responsive profile in GitHub Pages



## Day 05 & Day 06 :
[Recording Video](https://drive.google.com/file/d/1DrXN-NwPcmDceWhPAGEABNyFlu75D7F-/view?usp=sharing,%20https://drive.google.com/file/d/1a84lq8wZ0zZ66JkcVTRLDX2bymxsvsJ8/view?usp=sharing)

### Tables
*  `.table`   =>  Layout for table
*  `.table-dark`
*  `.table-bordered` 
*  `.table-borderless` 
*  `.thead-dark`
*  `.thead-light`
*  `.table-striped`
*  `.table-hover`

#### Attributes for table
*   `colspan`
*   `rowspan`
*   `scope="col|group|colgroup|rowgroup"`
#### Table-responsive-{breakpoint}
*   `.table-responsive`
*   `.table-responsive-sm`
*   `.table-responsive-md`
*   `.table-responsive-lg`

Example:
```
	<!DOCTYPE html>
<html>
<head>
	<title>:: Bootstrap Tables ::</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<meta name="viewport" content="width=device-width,initial-scale=1">
</head>
<body>
	<div class="container mt-5">
		<div class="table-responsive-md">
			<table class="table  table-bordered  ">
	<thead class="thead-dark">
		<tr class="bg-primary">
			<th scope="col">S.No</th>
			<th>Continent</th>
			<th>First_Name</th>
			<th>Last_Name</th>
			<th>Age</th>
			<th colspan="2">Actions</th>
			
		</tr>
	</thead>
	<tbody>
		<tr>
			<td scope="row">1</td>
			<td rowspan="2">Non Asia</td>
			<td>Warren</td>
			<td>Buffet</td>
			<td>69</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
		<tr>
			<td>2</td>
			<td>Jeff</td>
			<td>Bezzos</td>
			<td>65</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
		<tr >
			<td>3</td>
			<td>Asia</td>
			<td >Mukesh</td>
			<td>Ambani</td>
			<td>60</td>
			<td>Edit</td>
			<td>Delete</td>
		</tr>
	</tbody>
	
    </table>
		</div>
</div>
</body>
</html>
```
### Cards

*  `.card`
*  `.card-header`
*  `.card-body`
*  `.card-footer`
*  `.card-img-top`
*  `.card-title`
*  `.card-subtitle`
*  `.card-text`
*  `.card-link`
*  `.card-group`
*  `.card-deck`

Example:
```
	<!DOCTYPE html>
<html>
<head>
	<title>:: Profile card ::</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<meta name="viewport" content="width=device-width,initial-scale=1">
</head>
<body>
<div class="container mt-5">
	<div class="card-deck">
	<div class="card" style="width:18rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	<div class="card" style="width:20rem;border: 1px solid lightgray;">
		<img  class="card-img-top" src="images/admin.png">
		<div class="card-body">
			<h1 class="card-title">Kalyan Chakravarthi</h1>
		<h3 class="card-subtitle">Software Developer</h3>
		<p class="card-text">Working in APSSDC</p>
		<button class="btn btn-primary"><a href="table.html" class="text-white">Click Me</a></button>
		</div>
	</div>
	</div>
</div>
</body>
</html>
```





## Day 06
[Recording video](https://transcripts.gotomeeting.com/#/s/da25761785c2f6ca343ee1f7f235854f7dc4e9204f6c105408cac3a55ba5d710)
## JS

###  History of JavaScript
* For implementing the dynamic behaviour of a web site.
* It was called as `live script` in initial stages.
* `Brendan Eich` (Netscape navigator) was introduced this `JavaScript`.(`September 1995`)
* `JavaScript` is an interpreter language.
* He tiedup with ECMA (Ecma Scrpt) - ECMA SCRIPT - 262 (`ES-262`)
* ECMA SCRIPT -2018 is the latest version (`ES-9`)
* For implementing high end JS modules, We've to focus on `ES-6`.

### Data types
* Number
* String
* Boolean
* Function
* Object
* null
* undefined

### Convertion functions
* Number()
* parseInt()
* parseFloat()

### Alerts in JavaScript
* alert()
  ```javascript
      alert("Hi");
  ```
* prompt()
  ```javascript
      prompt("Enter your name");
  ```
* confirm()
  ```javascript
    confirm("Are you sure?");
  ```
  Example:
   ```javascript
        if(confirm("Are you sure?")==true){
	        console.log("Clicked on okay");
        } else {
	        console.log("Clicked on cancel");
        }
   ```
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

### Array iteration using map,for-in and for-of
* **Map()**
	* Syntax:
```javascript
	arrayName.map({arrow function})
```

* Example
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	// iter holds the values and index holds the index values of an array
	names.map((iter,index)=>{
		console.log(iter);
		console.log(index);
	})
```

* for-in
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	for(i in names){
		console.log(i);
	}
```
	
* for-of
	
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	for(i of names){
		console.log(i);
	}
```
### Document Object Model (DOM):
* We can implement JavaScript code any where in html document.
* We've to use script tags for taht (`<script> </script>`)
* By using `document` keyword, We can manipulate the data in html document.
* Document object model functions are:
```javascript
		document.getElementById("id");
```

* Collections
```javascript
		document.getElementsByClassName("className");
		document.getElementsByTagName("Tag name");
```

* Common statements for DOM
```javascript
		document.querySelector("#selector | .selector | Tag Name Selector");
		document.querySelectorAll(".selector | Tag Name Selector");
```
### innerHTML
`innerHTML` triggers the information exist with in the tags.
Example:
```html
	<div id="second">
		Sample division
	</div>
```
```javascript
	var second=document.getElementById("second").innerHTML;
	console.log(second);
	____
	Output: Sample division
```

**Writing information into divisions using `innerHTML`**
```javascript
	document.getElementById("second").innerHTML="Hello everyone";
```

**Creating and appending HTML attributes**
We can create the html attributes by using javascript code part also. For that we need to use `document.createElement`. And we can append the information into the created elements by using `textContent`.

Syntax:
```javascript
	document.createElement("html tagname")
```

Example:
```javascript
	//Selecting a section from html;
	var secondDiv=document.getElementById("second");
	
	// Creating a html attribute
	var heading2=document.createElement("h2");
	heading2.textContent="heading";
	
	//Appending child attribute to parent
	secondDiv.appendChild(heading2);
```


## JS

###  History of JavaScript
* For implementing the dynamic behaviour of a web site.
* It was called as `live script` in initial stages.
* `Brendan Eich` (Netscape navigator) was introduced this `JavaScript`.(`September 1995`)
* `JavaScript` is an interpreter language.
* He tiedup with ECMA (Ecma Scrpt) - ECMA SCRIPT - 262 (`ES-262`)
* ECMA SCRIPT -2018 is the latest version (`ES-9`)
* For implementing high end JS modules, We've to focus on `ES-6`.

### Data types
* Number
* String
* Boolean
* Function
* Object
* null
* undefined

### Convertion functions
* Number()
* parseInt()
* parseFloat()

### Alerts in JavaScript
* alert()
  ```javascript
      alert("Hi");
  ```
* prompt()
  ```javascript
      prompt("Enter your name");
  ```
* confirm()
  ```javascript
    confirm("Are you sure?");
  ```
  Example:
   ```javascript
        if(confirm("Are you sure?")==true){
	        console.log("Clicked on okay");
        } else {
	        console.log("Clicked on cancel");
        }
   ```
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

### Array iteration using map,for-in and for-of
* **Map()**
	* Syntax:
```javascript
	arrayName.map({arrow function})
```

* Example
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	// iter holds the values and index holds the index values of an array
	names.map((iter,index)=>{
		console.log(iter);
		console.log(index);
	})
```

* for-in
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	for(i in names){
		console.log(i);
	}
```
	
* for-of
	
```javascript
	var names=["mark zukerburg","Jack dorsey","Tim","Jack ma"];
	for(i of names){
		console.log(i);
	}
```
### Document Object Model (DOM):
* We can implement JavaScript code any where in html document.
* We've to use script tags for taht (`<script> </script>`)
* By using `document` keyword, We can manipulate the data in html document.
* Document object model functions are:
```javascript
		document.getElementById("id");
```

* Collections
```javascript
		document.getElementsByClassName("className");
		document.getElementsByTagName("Tag name");
```

* Common statements for DOM
```javascript
		document.querySelector("#selector | .selector | Tag Name Selector");
		document.querySelectorAll(".selector | Tag Name Selector");
```
### innerHTML
`innerHTML` triggers the information exist with in the tags.
Example:
```html
	<div id="second">
		Sample division
	</div>
```
```javascript
	var second=document.getElementById("second").innerHTML;
	console.log(second);
	____
	Output: Sample division
```

**Writing information into divisions using `innerHTML`**
```javascript
	document.getElementById("second").innerHTML="Hello everyone";
```

**Creating and appending HTML attributes**
We can create the html attributes by using javascript code part also. For that we need to use `document.createElement`. And we can append the information into the created elements by using `textContent`.

Syntax:
```javascript
	document.createElement("html tagname")
```

Example:
```javascript
	//Selecting a section from html;
	var secondDiv=document.getElementById("second");
	
	// Creating a html attribute
	var heading2=document.createElement("h2");
	heading2.textContent="heading";
	
	//Appending child attribute to parent
	secondDiv.appendChild(heading2);
```

### Objects in Javascript
**O**bject is nothing but its a key,value pair. When we going to get the value from an object, we've to use the key of that object

Example:
```javascript
	var student={
		name:"Hemanth sai",
		role:"Student",
		branch:"CSE:
	}
	__________
	student.name => Hemanth sai
```
Arrays in the object:
```javascript
	var student={
		friends:["sai vasanth","savya sree", "nitesh bharti","venkatesh"]
	}
	_____
	// Here `0` is the index value
	student.friends[0]
	______
	Output: sai vasanth
	
	_____
	student.friends[student.friends.length-1]
	____
	Output: Venkatesh
```

Objects in Object:
```javascript
	var student={
		student1:{
			name:"Swetha"
		},
		student2:{
			name:"venkatesh"
		}
	}
	______
	student.student1.name
	_____
	Output: Swetha
```

### JSON
* **J**ava **S**cript **O**bject **N**otation
* Light weight data-interchange format (This is a format to trnsfer information between the nodes)
* This is very easy to read,understand and write.
* This is very easy for the machines to parse and generate data.
* This is subset of `javascript programming language standards (ECMA SCRIPT - 262)`.
* For accessing JSON data from a HTML document, we need to use a server.
	* npm server
	* web server for chrome (`200 OK`)
		* Web server for chrome is a static server invented google team. This allows us to access any information from external file into a HTML document.
		* **Installation of `200 OK`**
			* _Type **web server for chrome** in your chrome browser_ and press Enter.
			* _We have to choose web server for chrome from chrome.google.com from listing_.
			* _We have to click on add to chrome button. Soon after we will see a dialogue box and then click on add app_.

### Promises:
A promise is an object that may produce a single value some time in the future. The client and the server communicating with eachother, client need to send a request to the server, the server need to respond to the client request simultaniously. This promise give us a value that the is resolved or not resolved.
The states for the promise are
* Fulfilled
* Rejected
* Pending

The promise is a chine relation, We can build multiple coding blocks.
The syntax:
```javascript
	promise(request).then(response=>{
		return response;
	})
```

Promises examples:
* Fetch
* Cache

Example:
```javascript
	fetch('data.json').then(response=>{
		return response.json();
	}).then(data=>{
		console.log(data);
	})
```
The promioses concept is the replacement for XMLHttpRequest. The XMLHttpRequest provides a way to communicate with client and server


## React
### Features of React
* Its a library
* Virtual DOM : _Its enable us to build scalable and fast applications_.
* JSX
* Components
	* Functional Components (Stateless component)
	* Class Component (Statefull component)
	* Pure components
	* Higher Order Components (HOC's)
* One way data binding

### States and props in React
**S**tate provides an ability to store information in the components. With in class component only we can use the state concept. We've to use the constructor method as well as the super method for initializing the state as we need information from the base class. By using `this.state` we can initialize a state. The state should be in object format. 

Syntax:
```javascript
	constructor(){
    		super();
    		this.state={
      		name:"Hanuman"
    		}
  	}
```

We can implement the state concept in class component only.

#### But how we are going to implement the state functionality in a functional component ?
We can implement this by using the concepts called **Hooks**.
**H**ooks are new feature introduced in React 16.8 version. It allows us to use states and other React features without writing the class. We can implement the hooks in functional components.

Example:
	**useState**
	This is for implementing the states concept in functional components.
	
Syntax
```javascript
	// Importing useState functionality from the base class
	import React,{useState} from 'react';

	let StatesInFunction=()=>{
		// Here count is for initializing the value and setCount is for manipulating the initialized value
    		const [count,setCount]=useState("Bye");
    		return(
        		<div>
				<h2 
					onMouseOver={()=>setCount("Hi")}
					onMouseLeave={()=>setCount("Bye")}> {count} 
				</h2>
        		</div>
    			)
		}

	export default StatesInFunction;
```


Example II :
```javascript
	import React,{useState} from 'react';

	let StatesInFunction=()=>{
    		let initialValue=0;
    		let [count,setCount]=useState(initialValue);
    		return(
        	  <div>
            		<h2> {count} </h2>
            		<button onClick={()=>{setCount(count-=-1)}}> Increment </button>
            		<button onClick={()=>{setCount(count-=1)}}> Decrement </button>
            		<button onClick={()=>{setCount(count=initialValue)}}> Initial </button>
        	  </div>
    		)
	}

	export default StatesInFunction;
```

### Props in React
+ **P**rops is a special keyword in React which is used for passing the data from one component to another component.
+ It is uni-directional
+ props data is read-only, which means the data coming from the parent component should not be changed by child components.
+ Props are arguments passed among React components.

Example: (Passing properties (`props`) from class component to a functional component)
App.js
```javascript
	import React,{Component} from 'react';
	import './App.css';
	import StatesInFunction from './StatesInFunction';
	
	class App extends Component{
  	
	render(){
        return (
    		<div className="App"> 
			// Props	
      			<StatesInFunction name="Nitesh" age="20 years"/>

    		</div>
    		)
  	   }
	}


export default App;
```
StatesInFunction.js
```javascript
	import React from 'react';

	let StatesInFunction=(props)=>{
    		return(
        		<div>
            			<h2> {props.name} is {props.age} </h2>
            			<h2> {count} </h2>
        		</div>
    		)
	}

	export default StatesInFunction;
```
#### But how we are going to access the props in class components
Here we go with that
```javascript
	import React from 'react';

	export default class StatesInFunction extends React.Component{
    		render(){
        		return(
            			<div>
                			<h2> {this.props.name} is {this.props.age} old. </h2>
            			</div>
        		)
    		}
	}
```
### Routing in React (react-router-dom)
`npm install react-router-dom --save`

#### Primary components of React-route-dom:
* BrowserRouter
	
	Is usefull for initializing the navigation context. This is the parent component of `react-router-dom`
	
```javascript
		<BrowserRouter>
		</BrowserRoputer>
```
* Route
	
	Is for specifying the path.
	
```javascript
		<Route exact path="/about" component={About}>
		</Route>
```

```javascript
		<BrowserRouter>
			<Route exact path="/about" component={About} />
		</BrowserRouter>
```
* Link

	This is for providing event that calls to the path specified in the path of route component.
	
```javascript
		<Link to="/about"> Click me </Link>
		// <a href="/about"> Click me </a>
```

Example:

```javascript
	<BrowserRouter>
		<Route path="/about" component={About}/> 
	<BrowserRouter>
	
	<Link to="/about" />
```

Most of the web developers or web designers uses the link attribute (`<a> </a>`) to pass the data from one page to another page.

In react we are using the `<Link> </Link>` attribute instead of anchor tag (`<a> </a>`).

#### But how we are going to pass data from one component to another component using `<Link />` ?

For this we have to pass the parameters in the format of object as shown below.

```javascript
	<Link to={{pathname:"/resume", data:{id:index}}} className="button"> View profile </Link>
```

* Here the `pathname` specifies the url we are going to navigate.
* `data` represents the information which we are passing. Here `id` is the key and the `index` is the value.

If you wanna access that information in destination component, we've to use the `location` keyword.

```javascript
	import React from 'react';
	import {profiles} from './data.json';
	import './App.css';

	let Resume=(props)=>{
    	var info=profiles[props.location.data.id];
    	return(
        	<section className="parent"> 
            		<article className="basicsCard"> 
                		<h2> {info.basics.name} </h2>
            		</article>
        	</section>
    		)
	}

	export default Resume;
```

## Node JS
### node with mysql
Installing mysql

`npm install mysql`

#### COnnecting with mysql

```javascript
	var mysql = require('mysql');

	// mysql connection
	var connection=mysql.createConnection({
		host:"localhost",
		user:"root",
		password:""
	});
	
	connection.connect(err=>{
		if err throw err
		console.log("Connected to mysql");
	})
```

#### Creating a database
```javascript
	connection.connect(err=>{
	if (err) throw err;
	console.log("Connected to mysql");
	connection.query("CREATE DATABASE node-info", (err,result)=>{
		if(err) throw err;
		console.log(result);
		})
	})
```

#### Creating a table
```javascript
	var connection=mysql.createConnection({
		host:"localhost",
		user:"root",
		password:"",
		**database**:"node_info"
	});

	connection.connect(err=>{
		if (err) throw err;
		console.log("Connected to mysql");
		connection.query("CREATE TABLE employee (name varchar(20), emaild varchar(50), mobile varchar(20))", 			(err,result)=>{
			if(err) throw err;
			console.log("Table created");
		})
	})
```

#### Inserting Data
```javascript
	connection.connect(err=>{
	if (err) throw err;
	console.log("Connected to mysql");
	connection.query("INSERT INTO employee (name,emaild,mobile) VALUES ('Hemanth','hemanth@gmail.com','9888786858')", 		(err,result)=>{
		if(err) throw err;
		console.log("Table created");
		})
	})
## 28-07-2020
[Recording Video](https://transcripts.gotomeeting.com/#/s/bf9ab41da18cd47e2a6a538ca645e07c36958d0a977be73fa6c0649fde4ca061)

## 29-07-20
[Recording Video](https://transcripts.gotomeeting.com/#/s/13328374375f0e28366e1193d7d175252908f0c5809f229db6debe44ec403a9c)

## 30-07-2020
[Recording Video](https://transcripts.gotomeeting.com/#/s/04540eba365cd34228d444c0fab34975c6f64e16a17ba0c7a2107d878d5e168d)

## 31-07-2020
[Recording Video](https://transcripts.gotomeeting.com/#/s/cb2cc0b15057186f3e1d66b33058acd23f86aa13616f180d29f41fa6a6ac03ea)

## 1-08-2020
[Recording Video](https://transcripts.gotomeeting.com/#/s/5951cccaf3ed849c4594e0fff5947f1b62578f2cd471a09cfdb1d5ff337e8e59)






