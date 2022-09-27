

https://www.udemy.com/course/complete-ios-bootcamp/

## The very basic

### Introduction
![](assets/Pasted%20image%2020220927170857.png)

### Hardware


### Software
https://developer.apple.com/xcode/


### Tool


### First App
![](assets/Pasted%20image%2020220927171836.png)
![](assets/Pasted%20image%2020220927171937.png)
Select Objective-C
![](assets/Pasted%20image%2020220927172626.png)
ubcheck the checkbox
![](assets/Pasted%20image%2020220927172652.png)

### XCode

### Interface Builder
![](assets/Pasted%20image%2020220927174109.png)
Select label
![](assets/Pasted%20image%2020220927174323.png)
You can select the type
![](assets/Pasted%20image%2020220927174445.png)



### Simulator
![](assets/Pasted%20image%2020220927180522.png)
![](assets/Pasted%20image%2020220927180543.png)
you can check version of os

![](assets/Pasted%20image%2020220927180710.png)
You can add your custom simulator
![](assets/Pasted%20image%2020220927180936.png)
Uncheck if u don't wanna see it
Result
![](assets/Pasted%20image%2020220927181016.png)

### Understanding iOS
Create new project
![](assets/Pasted%20image%2020220927181201.png)
https://livebook.manning.com/book/objective-c-fundamentals/chapter-1/69

When you click a file in the left pane, the right pane updates to provide an editor suitable for the selected file. For `*.h and *.m` source code files, a traditional source code text editor is presented, but other file types (such as `*.xib` resource files) have more complex graphical editors associated with them.

For now, let’s focus on understanding the general structure of an Objective-C–based project. Objective-C is an object-oriented language, meaning that a large portion of your coding efforts will be spent defining new classes (types of objects). [Listing 1.1](https://livebook.manning.com/book/objective-c-fundamentals/chapter-1/ch01list01) defines a new class called CoinTossViewController. By convention, the definition of a class is kept in a header file that uses a `*.h` file extension.

A header (`*.h`) file specifies what you can expect a class to contain and how other code should interact with it. Now that you’ve updated the header file, you must provide the actual implementation of the features you’ve specified. Open the matching Coin-TossViewController.m file, and replace its contents with that of the following listing.

`*.m`: Logic of code and import file `*.h`

![](assets/Pasted%20image%2020220927182600.png)

Select .h file
![](assets/Pasted%20image%2020220927182448.png)

Drag the label to code
![](assets/Pasted%20image%2020220927182725.png)
![](assets/Pasted%20image%2020220927182746.png)
![](assets/Pasted%20image%2020220927182951.png)
add line 21
![](assets/Pasted%20image%2020220927183027.png)
Run app to see the label changes


### Outlets
Create new project
![](assets/Pasted%20image%2020220927183255.png)
Drag
![](assets/Pasted%20image%2020220927183457.png)
![](assets/Pasted%20image%2020220927183634.png)
run


### Text Views
Drag and go to controller change text 


### Labels and Text Views Exercise
![](assets/Pasted%20image%2020220927183936.png)

### Label Rows Assignment
![](assets/Pasted%20image%2020220927184049.png)


### The Very Basics Recap
The Very Basics Recap

**01 - The Very Basics Recap**

  

In this section, we will cover the following topics:

  
-   Hardware
    
-   Programming Languages
    
-   Different Software
    
-   The tool of Choice (XCode)
    
-   Use of iOS Simulator
    
-   Interface Builder
    
-   Developing a Very Basic App

## Basic programming

### Intro

### Command Line & Print
Create new project
![](assets/Pasted%20image%2020220927192924.png)
![](assets/Pasted%20image%2020220927193021.png)
![](assets/Pasted%20image%2020220927193140.png)


### Comments
Create new command line tools

Using // or `/**/`

### Basic Variables
https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/Strings/Articles/FormatStrings.html#//apple_ref/doc/uid/20000943-CJBEAEHH

Int, float, char, bool
![](assets/Pasted%20image%2020220927193632.png)

https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/Strings/Articles/formatSpecifiers.html#//apple_ref/doc/uid/TP40004265-SW2


```objectivec
int myInt = 3;
float myFloat = 3.3;
BOOL myBool = true;
char my Char = 'c';
NSLog(@"Integer is: %i", myInt);
NSLOg (@"Float is: %f", myFloat);
NSLog (@"Int is: %i and Float is: %f", myInt, my Float) ;
NSLog(@"Character is: %c", myChar);
NSLog(@"Bool is: %hhd", myBool)
```

### String

```objectivec
int myInt = 32;
NSString* myString = @"A string of characters" ;|
myString = @"Hello";
NSLog("Hello World" ) ;
```

Using function
![](assets/Pasted%20image%2020220927194536.png)

Or you can print
```
NSLOG((@"%@", myStr);

```

Asterisk mask is a pointer


### Append Strings Exercise
![](assets/Pasted%20image%2020220927195024.png)
![](assets/Pasted%20image%2020220927195347.png)

### Variables In iOS
Create ios app with label
![](assets/Pasted%20image%2020220927195545.png)

![](assets/Pasted%20image%2020220927195704.png)



### If Else
Create macOS command tool
![](assets/Pasted%20image%2020220927195917.png)

Cannot compare string by == operator


### Operator

Compare 2 strings: need to check type of the second params

```
if ([category isEqualToString:@"Some String"])
{
    // Do stuff...
}
```

### Arrays and Sets
![](assets/Pasted%20image%2020220927200821.png)
![](assets/Pasted%20image%2020220927200915.png)
5 objects

The same output:

```
NSLog(@ "Object at index 2 is: 60", [daysArr objectAtIndex:21);
NSLog (@"There are %lu objects in my array", daysArr.count):
[daysArr add0bject :@"Friday " ] ;
NSLog ("There are %lu objects in my array", [daysArr count]);
```
https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/FoundationTypesandCollections/FoundationTypesandCollections.html

![](assets/Pasted%20image%2020220927201822.png)

```
[daysArr add0bject : @" Friday " 1;
[daysArr remove0bject : @"Friday"li
[daysArr remove0bjectAtIndex: 0];
```

![](assets/Pasted%20image%2020220927202148.png)

### Dictionaries

### For Loops

### Occurance of X Exercise

### Compare Arrays Assignment

### Switch

### While Loops

### Jump Statement

### Functions

### Preview

### Unique Words Assignment

### Most Photos Assignment

### Ordered Names Assignment

### Available People Assignment

### Basic Programming Recap

### Basic Programming Quiz
