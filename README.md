# Essentials
+UIImage
+Conditionals
-If statement is..
+For Loops
+Boolean Values
+Methods
-declaration
-parameters
-return values
-
We covered a good deal of material today.  **Essentials** will give you a quick rundown of the terms and concepts that you should be familair with going into next week.

##InterfaceBuilder##
+ **UIImageView**: UIImage view is an object from the object library that you can use for inserting an Image.  In order to insert an image, you have to put the file into your Nav folder.  

```swift
resultImage.image = UIImage(named: "sadPuppy.jpg")
```

##Methods##
A method is a concept across virtually all computer programming languages.  A method is just a set of instructions that you assign a name and likely use over and over again.  For example, if we had a method called

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
  println("You are an amazing teacher!") 
  }
else if name == "Lyel"{
  println(you are an amazing teacher!") 
  }
else {
  println("I guess you're okay too.")
}
```

We can also comapre number values:

```swift
if bank_account_total =< 0 {
  println("Sorry, you do not have any money to withdraw at the moment.")
}
```


