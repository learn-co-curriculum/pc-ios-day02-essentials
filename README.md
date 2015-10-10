# Essentials

We covered a good deal of material today.  **Essentials** will give you a quick rundown of the terms and concepts that you should be familair with going into next week.

##InterfaceBuilder##
+ **UIImageView**: UIImage view is an object from the object library that you can use for inserting an Image.  In order to insert an image, you have to put the file into your Nav folder.  

```swift
resultImage.image = UIImage(named: "sadPuppy.jpg")
```

##Methods##
A method is a concept that exists across virtually all computer programming languages.  A method is just a set of instructions that you assign a name and likely use over and over again.  For example, if we had a method called

```swift
func brush_your_teeth()
```

What you're actually saying is:

1. Go to the bathroom

2. Pick up your toothbrush

3. Wet your toothbrush

4. Pick up your toothpaste

5. Squeeze toothpaste tube onto your toothbrush

6. Lift your arm...

7. And so on...  

But when your mother tells you to go brush your teeth, does she say all of those steps?  Of course not! She merely tells you to call the brush_your_teeth() function.  Notice how 

1) *Each of those steps could be methods themselves* and 

2) *How much more efficiently we can write our code with methods.*

**How to write methods**
We define the function with the ```func``` keyword, the name of the function, its parameters, and return values (if there are return values).  For example:

```swift
func sayHey(name:String) -> String{
  salutation = "Hey \(name)!  We are so happy that you're here!"
  return salutation
}
```

In this case, "say_hey" is the name of the function, "name" is a parameter of type *String*, and the function will return a String.

**Return Values**
+ Every method that we write gives us something called a return value - this is what Swift evaluates for us and gives us back to use in other parts of our program. The return value of our methods is the last line evaluated. 
+ What would the return value of these methods be?
	```swift
	func helloWorld() {
		"Hello World"
	} 
	// returns "Hello World"

	func onePlusOne() -> int {
		1 + 1 
	} 
	
	// returns 2 
	```
+ A return value is always going to be the result of the last line of code in a method. So what's the return value of the following method:

```swift
 func goHome() -> String { 
	"Close your computer"
	"Put it in your bag"
	"Stand up"
	"Walk out the door" 
	"Go to your house"
}
```


This method returns `Go to your house`.
 

**Parameters**
- Functions are not requireed to use parameters. 
- Functions still require a ```()``` whether there are paramters or not.
- Parameters are also called *arguments*.  A parameter is information that a method uses in
- Functions can have multiple parameters

```swift
func deliver(contents:String, recipient:String){
  }
```
  
  
##Conditionals##
+ Conditionals are also known as *if statements*.  Conditionals are one of the foundational logic structures that computers use to make decisions.  You use conditionals all the time.  For example:

```swift
if its_snowing_outside {
  wear gollashes 
  }
else {
  wear flipflops
  }
```

+ Often, when we are using conditionals, we'll need to compare two values.  In order to do this in Swift, we need to make sure that the two things that we are comparing are the same type.  For example,

```swift
if name == "Dan" {
  print("You are an amazing teacher!") 
  }
else if name == "Lyel"{
  print("You are an amazing teacher!") 
  }
else {
  print("I guess you're okay too.")
}
```

We can also comapre number values:

```swift
if bank_account_total =< 0 {
  print("Sorry, you do not have any money to withdraw at the moment.")
}
```

##Loops##
##Booleans##
