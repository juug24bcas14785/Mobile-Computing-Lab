Aim
In this blog, we will take a look at how to draw simple shapes on the screen using Canvas and Paint, and how we can design our own custom View for the Android application. 

Algorithm 


To start, open Android Studio and create a new project using the “Empty Activity” template. 

Step 2: Choose the programming language as Java and complete the project setup steps. 
Open the project and verify that the app level AndroidManifest.xml file has MainActivity as the launcher. 

Now, let’s create a new MyView class. 

Inside the class constructor, create a Paint object and set its color, stroke and style. 

The onDraw method of the View class must be overridden. 

Use the appropriate methods to draw different shapes and text: drawLine(), drawRect(), drawCircle(), drawOval(), and drawText(). 

Open the "MainActivity.java" file. 

Create an object of the Custom View Class. 
- drawLine() to draw a line 
- drawRect() to draw a rectangle 
- drawCircle() to draw circles 
- drawOval() to draw ovals 
- drawText() to show the text on the screen 

Step 8: Open the MainActivity.java file and create an object of the custom view class.

  