# Infrastructure

The infrastructure layer contains things that are not necessarily tied to the core of your application. Think about something like a global state management tool like Redux, for example. Putting all the Redux config and setup files in the infrastructure layer is good because it decouples the core of your react app from any infrastructure-layer concerns. 

Also it allows you to substitute one tool for another. For example, it's much easier to change from Redux to Mobx or any other tool that serves the same purpose, since the infrastructure is loosely coupled to the application.