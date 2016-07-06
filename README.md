## Swift for Non-Programmers Reading Guide

This reading guide provides guiding questions and resources for the first 3 weeks of material. If you are a beginner at coding or need some extra help with the basic topics, this is the guide for you! We recommended using this guide as needed. If a topic is unclear find it in this guide and read up on it using the resources. As you are reading through the sources keep the questions in mind and see if you can find the answer to them.

Instructors: This is for students who haven't coded before and need some additional help with the first 3 weeks of materials. I think this should be in the resources page and listed as an optional resources with a little blurb about how it is meant to clear up confusing topics for beginners. It can be introduced in the first class when you're describing all the resources for the course.

point out to do the questions in readings if any

##### Week 1

###### Views

An introduction to building code-less UI in Interface Builder.

- What is a view?
- [UIViews Class Reference](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIView_Class/index.html)
- What is the role of storyboards in serving iOS apps?
- [Introduction to Storyboards](https://developer.xamarin.com/guides/ios/user_interface/introduction_to_storyboards/)
- What's the difference between Springs+Struts layout method and Auto Layout?
- [Spring+Struts and Auto Layout](https://theswiftdev.com/2016/05/17/from-springs-and-struts-to-autolayout-and-anchors/)
- How do you add images to the image library and then use them in UIImagesViews?
- [Adding and Displaying Images Video](http://codewithchris.com/11-adding-and-displaying-images-in-your-app/) *

###### View Controllers

The default, built-in navigation paradigm for iOS apps.

- How is Scene/View Controller used in an iOS app?
- [Segue between Swift View Controllers](http://www.codingexplorer.com/segue-swift-view-controllers/)
- How do you add View Controllers of the same or different types to a Storyboard?
- [Storyboards Tutorial](https://www.raywenderlich.com/113388/storyboards-tutorial-in-ios-9-part-1)

###### Command Line

Command line skills give access to a multitude of developers' tools and becomes the primary way to operate source control systems like Git.

- How can we use the command line to interact with our computer?
- [How To Use Command Line](http://generalassembly.github.io/prework/cl/#/)

###### Git/Github

Source control is a fundamental skill for all professional developers.

- How do you make a clone an existing repository?
- How do you pull updates from a repository?
- How do you push a repository and a commit to github?
- [Basics of Github](http://rogerdudler.github.io/git-guide/)

###### Data Types and Values

The foundations for understanding and storing data.

- What are swifts basic data types and their properties?
- [Swift Data Types](http://www.tutorialspoint.com/swift/swift_data_types.htm)

###### Variables and Constants

Understanding how to use variables and constants allows your code to be safer and more efficient. *

- When should you use a variable and when should you use a constant?
- [Swift Variables](http://www.tutorialspoint.com/swift/swift_variables.htm)
- [Swift Constants](http://www.tutorialspoint.com/swift/swift_constants.htm)
- How do you assign new values to variables already declared and initialized?
- [Variables and Constants](https://www.raywenderlich.com/117139/swift-tutorial-variables-and-constants)

###### Control Flow

Forms the foundations for all logical "decision-making" (conditionals) and automation (loops) in code, regardless of language.

- How do if/else statements and switch/case conditionals control the flow of our program?
- How can we use for/while loops to repeat a segment of code?
- [Control Flow](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/ControlFlow.html)
- How can we use comparison operators (&lt;,&gt;,=) and boolean operators (!, &&, ||) to create comparison expressions?
    - Use the link above and skip to sections called Logical Operators and Comparison Operators

##### Week 2

###### Functions

Functions is an incredibly important foundation of programming that allow us to reuse code and break our program into steps.

- How do functions take in inputs?
- [Functions in Swift: Parameters and Return Types](http://www.codingexplorer.com/functions-swift-parameters-return-types/)
- What is function scope?
    - In the "Functions" link go to section called Nested Functions

- How can functions call and return other functions?
- [Functions](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/Functions.html)
- What is recursion?
- [Recursion](https://www.weheartswift.com/recursion/) - focus on the intro section

###### Data Structures

####### Arrays

Unlike variables, allows you to store more than one element.

- How do you build an array?
- How do you iterate through an array?
- [Arrays](https://www.weheartswift.com/arrays/)
- What's the difference between arrays and linked lists?
- [Linked Lists](https://github.com/raywenderlich/swift-algorithm-club/tree/master/Linked%20List)

####### Dictionaries

Allows you to store and organize data based on keys as opposed to index.

- What are dictionaries?
- How do you add and read values from dictionaries?
- When would we use dictionaries over arrays?
- [Dictionaries](https://www.weheartswift.com/dictionaries/)

###### Optionals

Optionals make code efficient by allowing variables to be declared with a value or 

nil.

- Why are optionals needed?
- [Learning Swift: Optional Types](http://lithium3141.com/blog/2014/06/19/learning-swift-optional-types/)
- Whats the difference between 

? and 

!?
- [When to use 

?, 

!, 

as?, 

if let and 

as](http://www.touch-code-magazine.com/swift-optionals-use-let/)

###### Classes and Objects

Classes and objects are the foundation of object-oriented programming. Subclassing is fundamental to data model design and using iOS frameworks.

- How are 

get, 

set, 

willSet, 

didSet used?
- [Swift Property Observers](http://www.codingexplorer.com/swift-property-observers/)
- How do classes and instances of classes relate?
- How do the keywords 

super and 

self contrast?
- [Inheritance](http://www.tutorialspoint.com/swift/swift_inheritance.htm)
- What is polymorphism?
- [Polymorphism and Type Casting](https://www.hackingwithswift.com/read/0/20/polymorphism-and-type-casting)

###### Object-Oriented Programming

Knowing the best practices and patterns around objects is a necessary skill for becoming a professional developer.

- What is MVC?
- [Model-View-Controller](https://developer.apple.com/library/mac/documentation/General/Conceptual/DevPedia-CocoaCore/MVC.html)
- What are delegates?
- [Guide to Swift Delegates](http://useyourloaf.com/blog/quick-guide-to-swift-delegates/)
- How do you create relationships between models?
- [Object Oriented Programming in Swift](https://www.weheartswift.com/object-oriented-programming-swift/)

###### IBOutlets/IBActions

This connects the raw Swift we've been learning to the UI we created at the beginning of the course.

- How can you you create IBOutlets and IBActions?
- [IBAction and IBOutlet](https://thatthinginswift.com/ibaction-and-iboutlet/)
- What are default methods in the UIViewController class (

awakeFromNib)?
- [awakeFromNIB](https://developer.apple.com/reference/objectivec/nsobject/1402907-awakefromnib)

##### Week 3

###### Table Views

Table views are one of the most common views deployed in iOS apps. It also demonstrates a necessary "design pattern" used in iOS implementation.

- What is the "Delegate Pattern" and how is it deployed for table views?
- [Creating a Delegate in Swift](http://stephenradford.me/creating-a-delegate-in-swift/)
- How do you create table cells with the dynamic prototype technique?
- [Create a Table View](https://developer.apple.com/library/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/Lesson7.html)

###### Passing Data

Passing data powers master/detail UI pattern. *

- What is prepareForSegue used for?
- How can you create objects from user inputs?
- How do you add multiple segues to the same target view controller and populate it depending on the segue identifier?
- [Passing Data Between ViewControllers](http://jamesleist.com/ios-swift-passing-data-between-viewcontrollers/)

###### Debugging fundamentals in Xcode

Provides familiarity with tools that enable a developer to inspect running code.

- What kinds of errors will stop app execution?
- What is a breakpoint and why is it useful?
- [Beginning iOS Development: Debugging Fundamentals](http://code.tutsplus.com/tutorials/beginning-ios-development-debugging-fundamentals--mobile-4463)
- What is a stack trace saying?
- [Tracking Tasks With Stack Traces](http://www.cocoawithlove.com/blog/2016/02/28/stack-traces-in-swift.html)

- [Status](https://status.github.com/) 
- [API](https://developer.github.com/) 
- [Training](https://training.github.com/) 
- [Shop](https://shop.github.com/) 
- [Blog](https://github.com/blog) 
- [About](https://github.com/about)
[](https://github.com/)
