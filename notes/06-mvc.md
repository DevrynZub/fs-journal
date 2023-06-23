# MVC
module - broken up into smaller parts

method is a function written inside of a object
method is basically a function 
services are the only thing that can change models,
models are stores in the app state
constructor - new homeController ()runs a new controller inside the constructor 
controllers made available to all other code, use EXPORT 
export class "match to file name" {
  constructor(){
    lOG LOG LOG 
  }



}
underscore is for private things, not accessible to the user
getters must return a value! MUST return
getters do not take any parameters
CTRL + . to declare a fix

Priority -
  AppState - Data/Variables
  controller - user controlled (button)


  Appstate.on(event to call to the appstate to change anything wiht the appstate which causes the controller to update the page)

  for the listener to do something by using EMIT, appstate.emit

  local storage = 