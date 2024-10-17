# Experiment 11: Classes and Objects in C++

This repository demonstrates the study and implementation of object-oriented programming concepts, specifically classes and objects, in C++.

## Files in the Repository

- **method.cpp**: Defines methods inside the class to demonstrate encapsulation.
- **method_outside.cpp**: Defines methods outside the class to separate declaration and definition.
- **oops.cpp**: Demonstrates basic OOP principles like inheritance and polymorphism.
- **volume_cuboid.cpp**: Calculates the volume of a cuboid using a class.
# Algorithms

## Basic C++ Class

### Algorithm

1. **Start.**  
2. **Define Class:**  
   - Define the class `Student` with the following public data members:  
     - `name` (string)  
     - `age` (float)  
     - `branch` (string)  
     - `year` (string)  
     - `result` (float)  
3. **Define Method:**  
   - Inside the class, define a public method `display()` to display student details:  
     - Print the values of `name`, `age`, `branch`, `year`, and `result`.  
4. **In `main()` Function:**  
   - Create an object `S1` of the `Student` class.  
   - Assign values to the attributes of `S1`:  
     - Set `name` to `"Adrish Purkayastha"`.  
     - Set `age` to `20`.  
     - Set `branch` to `"EnTC"`.  
     - Set `year` to `"2nd"`.  
     - Set `result` to `9.03`.  
   - Call the `display()` method on `S1` to print the details.  
   - Create another object `S2` of the `Student` class.  
   - Assign values to the attributes of `S2`:  
     - Set `name` to `"Aditya Sthawarmath"`.  
     - Set `age` to `19`.  
     - Set `branch` to `"EnTC"`.  
     - Set `year` to `"2nd"`.  
     - Set `result` to `8.64`.  
   - Call the `display()` method on `S2` to print the details.  
5. **End.**

---

## Method Definition

### Algorithm

1. **Start.**  
2. **Define Class:**  
   - Define a class `Student`.  
   - Inside the class, define a public method `my_method()`.  
3. **Method Implementation:**  
   - In the method, print the message: `"I'm studying in 2nd year."`  
4. **Create `main()` Function:**  
   - Inside the `main()` function:  
     - Declare an object `s1` of class `Student`.  
     - Call the method `my_method()` on the object `s1`.  
5. **End.**

---

## Volume of Cuboid

### Algorithm

1. **Start.**  
2. **Define Class:**  
   - Define a class `Area_cuboid`.  
   - Declare public variables: `l`, `b`, `h`, and `volume`.  
3. **Define Methods:**  
   - Define the following methods:  
     - `input()`: Takes input for length, breadth, and height of the cuboid.  
     - `calculate()`: Computes the volume of the cuboid using the formula:  
       - `volume = l * b * h`.  
     - `output()`: Prints the volume of the cuboid.  
4. **Create `main()` Function:**  
   - Inside the `main()` function:  
     - Declare an object `C1` of class `Area_cuboid`.  
     - Call the method `input()` on the object `C1`.  
     - Call the method `calculate()` on the object `C1`.  
     - Call the method `output()` on the object `C1`.  
5. **End.**
