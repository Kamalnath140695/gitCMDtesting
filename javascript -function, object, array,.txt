console.log("Hello, World!");

var name = "kamal"
add = 5+5

console.log(name)
console.log(add)
//functions
//functions-reuseability


//create
function welcome(name,message){
  console.log("hi "+name+", welcome to my website" + message)
}
var message = "here we can learn web development"
//call
welcome('raj',message)
welcome("lavanya",message)

//objects

var personName = "kamal"
var personAge= 21
var personCity = "chennai"

function welcome(){
  console.log("welcome to my site")
}

//user defined object
var person = {
  name: 'raj',
  age: 21,
  city: "chennai",
  food: {
    fav: "briyani",
    gallery: "nuts"
  },
  welcome(){
    console.log("welcome to my site")
  }
  
}
console.log(person)

//ARRAYS --0,1,2,3,....

//BIKE
var bikecolor =["blue","orange","yellow","black"]
var bikemodel =["4541,625,2772,167"]

console.log(bikecolor)

var bike = [
  {color: "blue" , model: 541}
  {color: "red" , model: 6767}
  ]

var color = "red"

console.log(bike[0].model)

