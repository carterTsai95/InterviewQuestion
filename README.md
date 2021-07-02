# iOS Developer Interview Preparation

## Purpose of this open source

This idea come out when I start to prepare my iOS interview question. In this open source repository, I am trying to gather the related iOS interview question as much as I can. Then, I will use my own word to define/answer those of the question in order to examine my knowledge.

## Table of Contents

- [Swift Fundemantal Knowledge](https://github.com/tsaihong1995/InterviewQuestion#swift-fundemantal-knowledge)

    - [What are struct and class in iOS? What is the difference? When would you use each?](https://github.com/tsaihong1995/InterviewQuestion#what-are-struct-and-class-in-ios-what-is-the-difference-when-would-you-use-each)
    - [What is framework in iOS? & What iOS frameworks do you have experience working with?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#what-is-framework-in-ios)
    - [How can you store information within your iOS app?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#how-can-you-store-information-within-your-ios-app)
    - [How do you cast between types?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#how-do-you-cast-between-types)
    - [What is the difference between var and let?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#what-is-the-difference-between-var-and-let)
    - [What is the difference between implicit and explicit?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#what-is-the-difference-between-implicit-and-explicit)
    - [Tell me about enum in Swift language. Can you give useful examples of enum associated values?](https://github.com/tsaihong1995/InterviewQuestion#tell-me-about-enum-in-swift-language-can-you-give-useful-examples-of-enum-associated-values)
    - [What is Core Data?](https://github.com/tsaihong1995/InterviewQuestion#what-is-core-data)
    - [When would you use Core Data over NSUserDefault?](https://github.com/tsaihong1995/InterviewQuestion#when-would-you-use-core-data-over-nsuserdefault)
    - [What is NSFetchRequest?](https://github.com/tsaihong1995/InterviewQuestion#what-is-nsfetchrequest)

- [Debugging & Optimization](https://github.com/tsaihong1995/InterviewQuestion#debugging)
    - [How do you debug and profile code on iOS application?](https://github.com/tsaihong1995/InterviewQuestion#how-do-you-debug-and-profile-code-on-ios-application)
	- [How do you optimize scrolling performance of dynamically sized table or collection views?](https://github.com/tsaihong1995/InterviewQuestion#how-do-you-optimize-scrolling-performance-of-dynamically-sized-table-or-collection-views)
	- Explain your process for tracing and fixing memory leaks.
	- You’ve just been alerted that your new app is prone to crashing. What do you do?
	- How do you test your code? How do you make your code testable?

- [Design Pattern](https://github.com/tsaihong1995/InterviewQuestion#design-patterns)
    - [What is Singleton Pattern?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#what-is-singleton-pattern)
    - [What is the delegation pattern? How would you explain delegates to a new Swift developer?]()
    - [What is MVC?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#what-is-mvc)
    - [What is MVVM?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#what-is-mvvm)

- [General / Uncategorized](https://github.com/tsaihong1995/InterviewQuestion#general--uncategorized)

    - [What is a protocol? How do you define your own protocol?](https://github.com/tsaihong1995/InterviewQuestion#what-is-a-protocol-how-do-you-define-your-own-protocol)
    - [What is the difference between a class and an object?](https://github.com/tsaihong1995/InterviewQuestion#what-is-json-what-are-the-pros-and-cons)
    - [What is JSON? What are the pros and cons?](https://github.com/tsaihong1995/InterviewQuestion#what-is-json-what-are-the-pros-and-cons)
    - [What is the difference between not-running, inactive, active, background and suspended execution states?](https://github.com/tsaihong1995/InterviewQuestion#what-is-the-difference-between-not-running-inactive-active-background-and-suspended-execution-states)
    - [What is KVO?](https://github.com/tsaihong1995/InterviewQuestion#what-is-kvo)
	- [What is NSFetchRequest?](https://github.com/tsaihong1995/InterviewQuestion#what-is-nsfetchrequest)

- [Memory Management](https://github.com/tsaihong1995/InterviewQuestion#memory-management)
    - [Why do you generally create a weak reference when using self in a block?](https://github.com/tsaihong1995/InterviewQuestion#why-do-you-generally-create-a-weak-reference-when-using-self-in-a-block)
    - [What is memory management handled on iOS?](https://github.com/tsaihong1995/InterviewQuestion#what-is-memory-management-handled-on-ios)
    - [What is the difference between *weak* and *strong*?](https://github.com/tsaihong1995/InterviewQuestion#what-is-the-difference-between-weak-and-strong)
    - [What is a memory leak?](https://github.com/tsaihong1995/InterviewQuestion#what-is-a-memory-leak)
    - [What is a retain cycle?](https://github.com/tsaihong1995/InterviewQuestion#what-is-a-retain-cycle)
    - [What is the difference between copy and retain?](https://github.com/tsaihong1995/InterviewQuestion#what-is-the-difference-between-copy-and-retain)
    - [What is the difference between a stack vs a heap?](https://github.com/tsaihong1995/InterviewQuestion#what-is-the-difference-between-a-stack-vs-a-heap)
    - [What are “strong” and “weak” references? Why are they important and how can they be used to help control memory management and avoid memory leaks?](https://github.com/tsaihong1995/InterviewQuestion/blob/main/README.md#what-are-strong-and-weak-references-why-are-they-important-and-how-can-they-be-used-to-help-control-memory-management-and-avoid-memory-leaks)

- [Thread Management](https://github.com/tsaihong1995/InterviewQuestion#thread-management)
    - [What is the difference between synchronous and asynchronous task?](https://github.com/tsaihong1995/InterviewQuestion#what-is-the-difference-between-synchronous-and-asynchronous-task)
    - [What is GCD and how is it used?](https://github.com/tsaihong1995/InterviewQuestion#what-is-gcd-and-how-is-it-used)


# Interview Questions & Answers


## Swift Fundemantal Knowledge

### What are struct and class in iOS? What is the difference? When would you use each?

The common parts between struct and class:
 - Both can define properties and functions in classes/structs
 - Both can has initializers to initialize thier original state with init()
 - Can use **extension** to extended the functionality
 - Both can conform to protocols.


The stuct is ***Value*** type. In Swift, the struct type will be passed as values rather than references which means value type is an independent instance and holds its data in its own memory allocation. One of the Pros is if there is a large object it needs to pass around. Using structs can improve the performance.

In Swift **struct**, **Array**, **String**, **Dictionary**, **tuple** are value types.

Structs are preferable to use if
 - It doesn't have to inherit value from other types.
 - When programmer only want to encapsulate some data.

<details open>
<summary>Struct Example</summary>

```swift
struct Bike {
    let brand: String
    var model: String
}

var bike1 = Bike(brand: "Giant", model: "G-1")

let bike2 = bike1

bike1.model = "G-2"

print(bike1)
print(bike2)

/*
Output:
Bike(brand: "Giant", model: "G-2")
Bike(brand: "Giant", model: "G-1")

Note: Only Bike1's model has changed.
*/
```
</details>


The ***class*** is reference types which stored on heap. The class also has ability:
- Inheritance from the other class.
- Classes can be deinitialized.

<details open>
<summary>Class Example</summary>

```swift
class Person: CustomStringConvertible {
    var age: Int
    var name: String

    var description: String {
        return "Age \(age) - Name \(name)"
    }

    init(age: Int, name: String) {
        self.age = age
        self.name = name
    }
}


let person1 = Person(age: 20, name: "Hung-Chun")

let person2 = person1

person2.age = 18

person1.name = "Carter"

print(person1)
print(person2)

/*
 Output:
 Age 18 - Name Carter
 Age 18 - Name Carter
 
 Note: Because class is reference type, when we assign the person2 = person1, we indicate that person2 point to the person1's address. So when we modify the person1 or 2's property value, it will modify both's.
 */



```
</details>



### What is framework in iOS?

The framework in iOS is like the container with the various resources (images, data files, UI objects, etc.) Framework also can be library or containing many libraries, collection of scripts.


### How can you store information within your iOS app?

There are many different ways that we can achieve data persistence in Swift
- **UserDefault**
UserDefault usually store small amount of user's data like (settings, preferences, etc.)
-Limitation :
	- UserDefault is not encrypted
	- Unit testing user defaults can occur some false positives.
- **Keychain**
It usually use to save the sensitive user data. For example: Password, login information...
-Pros:
	- Thread safety
	- All information in keychain is encrypted

- **Saving file to disk**
We can also encode the data to the JSON file then save it to the user's local device. When the application is running or execute, it will read/write the data from the path.

- **Core Data**
Core Data is Apple's persistency framework which based on an object graph. It can uss for saving the app's permanet data for offline use or cache the data.
- **SQLite**

### How do you cast between types?

> Apple - A constant or variable of a certain class type may actually refer to an instance of a subclass behind the scenes. Where you believe this is the case, you can try to downcast to the subclass type with a type cast operator (as? or as!).

Downcasting can be done in two ways:
- Conditional downcasting (as?).
- Forced downcasting (as!)

Conditional Downcasting
While using the conditional downcasting, it will always return an optional value. That's mean when the downcasting is not available, it will always return _nil_.

Forced Downcasting
When we use the Forced Downcasting, we need to make sure that the downcast will always succeed. Otherwise, it will occure runtime error if we try to downcast to an unvailable class type.

Upcasting can lets the base class object to cast to its superclass.

```swift
class PizzaStore {
    var establish :Int?
    
    init(establish:Int?) {
        if let establish = establish {
            self.establish = establish
        }
    }
}

class Dominos: PizzaStore {
    var name: String?
    
    init(name:String?, establish:Int?) {
        if let name = name {
        self.name = name
        }
        super.init(establish: establish ?? 0)
    }
}

class PizzaHut: PizzaStore {
    var hasApplePie: Bool?
    
    init(hasApplePie:Bool?, establish:Int?) {
        if let hasApplePie = hasApplePie {
            self.hasApplePie = hasApplePie
        }
        super.init(establish: establish ?? 0)
    }
}

let pizzaStoreArray = [Dominos(name: "Domino's", establish: 1960), PizzaHut(hasApplePie: false, establish: 1958)]

let dominoPizzaStore = pizzaStoreArray[0] as! Dominos
let dominoPizzaStoreAsPizzaStore = dominoPizzaStore as PizzaStore
```


### What is the difference between var and let?

The **let** keyword defines a constant which means the property that we don't want it to change their value.

> Note: The optional and the weak can't be written using let.

The **var** defines a variable which can let us to modify it's value.

### What is the difference between implicit and explicit?

When referring to something as implicit or explicit, it is often referring to how an object is declared. In the two examples below:

<details open>
<summary>Swift</summary>
    
```swift
var name: String = "onthecodepath" // explicit
var name = "onthecodepath" // implicit
```
</details>

In the first line above, the name variable is *explicitly* declared since the type of the variable follows the name of the variable. In the second line, the String type is not explicitly declared. However, Swift is able to infer that name is of a String type since the value that it is being set as is of a String type.

### Tell me about enum in Swift language. Can you give useful examples of enum associated values?

An enumeration (enum) is value type in a type-safe way. It is not mandotary to provide the initial value for the enumeration.

Here’s an example for the four main points of a compass:

```swift
enum Direction {
    case north
    case south
    case east
    case west
}
```

 > Note: Swift enums don’t have integer values set by default. In example above north, south, east, west don’t implicitly equal 0 ,1 ,2 ,3. Instead these enumeration cases are values in their own right of type _Direction_.

**Important**: A swich statement must be exhaustive if we want to use the enumeration in it. If we use the _default_, it is not nessasary to include all the cases.

```swift
let someAnimal = Animal.human
switch somePlanet {
case .human:
    print("This is human species")
default:
    print("The animal is other than human")
//It is no need to include all the cases in the Animal enumeration.
}
// Prints "The animal is other than human"
```

- Associate values lets us add more information to our enumeration.

The scenario is "In my SwiftUI application, I want to present different views modal, when I selected the certain button." In this case, we can use the enum associate value helps us to tackle down this problem.

Requirement:
1. We have 3 different view we want to provide to user to select
-  Home View
-  Favorite View
- Setting View

Step 1. Let us define the MyOption which will contain those three views

```swift

//We want to present the implicitly our each view name, so we need to conform to String and CaseIterable.

enum UserOption: String,  CaseIterable {
	case setting = "Setting View"
	case action1 = "Action 1"
	case action1 = "Action 2"
}
```
Step 2. Let's wrap the UserOption enum into the other enum because we will use the function to determine which case user is selected and generate the corresponding view.

```swift
enum OtherViews {
    enum UserOption: String,  CaseIterable {
        case setting = "Setting View"
        case action1 = "Action 1"
        case action2 = "Action 2"
    }
    
    static func optionView(optionSelected: UserOption) -> AnyView {
        switch optionSelected {
        case .setting:
            return AnyView(Text("Showing Setting View"))
        case .action1:
            return AnyView(Text("Showing Action1 View"))
        case .action2:
            return AnyView(Text("Showing Action2 View"))
        }
    
    }
}
```

Step 3. Let create our view to include those fucntionality.

```swift
import SwiftUI

struct ContentView: View {
    @State private var isShowingModal = false
    @State private var optionSelected: OtherViews.UserOption = .action1
    var body: some View {
        VStack {
            Picker(selection: $optionSelected, label: Text("")) {
                
                ForEach(OtherViews.UserOption.allCases, id: \.self) { option in
                    Text(option.rawValue.capitalized).tag(option)
                    
                }
            }.pickerStyle(SegmentedPickerStyle())
            Button("Show Modal") {
                self.isShowingModal.toggle()
            }
            .sheet(isPresented: $isShowingModal) {
                OtherViews.optionView(optionSelected: optionSelected)
            }
        }
        .padding()
    }
}

struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
    
}
```



### What is Core Data?

Core Data is a framework that is used to manage model layer objects (Like the M in MVC). It has the ability to persist object graphs to a persistent store. Data is organized into relational entity-attribute model.

#### When would you use Core Data over NSUserDefault?

- Most of time, NSUserDefault is used to store small quantity of data (settings, preferences, etc.). The UserDefault object known as NSUserDefault.
- Core Data is used to store a large amount of data.


### What is NSFetchRequest?

NSFetchRequest is the class responsible for fetching from Core Data. Fetch requests can be used to fetch a set of objects meeting a certain criteria, individual values and more. ([source](https://medium.com/ios-os-x-development/50-ios-interview-questions-and-answers-part-2-45f952230b9f))

## Debugging

### How do you debug and profile code on iOS application?
- Using NSLog and print functions can be used for output into console.
- Set the breakpoints and using the Debug bar and Variables view to monitor the object or class.
- Some Senior Developer will use the Crash Logs to gain more information and try to find out the specific problem.

### How do you optimize scrolling performance of dynamically sized table or collection views?

Firstly, I will analyze which element or reason cause the choppy loading while using the collection views. Most of the time it is because we load the data (Image, text, object) synchronously.

Imangine this scenario in the restaurant. In the restarant there are 3 chief but only have one server. The customer order the bunch of the dishes (Just like user scrolling down the collection view). Sometime the kitchen (backend) might able to handle this big volume, but we only open one thread to serve our content which is data.

So we might can do following strategies to improve the performence. 
- **Splitting out the long-running operations and move them to a background thread.**
This allows us to handle any events when they happen, on the main thread. When the background operation completes, you can make any required UI updates, based on the operation, on the main thread.
- **Loading the data asynchronously **
We can use Grand Central Dispatch (GCD) to execute tasks concurrently. The main idea is to create a closure to handle how the cell is updated once the data is loaded.
- **Prefetching the data**
The problem occur while we fetch big amount of the data. But we also can try to prefethching the oncoming data. For example, the view only present the data 1-10, meanwhile we let our program already fetch the next 11-20 and 21-30 items. Whenever the user scroll down, we continually fetching the oncoming data.

### Explain your process for tracing and fixing memory leaks.

### You’ve just been alerted that your new app is prone to crashing. What do you do?




## Design Patterns

### What is Singleton Pattern?

The Singleton design pattern ensures that only one instance exists for a given class and that there’s a global access point to that instance. It usually uses lazy loading to create the single instance when it’s needed the first time. ([source](https://medium.com/ios-os-x-development/ios-interview-questions-13840247a57a))

### What is the delegation pattern? 

The delegation pattern is a powerful pattern used in building iOS applications. The basic idea is that one object will act on another object's behalf or in coordination with another object. The delegating object typically keeps a reference to the other object (delegate) and sends a message to it at the appropriate time. It is important to note that they have a one to one relationship.

### What is MVC?

MVC stands for **Model-View-Controller**. It is a software architecture pattern for implementing user interfaces. 

MVC consists of three layers: the model, the view, and the controller.
- The **model layer** is typically where the data resides (persistence, model objects, etc)
- The **view layer** is typically where all the UI interface lies. Things like displaying buttons and numbers belong in the view layer. The view layer does not know anything about the model layer and vice versa.
- The **controller (view controller)** is the layer that integrates the view layer and the model layer together. 

### What is MVVM?

MVVM stands for **Model-View-ViewModel**. It is a software architecture pattern for implementing user interfaces.

MVVM is an augmented version of MVC where the presentation logic is moved out of the controller and into the view model. The view model is responsible for handling most, if not all, of the view's display logic. 

A common occurence in MVC is where you have a massive-view-controller (some joke this is what MVC stands for). In order to shrink the size of your view controller and make the logic and readibility of your code easier to follow along, the MVVM will be used. 

## General / Uncategorized

### What considerations do you need when writing a UITableViewController which shows images downloaded from a remote server?

- Only download the image when the cell is scrolled into view (when cellForRowAtIndexPath is called)
- Download the image asynchronously on a background thread so as not to block the UI so the user can keep scrolling
- When the image has downloaded for a cell, check if that cell is still in the view or whether it has been re-used by another piece of data. If the cell has been re-used, then the image should be discarded. Otherwise, it should be switched back to the main thread to change the image on the cell. ([source](https://www.codementor.io/mattgoldspink/ios-interview-tips-questions-answers-objective-c-du1088nfb))

### What is a protocol? How do you define your own protocol? 

A protocol defines a list of required and optional methods for a class that adopts the protocol to implement. Any class is allowed to implement a protocol so that other classes can send message to it based on the protocol methods without knowing the type of class. An example of how a protocol is defined:

A common instance protocols are used is providing a DataSource for UITableView or UICollectionView ([source](https://www.codementor.io/mattgoldspink/ios-interview-tips-questions-answers-objective-c-du1088nfb))

### What is JSON? What are the pros and cons?

JSON stands for JavaScript Object Notation. According to [wiki](https://en.wikipedia.org/wiki/JSON), it is a file format that uses human-readable text to transmite data objects consisting of attribute-value pairs and array data types. 

Pros:

- It is lighter than XML meaning that it can represent the same data in XML in fewer bytes. This makes network transmissions and read/writes faster
- Since it is native to JavaScript, computationally-expensive XSL tranformations are not needed in order to extract data

Cons:

- Not as widespread as XML
- Data is not readily streamable and has to be broken up into individual objects
- Can't use comments

### What is the difference between not-running, inactive, active, background and suspended execution states?

- **Not-running state** occurs when the app either has not be launched or was running but was terminated by the system.
- **Inactive state** occurs where the app runs in the foreground but is currently not receiving events. (It may be executing other code though). This state is typically brief as apps transitions to other states.
- **Active state** is where the app is running in the foreground and receiving events. This is the normal mode for foreground apps.
- **Background state** occurs when the app is in the background and executing code. Apps typically enter this state on their way to being suspended. Apps that require extra execution time may remain in this screen longer. Apps being launched directly into the background enters this state instead of inactive state.
- **Suspended state** is where the app is in the background but it is not executing code. Apps will remain in memory, but are removed by the system if low-memory condition occurs in order to make more space for foreground apps.

### Is it faster to iterate through an NSArray or an NSSet?

It depends. NSSet is faster to iterate through if the order of the items in the collection is not important. The reason is because NSSet uses hash values in order to find items while NSArray has to iterate through its entire contents to find a particular object. ([source - #25](https://medium.com/cocoaacademymag/25-ios-interview-questions-and-answers-for-junior-developers-19bfe6e99b0))

### What is KVO?

KVO stands for *Key-Value Observing*. It allows a controller or class to *observe* when a property value changes. 

## Memory Management

### Why do you generally create a weak reference when using self in a block?

Sometimes it is necessary it capture self in a block such as when defining a callback block. However, since blocks maintain strong references to any captured objects including self, this may lead to a strong reference cycle and memory leak.

Instead, capturing a weak reference to self is recommended in order to avoid this issue


### What is memory management handled on iOS?

iOS uses something called ARC which stands for Automatic Reference Counting. When an object is said to have a strong reference to it, ARC increase its retain count by 1. When the retain count of an object reaches 0, the object will typically be deallocated if there are no more strong references to it. Unlike garbage collection, ARC does not handle reference cycles automatically. 

> What is  ARC?

Automatic Reference Counting (ARC) provides automatic memory management for all Objective-C object. Developer no need to manually reain and release operations.

### What is the difference between *weak* and *strong*?

First, objects are *strong* by default.

- ***Strong*** means that the reference count will be increased and the reference to it will be maintained through the life of the object. 
- ***Weak***, means that we are pointing to an object but not increasing its reference count. It’s often used when creating a parent child relationship. The parent has a strong reference to the child but the child only has a weak reference to the parent. ([source](https://medium.com/ios-os-x-development/ios-interview-questions-13840247a57a))

Common instances of ***weak*** references are delegate properties and subview/controls of a view controller's main view since those views are already strongly held by the main view. ([source](http://stackoverflow.com/questions/11013587/differences-between-strong-and-weak-in-objective-c))

### What is a memory leak?

A memory leak commonly occurs when an object is allocated in such a way that when it is no longer in use or needed, it is not released. In iOS programming, you create certain objects with weak references in order to avoid a strong to strong relationship that creates a retain cycle and a memory leak.

### What is a retain cycle?

Retain cycles can occur when memory management is based on retain count. This typically occurs when two objects strongly reference each other. As a result, the retain count of either object will never reach zero and deallocated from memory (hence retaining each other). 

### What is the difference between *copy* and *retain*?

Calling *retain* on an object will increase its *retain* count by one. When the *retain* count of an objective reaches 0, the object will be deallocated and released from memory.

When you *retain* an object, you share the same version with whoever passed the object to you. But when you *copy* an object, you do not share the same version of the object that was passed to you. Instead, a duplicate of that object is created with duplicated values.

### What is the difference between a stack vs a heap?

A stack is a region of memory where data is added or removed in a last-in-first-out (LIFO) order. According to [Ates Goral](http://stackoverflow.com/questions/79923/what-and-where-are-the-stack-and-heap), it is the memory set aside as scratch space for a thread of execution. Meanwhile the heap is memory set aside for dynamic allocation. Unlike the stack, you can allocate a block at any time and free it at anytime. 

Note: In Objective-C, all objects are always allocated on the heap, or at least should be treated as if on the heap. 

### What are “strong” and “weak” references? Why are they important and how can they be used to help control memory management and avoid memory leaks?

When developer create the objects the default references is set as *strong*, and this will prevents the ARC(Automatic Reference Count) from removing the object from memory. If we don't deinitialized the object while we are not using, this will cause the memory leak. Upon time, the application might occur the error which is run out of the memory.

So the *weak* reference is to slove this issue, when we create a weak reference we are pointing to an object without increasing reference count.

Common instances of ***weak*** references are delegate properties and subview/controls of a view controller's main view since those views are already strongly held by the main view. ([source](http://stackoverflow.com/questions/11013587/differences-between-strong-and-weak-in-objective-c))


## Thread Management

### What is the difference between synchronous and asynchronous task?

Synchronous tasks wait until the task has been completed while asynchronous tasks can run in the background and send a notification when the task is complete.


### What is GCD and how is it used?

GCD stands for Grand Central Dispatch. According to [Ray Wenderlich](https://www.raywenderlich.com/60749/grand-central-dispatch-in-depth-part-1), it offers the following benefits
- Improving your app's responsiveness by helping to defer computationally expensive tasks and run them in the background.
- Providing an easier concurrency model than locks and threads and helps to avoid concurrency bugs.
- Potentially optimize your code with higher performance primitives for common patterns such as singletons.

In other words, GCD provides and manages queues of tasks in the iOS app. This is one of the most commonly used API to manage concurrent code and execute operations asynchronously. Network calls are often performed on a background thread while things like UI updates are executed on the main thread.


## Unit Testing / UI Testing

### What is the purpose of Unit/UI testing? What are the benefits?

Unit/UI testing are the basic of test-driven development. This development approach allows you to codify requirements for your code before you implement it. Unit tests are important to make sure that code meets its design and requirements and behaves as expected. Parts of the program are segregated and tested to ensure that individual parts are working correctly. 

# Algorithm Resources

#### [swift-algorithm-club](https://github.com/raywenderlich/swift-algorithm-club): Algorithm and data structures in Swift









