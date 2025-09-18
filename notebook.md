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
