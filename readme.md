# Exercise#1

# 1.) & 2.)
let numbers = [1, 2, 3, 4, 5]
console.log(numbers[0])
console.log(numbers[1])
console.log(numbers[2])
console.log(numbers[3])
console.log(numbers[4])

# 3.)
Number
String 
Undefined

# 4.)
# Example 1
const goToWork= function(day){
  if (day === 'Wednesday'){
   return true; 
  }
  else {
    return false;
  }
};
goToWork('Wednesday')

# Example 2
    onst goForRun = function(weather){
    if (weather === 'Sunny'){
    return true;
 }  
    else {
    return false;
  }
};
  
goForRun('Sunny')

# 5.)
let myArray = ['Thomas', 'Amber', 'Raoul'];
let emptyArray = [];

for (let i = 0; i < myArray.length; i++) {
  emptyArray.push( myArray[i] );
}
console.log(emptyArray, myArray);


# Exercise#2

# 1.)
“This” is the same as using “@“

# 2.)
class Person { 
  constructor(firstName, lastName){
    this.firstName = firstName
    this.lastName = lastName
  }
    greet() {
      console.log(`Hello, I am ${this.firstName} ${this.lastName}`)
    }
}

bob = new Person("Thomas", "Ochman")
bob.greet()






