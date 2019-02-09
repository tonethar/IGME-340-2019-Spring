# Course Topics

## Weekly

### Week 1

- Intro to Xcode
    - playgrounds
    - navigator area
    - editor area
    - utilities area
    - choosing a simulator
    - compiling and running
 - Swift
   - variables and constants - `var` / `let`
   - creating instances
   - Types: strings, floats, ints
   - explicit casting v. type interence
 - Cocoa Touch
   - `UIView`, `UILabel`
   - parent/child - `addSubview()`
   - coordinate system
 - Exercises
   - Hello RIT-1
   
### Week 2
- Storyboard
  - outlets
  - actions
- Swift
  - arrays
  - dictionaries
  - functions
- Installing Apps onto iOS devices
  
 ### Week 3
 - Creating a Custom Class - `Person.swift`
 - Model-View-Controller
   - model contains and validates the data
 - Re-write *Motivator* to become *MVC Motivator*
 - App Design Exercise:
   - "Magnetic Poetry" App
 - Links:
   - [Swift Language Guide](https://docs.swift.org/swift-book/)
   - [iOS HIG](https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes/)
   
 ### Week 4
 - Review *Monster HW*
   - add `didSet` property observer
   - add `description` method via - `CustomStringConvertible` - https://developer.apple.com/documentation/swift/customstringconvertible
 - Review *Motivator MVC Plus Bromides*
   - *nil coalescing operator* - `??` - is like a ternary operator for optionals 
   - random array elements
   - class extensions
   - use `enum` to get rid of "magic numbers" in your code
 - Project 1
   - Assign [Project 1](./assignments/project-1.md)
   - Form Groups
   - Topics needed for Project 1 - Deliverable #1:
     - Demo importing icons
     - Demo setting up a splash screen
     - Everything you need for completing checkpoints #1 & #2 is posted!
     
 ### Week 5
 - Topics needed for Project 1 - Deliverable #2:
   - Storyboard
     - autolayout
     - autoresizing
   - Tables
     - datasource prototcols
       - how many sections?
       - how many rows?
     - delegate protocols
       - row was tapped
   - ViewControllers
     - creating them in Storyboard
     - segues
     - sending data to a "child" view controller - `prepare(for segue: UIStoryboardSegue, sender: Any?) `
     - sending data to a "parent" view controller - `@IBAction func unwindToMain(segue:UIStoryboardSegue)`
   - Navigation bars
     - adding one to a VC (using Storyboard)
     - adding buttons to a Nav Bar (using Storyboard)
   - Other examples of delegation and protocols:
     - `CLLocation`
     - `UIPickerView`
     
### Week 6
 - Topics needed for Project 1 - Final Deliverable:
   - Save a snapshot of view
   - Share a snapshot of view
   - Singletons
   
   
### Week 7
 - Topics needed for Final Project Extras: 
   - Dependency Injection
   - `UIAppearance`
   - `Kinetic Realism` & `UIInterpolatingMotionEffect`
   
 

## All Topics
- Tools
  - Xcode
  - Playgrounds
- Debugging
  - Regular Breakpoints
  - Exception Breakpoints
  - Conditional Breakpoints
  - Step In/Step Over/Continue
  - Stack Trace
  - Profiling
  - Throwing Exceptions
  - Debugger Console
- Testing
 - Unit Testing
 - *UI Testing*
- Swift Language Features and Concepts
  - Immutability
  - Type Inference
  - Type Safety
  - upcasts and downcasts
  - Optionals
  - guard
  - Do/Try/Catch
  - Designated Initializers and Convenience Initializers
- Software Design Patterns
  - Target-Action
  - MVC
  - Dependency Injection
  - MVVM
  - Notifications
  - Delegation and Protocols (Dynamic Dispatch)
  - Inheritance
  - Composition
  - Separation of Concern
  - Singleton
- Mobile App Design
  - Prototyping
  - Application Definition Statement
  - Navigation
    - Navigation Controllers - "Drill Down" with Detail Views
    - Tab Bar
    - iPad Split View
- Foundation Classes
  - NSString & NSMutableString
  - NSArray & NSMutableArray
  - NSDictionary & NSMutableDictionary
  - NSData
  - NSDate
- Cocoa Touch
  - Application Delegate & Lifecycle
  - Saving State in NSUserDefaults
  - UIView and its subclasses
- Other iOS Frameworks
  - AVFoundation
  - Core Location
  - Maps
  - CoreGraphics
  - SpiteKit or WatchKit
  - Profiling with Instruments
  - Core Animation Tool
- Leaks Tool
- Case Studies
  - CountR & Technobabble Generator & Tip Calculator
- Concepts explored:
- Storyboards
Target-Action
View Controllers
Writing Methods
Calling Methods on Foundation classes
Custom Classes
Magnet App
Concepts explored:
GestureRecognizers
Arrays
Utilizing Camera (P1)
Storing Data (P1)
Sharing Content (P1)
Object Serialization (P1)
National Parks
Concepts explored:
Model Classes
Navigation
Location
Maps
Table Views
Custom Table View Cells
Drawing App HW - Concepts explored:
  - Procedural Drawing with CoreGraphics
  - Gestures
  - Concert App

