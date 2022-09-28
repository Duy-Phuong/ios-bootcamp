

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
![](assets/Pasted%20image%2020220927202639.png)
![](assets/Pasted%20image%2020220927202721.png)
![](assets/Pasted%20image%2020220927202948.png)![](assets/Pasted%20image%2020220927203005.png)


### For Loops
![](assets/Pasted%20image%2020220927203234.png)


### Occurance of X Exercise

```objectivec
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[])
{
    @autoreleasepool
    {
        NSArray *citiesArr = [[NSArray alloc] initWithObjects:
                              @"Vancouver", @"Vancouver", @"New York",
                              @"New Delhi", @"Delta", @"Vancouver",
                              @"Burnabu", @"Paris", @"Dubai",
                              @"Vancouver", @"Vancouver", @"Tehran",
                              @"Toronto", @"Shanghai", @"Sao Paolo",
                              @"Taipei", @"Warsaw", @"Vancouver",
                              @"Rio De Janeiro", @"Vancouver",
                              @"Vancouver", @"Shanghai",
                              @"New Delhi", @"Delta", @"Vancouver",
                              @"Burnabu", @"Paris", @"Dubai",
                              @"Vancouver", @"Vancouver", @"Tehran",
                              @"Toronto", @"Shanghai", @"Sao Paolo",
                              @"Taipei", @"Warsaw", @"Vancouver",
                              @"Rio De Janeiro", @"Vancouver",
                              @"Vancouver", @"Shanghai", nil];
        
        int vancouverCount = 0;
        for (NSString* city in citiesArr)
        {
            if ( [city isEqualToString: @"Shanghai"] )
            {
                vancouverCount += 1;
            }
        }
        
        // finding the most repeated city name
        NSLog(@"Shanghai is repeated %i times", vancouverCount);
    }
    return 0;
}

```

### Compare Arrays Assignment

```objectivec
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[])
{
    @autoreleasepool
    {
        // Are the two arrays of the same size
        // Are the objects the same
        // is the order of the objects the same
        // And if the order is not the same, at what index the order breaks?
        
        NSArray *citiesArrOne = [[NSArray alloc] initWithObjects:
                                 @"Vancouver", @"Vancouver", @"New York",
                                 @"New Delhi", @"Delta", @"Vancouver",
                                 @"Burnabu", @"Paris", @"Dubai",
                                 @"Vancouver", @"Vancouver", @"Tehran",
                                 @"Toronto", @"Shanghai", @"Sao Paolo",
                                 @"Taipei", @"Warsaw", @"Vancouver",
                                 @"Rio De Janeiro", @"Vancouver",
                                 @"Vancouver", @"Shanghai",
                                 @"New Delhi", @"Delta", @"Vancouver",
                                 @"Burnabu", @"Paris", @"Dubai",
                                 @"Vancouver", @"Vancouver", @"Tehran",
                                 @"Toronto", @"Shanghai", @"Sao Paolo",
                                 @"Taipei", @"Warsaw", @"Vancouver",
                                 @"Rio De Janeiro", @"Vancouver",
                                 @"Vancouver", @"Shanghai", nil];
        
        
        NSArray *citiesArrTwo = [[NSArray alloc] initWithObjects:
                                 @"Vancouver", @"Vancouver", @"New York",
                                 @"New Delhi", @"Delta", @"Vancouver",
                                 @"Burnabu", @"Paris", @"Dubai",
                                 @"Vancouver", @"Shanghai",
                                 @"New Delhi", @"Delta", @"Vancouver",
                                 @"Burnabu", @"Paris", @"Dubai",
                                 @"Rio De Janeiro", @"Vancouver",
                                 @"Toronto", @"Shanghai", @"Sao Paolo",
                                 @"Taipei", @"Warsaw", @"Vancouver",
                                 @"Rio De Janeiro", @"Vancouver",
                                 @"Vancouver", @"Vancouver", @"Tehran",
                                 @"Vancouver", @"Vancouver", @"Tehran",
                                 @"Toronto", @"Shanghai", @"Sao Paolo",
                                 @"Taipei", @"Warsaw", @"Vancouver",
                                 @"Vancouver", @"Shanghai", nil];
    }
    return 0;
}

```

### Switch

```objectivec
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[])
{
    @autoreleasepool
    {
        int myInt = 4; // static
        
        switch (myInt)
        {
            case 1:
            case 2:
                NSLog(@"It was one or two");
                break;
                
            case 3:
                NSLog(@"It was three");
                break;
                
            default:
                NSLog(@"None of the above");
                break;
        }
        
        
        // a string
        // vancouver, sf, ny, Paris
        NSArray *strArr = [[NSArray alloc] initWithObjects:
                           @"Vancouver",
                           @"San Fransisco",
                           @"New York",
                           @"Paris", nil];
        
        NSString *myStr = @"New York";
        
        int cityIndex = (int) [strArr indexOfObject: myStr];
        switch (cityIndex)
        {
            case 0:
                NSLog(@"It was at first");
                break;
            
            case 1:
                NSLog(@"It was at second");
                break;
            default:
                break;
        }
        
    }
    return 0;
}

```
### While Loops

```objectivec
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[])
{
    @autoreleasepool
    {
        int myInt = 0;
        
        while (myInt < 20)
        {
            NSLog(@"myInt is now: %i", myInt);
            myInt ++;
        }
        
        myInt = -5;
        
        do
        {
            NSLog(@"myInt is: %i", myInt);
            myInt --;
        } while (myInt > 0) ;
        
    }
    return 0;
}

```

### Jump Statement

```objectivec
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[])
{
    @autoreleasepool
    {
        for (int counter = 0; counter < 10; counter ++)
        {
            if ( counter == 6 )
                break;
//            NSLog(@"Counter is: %i", counter);
        }
//        NSLog(@"End of the for loop");
        
        NSArray *citiesArr = [[NSArray alloc] initWithObjects:
                              @"Vancouver", @"Vancouver", @"New York",
                              @"New Delhi", @"Delta", @"Vancouver",
                              @"Burnabu", @"Paris", @"Dubai",
                              @"Vancouver", @"Vancouver", @"Tehran",
                              @"Toronto", @"Shanghai", @"Sao Paolo",
                              @"Taipei", @"Warsaw", @"Vancouver",
                              @"Rio De Janeiro", @"Vancouver",
                              @"Vancouver", @"Shanghai",
                              @"New Delhi", @"Delta", @"Vancouver",
                              @"Burnabu", @"Paris", @"Dubai",
                              @"Vancouver", @"Vancouver", @"Tehran",
                              @"Toronto", @"Shanghai", @"Sao Paolo",
                              @"Taipei", @"Warsaw", @"Vancouver",
                              @"Rio De Janeiro", @"Vancouver",
                              @"Vancouver", @"Shanghai", nil];
        
        
        for (NSString *city in citiesArr)
        {
            if ( [city isEqualToString: @"Shanghai"] )
            {
//                NSLog(@"We found Shanghai");
                break;
            }
            
//            NSLog(@"This city is: %@", city);
        }
        
        
        BOOL completed = false;
        // v = 3 and h = 2 -> break out entirly
        for (int h = 0; h < 5; h ++)
        {
            if ( completed )
                break;
            
            for (int v= 0; v < 5; v++)
            {
                NSLog(@"We are at h: %i and v: %i", h, v);
                if ( v == 3 & h == 2)
                {
                    completed = true;
                    break;
                }
            }
            NSLog(@"internal loop is finished");
        }
        NSLog(@"For loop is completely finished");
        
    }
    return 0;
}

```

### Functions

Create new ios project
![](assets/Pasted%20image%2020220927205346.png)

ViewController.m
```objectivec
#import "ViewController.h"

@interface ViewController ()

@end

@implementation ViewController

// function that runs at view load time
- (void)viewDidLoad
{
    [super viewDidLoad];


    NSMutableString *myStr = [NSMutableString stringWithString:@"Something"];
    
    [self whichIsBigger:3 and:4];
    
    
}

// -(return type) function name : (argument type)argument name

-(void)whichIsBigger:(int)a and:(int)b
{
    if ( a > b)
        NSLog(@"%i is larger", a);
    else
        NSLog(@"%i is larger", b);
}



@end

```

### Dice

```objectivec
#import <Foundation/Foundation.h>
int main(int argc, const char * argv[])
{
    @autoreleasepool
    {
        int counters[7] = {-1, 0, 0, 0, 0, 0, 0};
        
        for ( int i = 0; i < 1000000; i++)
        {
            int randomInt = 1 + arc4random() % 6;
            counters[randomInt]++;
        }
        
        for (int c = 1; c <= 6; c++)
        {
            NSLog(@"%i happens %i times", c, counters[c]);
        }
    }
    return 0;
}

```

### Unique Words Assignment

```objectivec
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[])
{
    @autoreleasepool
    {
         NSString *objC = @"Objective-C is a general-purpose, object-oriented programming language that adds Smalltalk-style messaging to the C programming language. It was the main programming language used by Apple for the OS X and iOS operating systems, and their respective application programming interfaces (APIs) Cocoa and Cocoa Touch prior to the introduction of Swift. \n The programming language Objective-C was originally developed in the early 1980s. It was selected as the main language used by NeXT for its NeXTSTEP operating system, from which OS X and iOS are derived.[3] Portable Objective-C programs that do not use the Cocoa or Cocoa Touch libraries, or those using parts that may be ported or reimplemented for other systems, can also be compiled for any system supported by GNU Compiler Collection (GCC) or Clang";
    }
    return 0;
}

```

### Most Photos Assignment

### Ordered Names Assignment

### Available People Assignment

### Basic Programming Recap

### Basic Programming Quiz

## Basic user interface

GUI KIT
BUTTONS
SEGMENTED CONTROLS
IMAGE VIEWS
TEXT FIELDS
UI SWITCH
SLIDERS AND STEPPERS
VIEW CONTROLLERS
NAVIGATION BETWEEN VIEW CONTROLLERS
PASSING DATA

### GUI Kit

https://www.behance.net/gallery/54882503/ios11-GUl-KIT

https://iosdesignkit.io/ios-gui


### Buttons
Select Action
Drag Button to file .h
![](assets/Pasted%20image%2020220927212717.png)

Go to .m file
![](assets/Pasted%20image%2020220927213047.png)

When u tap on button, the text is changed

Create mySecondAction like tapAction
![](assets/Pasted%20image%2020220928101413.png)

Add new action and connect it manually by clicking on the most-left icon
![](assets/Pasted%20image%2020220927213415.png)
Remove the first action => drag second action

Right click to drag and drop outlet for button to test

```objectivec
#import <UIKit/UIKit.h>

@interface ViewController : UIViewController


@property (weak, nonatomic) IBOutlet UILabel *resLabel;

@property (weak, nonatomic) IBOutlet UIButton *myButton;

@end


```

```objectivec
#import "ViewController.h"

@implementation ViewController

- (void)viewDidLoad
{
    [super viewDidLoad];

    // buttons through assistant editor
    // actions called fro IB
    // actions called by addTarget
    
    
    [_myButton addTarget:self
                  action:@selector(changeLabel)
        forControlEvents:UIControlEventTouchUpInside];
}


-(void)changeLabel
{
    _resLabel.text = @"This was programmatic";
}

@end

```


### Tap to Reveal Exercise
![](assets/Pasted%20image%2020220927222224.png)

Move to property

![](assets/Pasted%20image%2020220927222511.png)
![](assets/Pasted%20image%2020220927222552.png)

### Segment control
Add Segment to Main
![](assets/Pasted%20image%2020220927223441.png)


```objectivec
#import <UIKit/UIKit.h>

@interface ViewController : UIViewController

@property (weak, nonatomic) IBOutlet UISegmentedControl *mySegCtrl;

@property (weak, nonatomic) IBOutlet UILabel *resLabel;


- (IBAction)tapOnSeg:(id)sender;

- (IBAction)removeAction:(UIButton *)sender;

- (IBAction)addAction:(UIButton *)sender;



@end


```

```objectivec
#import "ViewController.h"

@implementation ViewController

- (void)viewDidLoad
{
    [super viewDidLoad];
    
}

- (IBAction)tapOnSeg:(id)sender
{    
    int currentIndex = (int) _mySegCtrl.selectedSegmentIndex;
    NSLog(@"Current Index is: %i", currentIndex);
    
    if ( currentIndex == 0)
        _resLabel.text = @"HELLO";
    else
        _resLabel.text = @"WORLD";
}

- (IBAction)removeAction:(UIButton *)sender
{
    [_mySegCtrl removeSegmentAtIndex:0
                            animated:true];
}

- (IBAction)addAction:(UIButton *)sender
{
    [_mySegCtrl insertSegmentWithTitle:@"Android"
                               atIndex:1
                              animated: true];
}
@end

```

### Image Views
Create ImageView and drag to header
drag to our project
![](assets/Pasted%20image%2020220927235051.png)
Check copy

```objectivec
#import "ViewController.h"


@implementation ViewController

- (void)viewDidLoad
{
    [super viewDidLoad];

    // an image which is a string name for your actual photograph
    // i.e. cat.jpg
    
    // UIImage a class for represneting image data
    
    // UIImage View
    

    
    _myImgView.image = [UIImage imageNamed: @"cat.jpg"];;
    
    _myImgView.contentMode = UIViewContentModeScaleAspectFit;
    
}


@end

```

Or you can

![](assets/Pasted%20image%2020220927235354.png)
Content mode: change to aspect fit
You can select Clip to bound
![](assets/Pasted%20image%2020220927235519.png)

### Image Switcher Exercise
![](assets/Pasted%20image%2020220927235841.png)

```objectivec
#import "ViewController.h"
@implementation ViewController

NSArray* imgArr;

- (void)viewDidLoad {
    [super viewDidLoad];
   
    imgArr = [[NSArray alloc] initWithObjects: @"birds", @"cat", @"eye", nil];
    
    for (int i = 0; i < imgArr.count; i++)    {
        NSString *title = [imgArr objectAtIndex: i];
        [_mySegCtrl setTitle:title forSegmentAtIndex:i];
    }
    [self segChangedAction: nil];
}

- (IBAction)segChangedAction:(id)sender {
    int myInd = (int) [_mySegCtrl selectedSegmentIndex];
    NSString *imgName = [imgArr objectAtIndex: myInd];
    NSString *jpgAdded = [NSString stringWithFormat: @"%@.jpg", imgName];
    UIImage *thisImg = [UIImage imageNamed: jpgAdded];
    
    _myImgView.image = thisImg;
    
    
//    _myImgView.image = [UIImage imageNamed: [NSString stringWithFormat: @"%@.jpg", [imgArr objectAtIndex: [_mySegCtrl selectedSegmentIndex]]]];
}
@end

```

### Text Fields

convert to int value

```objectivec
#import "ViewController.h"

@implementation ViewController

- (void)viewDidLoad
{
    [super viewDidLoad];
    
    _emailTxtFld.keyboardType = UIKeyboardTypeEmailAddress;
}

- (IBAction)submitAction:(id)sender
{
    [_usernameTxtFld resignFirstResponder];
    [_emailTxtFld resignFirstResponder];
    [_ageTxtFld resignFirstResponder];
    
    NSString* name = _usernameTxtFld.text;
    NSString* email = _emailTxtFld.text;
    NSString* age = _ageTxtFld.text;
    
    int ageInt = [_ageTxtFld.text intValue];
    
    NSString *resString = [NSString stringWithFormat:@"%@ with %@ and %@ years old", name, email, age];
    
    _resultLabel.text = resString;
    
    _usernameTxtFld.text = @"";
    _emailTxtFld.text = @"";
    _ageTxtFld.text = @"";
}
@end

```

```objectivec
#import <UIKit/UIKit.h>

@interface ViewController : UIViewController

@property (weak, nonatomic) IBOutlet UITextField *usernameTxtFld;
@property (weak, nonatomic) IBOutlet UITextField *emailTxtFld;
@property (weak, nonatomic) IBOutlet UITextField *ageTxtFld;
@property (weak, nonatomic) IBOutlet UILabel *resultLabel;

- (IBAction)submitAction:(id)sender;



@end


```

### UI Switch
Add new 

![](assets/Pasted%20image%2020220928003908.png)

Set default value
![](assets/Pasted%20image%2020220928004004.png)

### UI Slider
![](assets/Pasted%20image%2020220928004217.png)


### Image Slider Exercise
create folder images
![](assets/Pasted%20image%2020220928004652.png)

```objectivec
#import <UIKit/UIKit.h>

@interface ViewController : UIViewController

@property (weak, nonatomic) IBOutlet UISlider *mySlider;

@property (weak, nonatomic) IBOutlet UIImageView *myImgView;


- (IBAction)slideAction:(id)sender;


@end


```

```objectivec
#import "ViewController.h"

@implementation ViewController
NSArray *imgArr;

- (void)viewDidLoad
{
    [super viewDidLoad];
    [self populateArray];
    
    _mySlider.minimumValue = 0;
    _mySlider.maximumValue = imgArr.count - 1;
}

- (IBAction)slideAction:(id)sender
{ // round, floor, ceil
    int myIndex = roundf ( _mySlider.value );
    _myImgView.image = [UIImage imageNamed: imgArr[myIndex]];
}


-(void)populateArray
{
    imgArr = [[NSArray alloc] initWithObjects:
              @"3848765-wallpaper-images-download.jpg",
              @"birds.jpg",
              @"cat.jpg",
              @"eye.jpg",
              @"image-slider2.jpg",
              @"images.jpg",
              @"img.jpg",
              @"Spring-Lamb.-Image-shot-2-011.jpg", nil];
}
@end

```


### UI Stepper
![](assets/Pasted%20image%2020220928005126.png)
![](assets/Pasted%20image%2020220928005253.png)

### View Controller
Add new view controller
![](assets/Pasted%20image%2020220928075815.png)

![](assets/Pasted%20image%2020220928080001.png)
You can click on the arrow and drag it
![](assets/Pasted%20image%2020220928080209.png)
Drag button to the next ViewController
![](assets/Pasted%20image%2020220928080255.png)
You can change to see the difference
![](assets/Pasted%20image%2020220928080402.png)




### ViewControllerClass
![](assets/Pasted%20image%2020220928081245.png)

File/ New/ File
![](assets/Pasted%20image%2020220928081355.png)
![](assets/Pasted%20image%2020220928081424.png)
Or you can create empty file


```objectivec
#import <UIKit/UIKit.h>



@interface PinkViewController : UIViewController

@property (weak, nonatomic) IBOutlet UILabel *myLabel;
@property NSString *passedName;

- (IBAction)backToGreenAction:(id)sender;


@end

```

Back btn
```objectivec
#import "PinkViewController.h"

@implementation PinkViewController

- (void)viewDidLoad
{
    [super viewDidLoad];
    
    
    _myLabel.text = _passedName;
}

- (IBAction)backToGreenAction:(id)sender
{
    [self dismissViewControllerAnimated: true
                             completion: nil];
}
@end

```

### Segue
Create new file/ Home.storyboard
![](assets/Pasted%20image%2020220928082928.png)

Change Main storyboard
![](assets/Pasted%20image%2020220928083714.png)

![](assets/Pasted%20image%2020220928093758.png)

![](assets/Pasted%20image%2020220928083908.png)

Add identifier
![](assets/Pasted%20image%2020220928084049.png)

Main

```objectivec
#import <UIKit/UIKit.h>

@interface MainViewController : UIViewController


- (IBAction)gotoSecondAction:(id)sender;


- (IBAction)gobackToHome:(UIStoryboardSegue *)sender;


@end

```

```objectivec
#import "MainViewController.h"

@implementation MainViewController



- (IBAction)gotoSecondAction:(id)sender
{
    [self performSegueWithIdentifier: @"toPinkSegueId"
                              sender: nil];
}

- (IBAction)gobackToHome:(UIStoryboardSegue *)sender
{
    
}

@end

```

SecondViewController

```objectivec
#import <UIKit/UIKit.h>

@interface SecondViewController : UIViewController
- (IBAction)gotoThirdAction:(id)sender;


- (IBAction)goBackHomeAction:(id)sender;


@end

```

```objectivec
#import "SecondViewController.h"

@implementation SecondViewController


- (IBAction)gotoThirdAction:(id)sender
{
    [self performSegueWithIdentifier: @"toGreenSegueId"
                              sender: nil];
}

- (IBAction)goBackHomeAction:(id)sender
{
    [self dismissViewControllerAnimated: true
                             completion: nil];
}
@end

```

Third

```objectivec
#import "ThirdViewController.h"


@implementation ThirdViewController


- (IBAction)goBackToSecondAction:(id)sender
{
    [self dismissViewControllerAnimated: true
                             completion: nil];
}
@end

```

Add `- (IBAction)gobackToHome:(UIStoryboardSegue *)sender` in Main

![](assets/Pasted%20image%2020220928092835.png)

### Passing Data

```objectivec
#import "ViewController.h"
#import "PinkViewController.h"

@implementation ViewController

- (IBAction)gotoPinkAction:(id)sender
{
    [self performSegueWithIdentifier: @"toPinkSegueId"
                              sender: nil];
}

-(void) prepareForSegue:(UIStoryboardSegue *)segue sender:(id)sender
{
    PinkViewController *thisPinkInstance = [segue destinationViewController];
    thisPinkInstance.receivedData = _dataTextFld.text;
}

@end

```

PinkViewController

```objectivec
#import <UIKit/UIKit.h>

@interface PinkViewController : UIViewController


@property (weak, nonatomic) IBOutlet UILabel *receivedDataLabel;

- (IBAction)goBackHomeAction:(id)sender;

@property NSString *receivedData;

@end

```

```objectivec
#import "PinkViewController.h"

@implementation PinkViewController

- (void)viewDidLoad
{
    [super viewDidLoad];
   
    _receivedDataLabel.text = _receivedData;
}

- (IBAction)goBackHomeAction:(id)sender
{
    [self dismissViewControllerAnimated: true
                             completion: nil];
}
@end

```

### Recap
You can create outlet button and drag to the button on UI
![](assets/Pasted%20image%2020220928100202.png)



### Find Image Assignment

### User Manager Assignment

### Basic User Interface Recap
**03 - Basic User Interface Recap**

  

Basic User Interface

In this section, we will go back to iOS Development and using what we have learned in programming, we will begin working on a variety of basic user interface elements.

We will learn how to use UI elements as outlets and interact with them in our code. In specific in this section we will discuss topics such as:

  

-   GUI Kit
    
-   Buttons
    
-   Segmented controls
    
-   Image views
    
-   Text fields
    
-   UI switch
    
-   Sliders and steppers
    
-   View controllers
    
-   Navigation between view controllers
    
-   Passing data between different view controllers
    

  

By the end of this section, you should be easily add a variety of UI elements into your app and trigger functions in the code.

  

**GUI Kit**

In this lesson, we will have a look at the GUI Kit and try to familiarize ourselves with various available outlets.

These are the links to the two websites that we talked about in the video:

  

[https://www.behance.net/gallery/54882503/iOS11-GUI-KIT](https://www.behance.net/gallery/54882503/iOS11-GUI-KIT)

[https://iosdesignkit.io/ios-gui/](https://iosdesignkit.io/ios-gui/)

  

**Buttons**

-   We use Buttons to trigger actions depending on when and where on them a click has landed.
    
-   We could call functions on actions directly using the assistant editor or we could use the View Controller's connection inspector to do that.
    
-   For calling actions, we could also use the addTarget method.
    

  

**Scope of a variable**

-   Variables also have a scope which means in which function (or functions) are they available.
    
-   If a declaration of a variables is inside a body of a function, that variables is said to be local to that function only.
    
-   If the declaration is outside, that variable is accessible by every function.
    

  

**Segmented Controls**

-   They work like radio buttons that only one of them can be active at any given time.
    
-   The event to trigger them is the Value Changed.
    
-   Their segments are ordered from 0 upwards.
    
-   Their segments can be removed dynamically.
    
-   Their segments can be inserted dynamically.
    
-   Similar to buttons, they can be called using addTarget.
    

  

**Image Views**

-   Image Views are the containers that can show us images.
    
-   Images can be read from a variety of sources. if we use an image that is embedded into our project, we can simply use the
    

  

[UIImage imageNamed: @""]

  

-   We will see other methods of converting NS Data into images in the future.
    

  

**Text Fields:**

-   In this lesson, we will learn to use basic text fields and decorate them.
    
-   We will also learn how to change the keyboard type on them and fetch values from them.
    
-   We will quickly discuss getting int values from strings as well.
    
-   We will also learn how to press a button to get rid of the keyboard.
    
-   Text Fields also have placeholders.
    
-   We should clear the text fields once they are used.
    

  

In this lesson, we will quickly cover the mechanics of using a UI Switch outlet and changing a value (string) based on that. We will also learn about casting the sender to UI Switch.

  

**UI Sliders**

-   Sliders are used to scrub between a minimum and maximum number.
    
-   Their default value is a float number.
    
-   You can set them to be triggered only when the scrub is finished and not a continuous trigger.
    

  

**UI Stepper**

-   Stepper are used to increment a value.
    
-   Their step can be changed.
    
-   And they can step continuously or one at a time.
    
-   Steps don't have to be integers.
    

  

**View Controllers**

In this lesson, we will learn how to make a new view controller and how (from interface) go through a segue

View controllers are like a container that hold on to all UI objects for a certain class and they also provide user interactivity.

  

**View Controller Class**

In this lesson, we will learn how to add a new view controller class and connect it to our view controller in IB

We will run a test in which a value will appear from view did load

We will discuss both classes and run cycles of view controller in future

  

**Segue**

In this lesson, we will learn how to call a segue programmatically and in interface builder.

We will use the segues from buttons to view controllers.

We will also use segues from view controllers to view controllers.

We will talk further about the use of unwind segue. To use unwind segue, you would need a function with IBAction return type and an argument of the type UIStoryBoardSegue in the View Controller you are unwinding back to.

This part is a little confusing. Unwind segues are the only type of functions that you don’t code them in the class of your view controller. Rather you code them on where you want to go back to.

  

**Passing Data Between View Controllers**

-   In this lesson, we will learn how to prepare for a segue and pass data between our different view controller
    
-   To do that, we need to prepare for an upcoming segue using the prepareForSegue built-in function
    

  

**Recap**

In this section, we covered the following topics:

-   Buttons and how to assign functions to them in the storyboard as well as using the addTarget.
    
-   Segmented controls and how their selectedIndex number helps us
    
-   Image Views and how we could load images into them and change the content mode.
    
-   Text Fields and how we could change keyboard on them.
    
-   Switch and how we could get their isOn state.
    
-   Sliders and how we could read their value.
    
-   Steppers and how we could use them to increment or decrement a value.
    
-   View controllers and how we could use them to categorize our app also assign separate view controller classes to them.
    
-   We finally touched on segues and passing data between view controllers using prepareForSegue

### Basic User interface Quiz

## Swift

### Introduction to Swift Section

### Playground
![](assets/Pasted%20image%2020220928182112.png)

Playground: it helps us to see things are in real time

![](assets/Pasted%20image%2020220928182301.png)
![](assets/Pasted%20image%2020220928182324.png)
Then enter the name for playground

![](assets/Pasted%20image%2020220928182515.png)


### Swift Variables
playground

```swift
import Cocoa

// var, let, interpolations and annotations

let myInt : Int = 5
let myInt2 = 5

let myString : String = "Hello"
var userName : String = ""

var myFloat: Float = 3.5
print ( "My Float is: \(myFloat)" )

print ("My int is: \(myInt)")

// var ~ NSStrign
// let ~ NSMutableString
/*
 
 */

```

### Swift Optionals

Create new command line tool


```swift
import Foundation

var myInt : Int = 5 // non optional - initialized
var nextInt : Int? // optional integer that needs to be unwrapped before use
var unwrappeedInt : Int! // it is treated as if it was not optional

print ("\(nextInt!)") // this will crash // forced unwrapped

if let nextInt = nextInt // conditional unwrapping
{
    // then dowhatever you want to do
}
else
{
    // otherwise, it's still nil
}


print ("\(unwrappeedInt)") // treat as if it was not optional


```

### Swift Control Flow

playground

```swift
import Cocoa

for i in stride(from: 0, to: 50, by: 10)
{


}

```

https://www.programiz.com/swift-programming/for-in-loop#:~:text=while%20loop-,Swift%20for%2Din%20Loop,%2C%20range%2C%20string%2C%20etc.&text=Here%2C%20val%20accesses%20each%20item,last%20item%20in%20the%20sequence%20.

A for-in loop is usually used when the number of iterations is known. For example,

```swift
// this loop is iterated 5 times
for number in 1...5 {
   // body of loop
}

// this loop is iterated 4 times
for number in 1...<5 {
   // body of loop
}

for number in "Hello" {
   // body of loop
}

The syntax of repeat..while loop is:

repeat {
  // body of loop
} while (condition)

```

```swift
// program to display numbers

var i = 1, n = 5

// repeat...while loop from 1 to 5
repeat {
  
  print(i)

  i = i + 1

} while (i <= n)
```

### Swift Strings

```swift
import Cocoa

var str : String = "Hello, playground"
var multiLineString : String = """
This is line one
and this is line two
"""

var myStr: String = ""
var otherStr = String()

var firstStr = "Hello"
var secondStr = " World"

var resStr = firstStr + secondStr
// [firstStr appendString: secndStr]

print (resStr)

// if ( [oneStr isEqualString: another] )

if firstStr == secondStr
{
    print ("same")
}
else
{
    print ("not the same")
}


let myLongStr : String = "Hello, this is iOS Bootcamp"
for any : Character in myLongStr
{
    print (any)
}

```

### Arrays in Swift

create command line

```swift
import Foundation

var stringArray : Array <String> = ["Hello", "World"]

print (stringArray[0])
stringArray.append("iOS")
print (stringArray.count)
stringArray.remove(at: 1)
print (stringArray)

if let index = stringArray.index(of: "iOS")
{
    print ("iOS is at \(index)")
}
else
{
    print ("It's not here")
}

var myNSArray : NSArray = NSArray.init(objects: "Hello", "World")

```

### Dictionaries in Swift

### Functions in Swift

### Preview

### Random Image Picker Exercise

### Swift User Manager Assignment

### Swift Recap

### Swift Quiz
