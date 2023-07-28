# Vue

bcw create - vue-starter
npm -i if you fork down

adding scooped makes things within the file only pertain to that file otherwise it applies to everything 
no more bcw server

vue does not require you to respin server
Snipet will have what base template I need for my pages in vue 
{{ this is how to access JS within my HTML while in vue}}

setup - private functions
return - public functions 

v-on: then add whatever function you want to call, vues way of handeling onclick 
v-on:click
v-if= "variable > 0" conditional to only render the span or p if it is greater then 0

Logger.log instead of console.log

variable: computed(() => {return.Appstate.Variable})
return is only necessary if you are returning more then 1 object otherwise you wont need return 
Basically this is a function 

computed is basically get
Services have not changes, you still export a singleton

v-for = "variable in variable" :key= "" (property binding) or @click or whatever you need in-place of v-for
will want a key to tract a specific part of the v-for


write an axios server to talk to api
lifecycle hooks
onmount and onUnmounted to mount the controller 
setup as export default to start getting API using try catch



