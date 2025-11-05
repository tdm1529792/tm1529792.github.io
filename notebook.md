## Flutter Definitions

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
| main()     | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` | you launch a smartphone app |  |
| MaterialApp   | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` | layout and colors of a phone’s home screen |  |
| Scaffold     | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  |  |
| Column     | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
| Row     | A widget that shows things side-by-side. | `Row(...)` |  |  |
| Container     | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
| Text     | A widget to display text on the screen. | `Text('Hello')` |  |  |
| Image.network     | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
| ElevatedButton     | A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
| onPressed     | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
| StatelessWidget     | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
| StatefulWidget     | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
| Navigator     | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |
| Padding     | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |
| Center     | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
| Wrap     | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
| @override     | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
| build()     | The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |
| BuildContext     | Required in every widget class to describe what to show. | `build` |  |  |
| build     | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
| super.key     | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
| const     | A keyword that means the value won't change and is set once. | `const` |  |  |










| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |

|------|------------|--------------------------|-------------------|-------------|

|      | A named container used to store a value that may change. | `var x = 5;` |  |  |

|      | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |

|      | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  |  |

|      | A sequence of characters used to represent words or text. | `"Hello World"` |  |  |

|      | Whole number values. | `int age = 16;` |  |  |

|      | Number values with decimals. | `double age = 16.2;` |  |  |

|      | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |

|      | A collection of values in a specific order. | `List<String> names = [];` |  |  |

|      | A special value that means “nothing.” | `String? name = null;` |  |  |
|      | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |
|      | The information passed into a function to change how it works. | `greet(String name)` |  |  |
|      | The result a function gives back. | `return total;` |  |  |
|      | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
|      | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
|      | A specific version of a class. | `Dog myDog = Dog();` |  |  |
|      | A variable that belongs to a class/object. | `String name;` |  |  |
|      | A function that belongs to a class. | `void bark() {}` |  |  |
|      | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|      | A function that does not return a value. | `void printMessage() {}` |  |  |
||||||













