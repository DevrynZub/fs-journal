# Node
bcw create - node auth
localhost 3000

Steps - 

Controller - extends(gains another class in node) + (BaseController) 
Constructor now has to be called on baseController using super('this is where the mount path should be. EX: api/cats')
Bring in the router from BaseController = this.router
.get('this is where I would add if I was going to append onto the api', ex:this.getCats)

Declare method inside of the controller 

get()takes 3 arguments ALWAYS be req , res, next
req - request 
res - send back to the user =- res.send('')
next - default error handling with tryCatch

HAVE TO RESPIN SERVER TO UPDATE/REFRESH API FOR CHANGES 

db is where you would have the database for your information. Look at this note on day2

continue using service as we have been the last couple weeks. 

debugger over console.log, can also use const request - req 
drill into the param object 

postman mocks having a client built out, will send requests out on our behalf 


express-mvc for project template 
Need workspace 

Never push up .env 

Connect => Drivers => MongoDB Code 
Database Access 

Applications => MyApp => Copy Domain, ClientID, API Audience 
update env.js with .env info


cd ..
cd folder/client 
bcw serve

check postman for API/'', look for empty array
 postman for auth, set token for bearer token, go to auth tab and select that token that was made in the variables tab, 



