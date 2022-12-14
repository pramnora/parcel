# parcel
parcel

I was at...  
- https://codesandbox.io/s/upbeat-bush-0s28yx  
...attempting to create a first sandbox...when I came across a message stating...

>> We use the same configuration as Parcel to bundle this sandbox, you can find more
  info about Parcel 
  <a href="https://parceljs.org" target="_blank" rel="noopener noreferrer">here</a>.  

...here, meaning...    

- https://parceljs.org  

...when I went over there...I read what the introductory web page said...  

>
The zero configuration build tool for the web.JavaScript.CSS.HTML.TypeScript.React.images.SASS.SVG.Vue.libraries.Less.CoffeeScript.Node.Stylus.Pug.Electron.Elm.WebGL.extensions.GraphQL.MDX.XML.
Parcel combines a great out-of-the-box development experience with a scalable architecture that can take your project from just getting started to massive production application.
<  

...and, clicked on the link which said: [get started]  

...this, in turn, led me to...  
- https://parceljs.org/docs/  
...where I clicked on one of the links I saw at the top of the page...which stated:  

Building a webapp with Parcel  
Learn how to set up a new web   
application from scratch with Parcel  

- https://parceljs.org/getting-started/webapp/  
...there I saw instructions on how to use parcel to build a web page...;    
that runs inside of the web browser on:  
- http://localhost/1234  

-----

The instructions are detailed...so, you have to read through them very carefully...in order to go follow the tutorial along.  

-(To tell you the truth, when I first tried installing and running Parcel, I found it didn't work?! So, I used npm to uninstall...; then, re-install...; then, called: npx/-etc.; to go cut a long story short...eventually, I got a web page up and working inside of my web browser: http://localhost:1234. So, these instructions are just to save having the same headaches next time I try using it.)-  

Basically, you are meant to create a CLI/Client side Interface application...; this means you should already have Node installed/Node comes with NPM/Node Package Manager...that can be used to install all sorts of other software packages...it can be downloaded for FREE from:   
- https://nodejs.org  
...next, create a folder...call it:   
my-project    
...inside of the [my-project] folder...open up a Windows Command Prompt...; and, type in the command:     

>> C:\npm install --save-dev Parcel    

...this loads in the Parcel packages onto your computer system.     

-----

Inside of the [my-project] folder...create a sub-folder called:     
src   
...inside of the: [src] folder...you create 3 x test web page files, as follows:  

- index.html  
- styles.css
- app.js  

...the main [index.html] web page file...links to both external files: [styles.css]/[app.js].      

-(**NOTE**: The web page codes for: index.html/styles.css/app.js...are all found at:   

- https://parceljs.org/getting-started/webapp/    

...so, you don't need to type in any codes...; but, instead, just simply use 'copy and paste'...; then, 'save' each file using it's different filename/extension.)-       

-----

Now, go up a folder...back into: [my-project] which contains all the rest of your files.  

And, here you create a file called:    
package.json  
...inside of package.json goes the following code...  

>>{  
>> "name":"my-project",  
>> "source":"src/index.html",  
>> "scripts":{  
>>  "start":"parcel",  
>>  "build":"parcel build"  
>> },  
>> "devDependencies":{  
>>  "parcel":"latest"  
>> }  
>>}    

Next,  open up a Windows Command Prompt inside of the [my-project] main folder...and, type in the following command:

>> npm run build  

...this should create a new sub-folder to go inside of your main folder: [my-project], which is called:  

dist  

Open up a Windows Command Prompt inside of the [my-project] main folder...and, type in the following command:

>> npx parcel src/index.html  
 
...the response should say...   

>> Server running at: http://localhost:1234    

...and, when you open up a new web browser window...and, type into the address bar:  

http://localhost:1234    

...you should see the web page up and working.  

-----

## NOTES

**NOTE(1)**: My current computer/operating system is: Desktop PC/Windows 10 Pro...; so, I'm none too sure if these same instructions would work for any other computing platforms/operating systems.  

**NOTE(2)**: There were many more instructions to go and follow through...; you will see these whenever you return back to what is the main instruction page...    

- https://parceljs.org/getting-started/webapp/    

However, the instructions here...are merely just to get you up and *started*. -Enjoy! ;-)









