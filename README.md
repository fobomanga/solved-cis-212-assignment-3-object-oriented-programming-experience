Download Link: https://assignmentchef.com/product/solved-cis-212-assignment-3-object-oriented-programming-experience
<br>
The goal of this assignment is to gain basic Object-Oriented Programming experience working with Java classes and interfaces.

For this assignment, you’ll implement a hierarchy of Java classes that share a common interface.  You’ll then be able to create a data structure using this interface type and populate it with various instances of classes inheriting from the interface.

<ol>

 <li> Implement a new interface named Measurable with a single method named getArea() which takes no arguments and returns a double.</li>

 <li> Implement a new class named Rectangle that implements Measurable. Provide a class constructor which takes arguments appropriate for creating a 2D rectangle and implement the getArea() method to return the area of the rectangle.</li>

 <li> Implement a new class named Box that extends Rectangle. Provide a class constructor which takes arguments appropriate for creating a 3D box and implement the getArea() method to return the total surface area of the box.</li>

 <li> Implement a new class named Circle that implements Measurable. Provide a class constructor which takes arguments appropriate for creating a 2D circle and implement the getArea() method to return the area of the circle.</li>

 <li> Implement a new class named Sphere that extends Circle. Provide a class constructor which takes arguments appropriate for creating a 3D sphere and implement the getArea() method to return the surface area of the sphere.</li>

 <li> Implement a new class named Main with a public static main() method and private static nextDouble() and calculateSum() methods:

  <ul>

   <li> The nextDouble () method should simply return a double on the range (0.0, 1.0] (i.e., 0.0 exclusive to 1.0 inclusive) so that there are no 0.0 areas. Hint: see java.util.Random nextDouble and java.lang.Double MIN_VALUE.</li>

   <li> The calculateSum () method should take an ArrayList of type Measurable as an argument and return the sum of all areas in the list.</li>

   <li> The main() should create an ArrayList of type Measurable and populate that list with 1000 random instances of your Measurable classes from parts 2-5 (i.e., 25% chance of that each instance is one of the four classes). Use the nextDouble() method described above to generate random dimensions to pass into the Measurable constructors. Track the number of instances of each class created and print the results.</li>

  </ul></li>

</ol>

Finally call the calculateSum() method and print the result.

<ol start="7">

 <li> Write code that is clear and efficient. Specifically, your code should be indented with respect to code blocks, avoid unnecessarily repetitive code, avoid code that is commented out or otherwise unused, use descriptive and consistent class/method/variable names, etc.</li>

</ol>

Your output should look something like:

rects: 244 boxes: 233 circles: 256 spheres: 267 sum: 1801.4553056918676