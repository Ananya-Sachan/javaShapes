# javaShapes
# Overview
This Java program allows users to calculate the area, perimeter, and volume of various geometric shapes. It includes classes for shapes such as Circle, Rectangle, Square, Sphere, Cylinder, and Pyramid. The program is menu-driven, allowing users to select a shape, input the required dimensions, and obtain the calculated results.

# Files
Main.java: Contains the main method to run the program and interact with the user.

Shape.java: Defines the abstract class Shape, serving as the base class for all shapes. It includes methods for showing the shape, calculating the area, and calculating the perimeter.

Volume.java: Defines the interface Volume, which includes the method for calculating the volume of shapes that have volume.

Circle.java, Rectangle.java, Square.java, Sphere.java, Cylinder.java, Pyramid.java: Classes for individual shapes, implementing the necessary methods for calculation.

ShapeCalculator.java: Contains the ShapeCalculator class, which handles the calculation process based on the user's input.
# How it Works
The program starts by presenting a menu of available shapes to the user.
When a shape is selected, the program prompts the user to input the required dimensions.
Based on the user's input, the program creates an instance of the corresponding shape class (e.g., Circle, Rectangle) and calculates its area and perimeter.
If the selected shape has volume (e.g., Sphere, Cylinder, Pyramid), the program also calculates its volume.
The calculated results (area, perimeter, and volume) are then displayed to the user.
# Usage
Compile all Java files using a Java compiler (e.g., javac *.java).

Run the Main class (e.g., java Main).

Follow the prompts to choose a shape and input the required dimensions.

View the calculated results for the selected shape.
