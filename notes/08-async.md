# Async

Create - get API
read - 
update
delete

tryCatch under get method


const response = fetch() - allows us to make requests from javascript to API's
fetch can take in URL's 
use the await keyword to slow down javascript until data comes back

map is used for array methods not objects

Pojo = plain old javascript
li - ul

Order:

env
axios
controller - class 
router update with controller/ index.html(remove auth template)
async function in controller for get api(try/catch)
Move to service next and export service for use 
service create class and get function 
always use const res = await / LOG LOG LOG res.data
use controller for page load this.''
update appstate if log worked 
update service now with appstate.res
in controller create draw item, using template and forEach and setHTML
update html with id for draw function 
use on function to call draw
remember to update with onclick and reference the app.controller to get details for the api
making the details function make sure to call the parameter you need to get those details
Swap to service and async details for api to get data (api/''/(`${parameter}`))
Now work on making the class, copy the object from the console and start making the model 
update appstate with active object 
now create a draw for the active object to draw it to the page 
update html with details, then move to model and make a template,(cut HTML made) then setHTML in controller 
Make button to save to sandbox, need post request to send it, add an onclick and make a new controller to deal with it


query selector make sure to use ?, then define key = "to whatever you need to link such as an api key"
use parameter object within the axios service: params: ApiKey
htmlBody - target body to make changes in controller 



use join() to change an array into a string to upload to sandbox







