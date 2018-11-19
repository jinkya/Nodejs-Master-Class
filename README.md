
# Node js Master Class

## Section 1
Course Overview
> REST API, Web App GUI, CLI, stability, Performance

Prerequisites
> familarity with js
> You Don't Know Javascript
> [ramification floating point precision](https://stackoverflow.com/questions/11695618/dealing-with-float-precision-in-javascript)
> learn by hard way without using npm packages

Setting Up your workstation
> text editor(simple editor like sublime but IDE), Access to terminal(admin previlages), Node v8(prefer LTS)
![Node|v](https://github.com/nodejs/Release/blob/master/schedule.png)

Quizz
> loops in node js - Libuv
> Node js program run on single thread
> Node js first official non beta non io release - Version 4
> Creator of Node js - Ryan Dahl created in 2009
> Creaor of npm - Isaac Schueter
> Current owner of Node js - The Node.js Foundation
> js engines(js interpretor) - SpiderMonkey(Mozilla), Rhino(Mozilla), JavascriptCore/Nitro(Safari, iOS), Chakra(MS Edge), v8(Chrome, nodejs)

## Section 2
The story of Node js
> A video started circulating internet. Ryan Dahl San fransisco php meetup @ new way of running js on server(Fall 2011)
> Offered 2 years earlier - 2009 - standing ovation but hadenet been quite welcoming
> Ruby on rails was on hot wagon
> In Jan 2010 Isaac Schutler created npm package manager.
> GoogleTechTalks - Node.js: JavaScript on the Server - skeptical into by presentor
> Node js and Mongo readily started to work with JSON. (rise of JSON with MEAN stack)
> Joyent - official provider for the project. Microsoft collaboration created windows node js
> Rift with io js And Node js Foundation
> Many developers have all but abandoned the Node.js API, in favour of third party libraries, frameworks and NPM packages.

Whats is V8, exactly?
> V8 = The chrome v8 javascript engine.
> High level language to level language - compilers( source code to executable/ machine code/byte code), transpilers(source code of one type into source code of another type) and interpreter(source code directly execution, compile and optimizing and executing on the go)
> SpiderMonkey( first js engine ) by Mozilla and V8 by Chrome are both interchangebaly used by Mongo
> Web browsers embed js engines in order to execute js.
> Node js embeds js engine v8 to execute js

Whats node js exactly?
> server side js runtime environment
> V8 = engine | framework = nodejs | developer = driver
> C++ app embedding v8.
> Nodejs present itself as two application - 1. Script processor 2. REPL(Read Eval Print Loop)
> node index.js 				-- call the script procesor
  --- pass file name to node js | first initialize event loop then process initial part of js
  --- event loop = infinitly running loop. Nodes way of todo list
> The event loop continually checking if theres any new for nodejs to do
> Blocking - occupying the resources of thread at the expense of other todos
> web Apps requires multiple things at the same time.
> Single thread - one thing at a time - schedule things later
> non blocking ios and event loops - App design idea architecture matters...
> modules - module.exports= whatever; ||  var lib = require('./lib');
> Node module sys creates a dependency tree, which tells node which files are needed to run the application.

Anatomy of a Node Application
> Goto Anatomy of a Node Application Directory and run - node index.js

Common Node Conventions
> The package.json file - npm init
> package-lock.json - lock down the exact version of the npm dependency
> .npmrc - private cloud npm packages authentication token
> Testing and Task running - commonly held in /test directory and triggered by test runner like Mocha. Common testing files - .travis.yml, .jshintrc
> General urpose task runners often control the whole process - Grunt and Gulp being the most popular.
> Documentation and source control - git and github - .git and .gitignore - markdown formatting readme.md
> Common code comments
@Param @TODO @Author @Date
> Environments and COnfiguation 

Node.js vs Browser


## Section 3

## Section 4

## Section 5
Section Overview

Adding a CLI 
User interactions via cosole.  
CLI with an event-driven design pattern.
.
Handling Events 
Entire application startup with the specific cmd components and then booting cmd library for reading and writing to the console. 

.
Command 1: Exit 
Kill the application  
.
Command 2: Man/Help  
help support 
.
Command 3: Stats
current operating system metadata   
.
Command 4: List Users 
sys users 
.
Command 5: More User Info 
more user info -{userId}
.
Command 6: List Checks 
all the checks created by the users
list checks --up 
list checks --down 
.
Command 7: More check info  
more check info --{checkId}
.
Command 8:List Logs 
.
Command 9: More log info 
more log info --{logId}

Section Review

## Section 6

## Section 7

## Section 8

### Links
[nodejs official site](https://nodejs.org)
[npm package](https://www.npmjs.com/)

### Extras
