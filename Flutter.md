# Flutter Interview Questions

1. **What is Flutter?**
    
    Flutter is an open-source mobile application development framework created by Google. It allows developers to create high-quality, high-performance mobile applications for iOS, Android, and the web using a single codebase.

2. **What are the advantages of Flutter?**
    
    The advantages of Flutter include:

    - Hot reload feature allows developers to see changes in real-time
    - Fast development process and easy to learn
    - Cross-platform development with a single codebase
    - Great user interface and user experience
    - Supports a wide range of widgets and APIs

3. **What is the difference between StatelessWidget and StatefulWidget?**
    
    StatelessWidget is a type of widget in Flutter that does not have any mutable state. It is used to create widgets that do not change over time. StatefulWidget, on the other hand, is a widget that has mutable state. It is used to create widgets that change over time, such as a button that changes color when pressed.

4. **What is the purpose of the build() method in Flutter?**
    
    The build() method in Flutter is used to describe the user interface of a widget. It returns a tree of widgets that describes what the widget should look like. The build() method is called every time the widget needs to be rebuilt, which can happen for various reasons such as state changes or user interaction.

5. **What is the pubspec.yaml file in Flutter?**
    
    The pubspec.yaml file in Flutter is a YAML file that is used to define the dependencies and other metadata of a Flutter project. It lists the packages that the project depends on, as well as other project-specific information such as the version number, author, and description.

6. **How does Flutter handle asynchronous programming?**
    
    Flutter uses the async/await syntax to handle asynchronous programming. It allows developers to write asynchronous code that looks synchronous and is easy to read and understand. Flutter also provides a number of built-in methods and widgets to handle common asynchronous tasks, such as making HTTP requests or loading images.

7. **What is a widget in Flutter?**
    
    A widget in Flutter is a building block of the user interface. It can represent anything from a button to an entire screen. Widgets can be combined to create more complex widgets, and they can be nested inside other widgets to create a hierarchy of user interface elements.

8. **What is the difference between setState() and StatefulWidget?**
    
    setState() is a method in Flutter that is used to update the state of a widget. It triggers a rebuild of the widget and its children. StatefulWidget, on the other hand, is a type of widget in Flutter that has mutable state. It is used to create widgets that change over time, such as a button that changes color when pressed.

9. **What is the purpose of the initState() method in Flutter?**
    
    The initState() method in Flutter is called when a widget is inserted into the widget tree. It is used to initialize the state of the widget, such as setting default values for variables or making network requests to fetch data. The initState() method is only called once during the lifetime of a widget.

10. **What is the purpose of the dispose() method in Flutter?**
    
    The dispose() method in Flutter is called when a widget is removed from the widget tree. It is used to clean up any resources used by the widget, such as closing streams or stopping animations. The dispose() method is only called once during the lifetime of a widget.
