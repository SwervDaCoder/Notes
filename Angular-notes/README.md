# Angular

1.Install Powershell 


---
#Step1
* Ensure that you are not already in an Angular workspace folder. For example, if you have previously created the Getting Started workspace, change to the name of that folder.

* Run the CLI command ng new and provide the name angular-tour-of-heroes, as shown here:

```
ng new angular-tour-of-heroes
```

 > What this command does is prompts you for information about features to include in the initial app project. Accept the defaults by pressing the Enter or Return key 

---
#Step2

The Angular CLI installs the necessary Angular npm packages and other dependencies. This can take a few minutes.

It also creates the following workspace and starter project files:

A new workspace, with a root folder named angular-tour-of-heroes.
An initial skeleton app project, also called angular-tour-of-heroes (in the src subfolder).

An end-to-end test project (in the e2e subfolder).

Related configuration files.
The initial app project contains a simple Welcome app, ready to run. 

---
#Step3

1.cd into the workspace	
	
```
	cd angular-tour-of-heroes
```

2.Next open

```
  ng serve --open
```
 > The ng serve command builds the app, starts the development server, watches the source files, and rebuilds the app as you make changes to those files.

The new link is
http://localhost:4200/.

---

#Step 4

Open the project in visual Code and navigate to the src/app folder to make some changes to the starter app.

You'll find the implementation of the shell AppComponent distributed over three files:

1. app.component.ts— the component class code, written in TypeScript.

2. app.component.html— the component template, written in HTML.

3. app.component.css— the component's private CSS styles.

---

- Open the component class file (app.component.ts) and change the value of the title property to 'Title name'
- Open the component template file (app.component.html) and delete the default template generated by the Angular command line. Replace it with your own Html
 
- The double curly braces are Angular's interpolation binding syntax. This interpolation binding presents the component's title property value inside the HTML header tag.

**interpolations**:
 Allows you to access variables values (title = "value")

---

 > @Component is a decorator function that specifies the Angular metadata for the component
  
 > The Command line generated three metadata properties:

> 1.selector— the component's CSS element selector

 > 2.templateUrl— the location of the component's template file.
 
 >3.styleUrls— the location of the component's private CSS styles.

The ngOnInit() is a lifecycle hook. Angular calls ngOnInit() shortly after creating a component. It's a good place to put initialization logic

---
















