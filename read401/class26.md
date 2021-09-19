# Read 26 : Component Based UI

## Name 5 Javascript UI Frameworks (other than React)
* 1- Angular js
* 2- Vue js
* 3- Ember js
* 4- Node js
* 5- Redux

## What’s the difference between a framework and a library?
A framework is a skeleton where the application defines the “meat” of the operation by filling out the skeleton. The skeleton still has code to link up the parts but the most important work is done by the application.

A library is essentially a set of functions that you can call, these days usually organized into classes. Each call does some work and returns control to the client.

A framework embodies some abstract design, with more behavior built in. In order to use it you need to insert your behavior into various places in the framework either by subclassing or by plugging in your own classes. The framework’s code then calls your code at these points.

## Terms


| Term                            | Defenition                  |
| :-------------                  |   :----------         |
| Rendering|Javascript uses the document object model (DOM) to manipulate the DOM elements. Rendering refers to showing the output in the browser.|
|Templates|A template is a chunk of HTML that you need to inject onto the page. Often templates are created “server side” – in that they come to the JavaScript fully formed and just need to be put into the DOM. But sometimes that isn’t feasible or would require and extra round trip to the server which might be slow. In that case having the template right in JavaScript is ideal. You can certainly just do a bit of string concatenation adding together bits of HTML and data until you have the template you need. But that likely isn’t ideal as it doesn’t separate the concerns of data and template. Real JavaScript templating can help here.|
|State| State is a plain JavaScript object used by React to represent an information about the component’s current situation.It’s managed in the component (just like any variable declared in a function). The difference is while a “normal” variable “disappears” when their function exits, the state variables are preserved by React|
