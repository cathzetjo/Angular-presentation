Hello everyone.  

Today we are going to talk with you about Angular.  
Let me quickly explain to you what Angular is and why you should learn it.  

**Angular is a framework** for building client applications in HTML, CSS, and either JavaScript or a language like a Typescript that compiles to JavaScript.
Typescript is more common in the Angular community because Angular itself has been written by Typescript.

Now one question that a lot of beginners have is **why do we need Angular?**

Can we not use just simple old **JavaScript or jQuery**? We certainly can. And that’s how a lot of web applications are billed.
But as our applications get more complex vanilla JavaScript or jQuery becomes **hard to maintain**. 
We need a way to properly constructure our application.
Plus, a lot of applications that build on vanilla JavaScript or jQuery are **hard to test**.

And that’s why over the past few years various frameworks have been built and evolved to make web application development easier.
Angular is the example of such framework. 

So what are the **benefits of using Angular**?
At first it gives our application a clear and loosely coupled structure that is easy to understand and easy to maintain.
It also brings in a lot of utility code that we can reuse in various applications. 
Plus, applications build with Angular are more testable so we can easily write automated test to test various part of our application.

All right. Now when you know what Angular is let me show you how it’s easy to use Angular.
What do you need to build a project on Angular?

So the first thing you need to install is the latest version of **Node**.
Node its runtime environment for executing JavaScript code outside the browser.

Then we will need an - **Angular CLI.**
It's a command line tool that we use to create a new angular project

Now we can create our first project.
So as you see this command when you create new project generates new files and folders for our project. 
And out project is successfully build.

Now we can start coding but for that of course we need a code editor.
You can use any editor which is familiar for you.

So let’s run our application and see what we got.
In the folder of our project we can use command line or we can use git bush , we write command ng serve and now we can **load our application in a web server.**
So now we have a live development server listening on localhost port 4200.
And it’s pretty you know standard (the local host) and all the time the same  but you can change it in a settings (local port) after.

So that’s our first Angular application. Easy!

Now it`s time to look at the **structure of the Angular project.**
Let's see what files and folders we have in this new project.

So the first folder we have here is the **e2e folder.** And this is where we write end to end tests for our application.
These are basically automated tests that simulate a real user.

Also we have of course **node modules** and this is where you store all the third party libraries that our application may depend upon. 

Also we have the **source folder** and this is where we have the actual source code of our application.

So we have this app folder where inside there are **module and a component.**
So every application has at least one module and one component.

We have these **assets folder** where you store the static assets of our application. 
For example, if you have any images you have to save it here.

And also we have this **environment folder** and this is where we store configuration settings for different environments. So we have one file for the production environment and the other for the development environment.

Also inside the source folder, we have an **index.html** file that contains our Angular application.
And what is interesting here?
So note here we don't have any references to a script or a stylesheet.
These references will be dynamically inserted into this page.

Also, we have the **main file** which is a typescript file and this is basically the starting point of our application.
So all you're doing here is bootstrapping the main module of our application which is in this case app module.
So angular loads this module and everything else starts from there.

Also we have this **polyfills file.** Polyfills file basically imports some scripts that are required for running Angular.
So this polyfills file is some kind of gap between the features of javascript that angular needs and the features supported by the current browsers.

Also we have **styles.css** file and this is where we add the global styles for our application and also each page or each component can have its own styles.

Also we have **test.ts** file which is basically used for setting up more testing environments    

Next we have **editorconfig.** So if you're working in a team for example you want to be sure that all developers in the team use the same settings in their editors. So this is where you store your settings.

The other file here is **TSconfig** which has a bunch of settings for your typescript compiler. So your typescript compiler looks at the settings and based on the settings is going to compile your typescript code into javascript browsers can understand.

Also we have **TSlint.jason** which includes a number of settings for TSlint.
TSlint it’s a static analysis tool for typescript code so it checks your typescript code for readability maintainability and functionality errors.

Also, we have an important file **package.jason.**
This is a standard file that every node project has.
And we have this setting here dependencies and dev dependencies 
We can see in dependencies some libraries (Angular libraries)
Of course if you don’t use animation in your project you can remove that library from your dependencies.

And the next file we have is file **conflagration for Angular**. It's a pretty standard configuration. So let’s just skip it.

And also, our Angular project already has a **git repository.** That’s cool, right?
And of course, the gitignore file is already there. And sure you may add certain files or folders for excluding them from your git repository. Everything like we did before.

So this is the basic structure of an angular project.

And now I wanna tell you some  **cool thing about Angular** – once you`ll install  it – it will be doing a lot of work by itself.
Let me show you what I mean.

Angular CLI uses this tool called a **webpack.**
It gets all our scripts and stylesheets and **combines them in a bundle** and then modifies that bundle. And this is for optimization.
More than that whenever you change one of your file webpack **automatically recompile** your application and refreshes your bundles.

All the bundles that webpack generated it also **injected** them into our index.html file.

If you will change any file and you go back to the browser without even refreshing the page you  will see **updates.**
So this is a feature of a webpack called **Hot module replacement or hot module reloading.** 
So whenever one of files (one of source files) is modified webpack **automatically refreshes your browser.**

All that functionality is included and hidden in Angular and works automatically. So you don’t have to even understand what is webpack and how it works and its cool. But if you want to configure your webpack by your own – its absolutely no problem!
You can easily **switch to a native webpack approach** with the simple one command.

And in the end I would like to give you a little bit of **history.**
AngularJS introduced in 2010 as a JavaScript framework for building client applications.
It gained popularity and the Angular team decided to rewrite the original framework using TypeScript and as a result, Anglar 2 came out in mid-2016.
This new version is entirely different from Angular 1 and you can even think that its like different framework.
After it was made some updates Angular team decided to drop the version suffix and simply call the framework Angular.
So now we have two kinds of angular.
We have **Angular JS** which is the first generation of Angular written in JavaScript and is going to die sooner or later.
And we also have **Angular** which refers to Angular 2 or later.

So left only one **Question:** Do you need a framework like Angular to build client application?
Well, no you don’t.
But **using Angular makes your life a lot easier.**

Thank you for your attention.
