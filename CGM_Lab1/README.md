# Computer Graphics Lab – Assignment 1

## Basic Graphics Primitives

### Objective

To write a C++ program using the `graphics.h` library to draw the following basic graphics primitives in a single graphics window:

1. Straight Line
2. Circle
3. Rectangle
4. Triangle

---

## Technologies Used

* C++
* GCC / G++
* `graphics.h`
* XBGI (`libXbgi`)
* VS Code

---

## Program File

**File:** `CG_LabAssignement_BasicShapes.cpp`

---



## Graphics Primitives

### 1. Straight Line

A straight horizontal line is drawn using the `line()` function.

### 2. Circle

A circle is drawn using the `circle()` function.

### 3. Rectangle

A rectangle is drawn using the `rectangle()` function.

### 4. Triangle

The triangle is created by drawing three connected straight lines using the `line()` function.

---

## Functions Used

| Function       | Description                                       |
| -------------- | ------------------------------------------------- |
| `initgraph()`  | Initializes the graphics environment              |
| `line()`       | Draws a straight line between two points          |
| `circle()`     | Draws a circle with a specified center and radius |
| `rectangle()`  | Draws a rectangle using two corner coordinates    |
| `getch()`      | Waits for a key press                             |
| `closegraph()` | Closes the graphics environment                   |

---

## Header File Used

### `graphics.h`

The `graphics.h` header provides the graphics functions used in the program, including:

* `initgraph()`
* `line()`
* `circle()`
* `rectangle()`
* `getch()`
* `closegraph()`

In this project, `graphics.h` is provided through the **XBGI library** on openSUSE Tumbleweed.

---

## Compilation and Execution

The program can be compiled using `g++` from the terminal.

### Compile

```bash
g++ CG_LabAssignement_BasicShapes.cpp -o CG_LabAssignement_BasicShapes -lXbgi
```

### Run

```bash
./CG_LabAssignement_BasicShapes
```

---

## System Requirements

* openSUSE Tumbleweed or a compatible Linux distribution
* C++ compiler (`g++`)
* XBGI graphics library
* `graphics.h`
* Terminal or a compatible C++ development environment

### Required openSUSE Package

```bash
sudo zypper install libXbgi-devel
```

---

## Output

The program displays the following four basic graphics primitives in a single graphics window:

* Straight Line
* Circle
* Rectangle
* Triangle

A screenshot of the program output is included with the assignment submission.

---

## Learning Outcomes

After completing this assignment, the following concepts are understood:

* Basics of computer graphics programming
* Initialization of a graphics environment
* Two-dimensional coordinate system
* Drawing basic graphics primitives
* Using the `graphics.h` library
* Drawing geometric shapes using coordinates
* Understanding how graphical objects are represented using points and coordinates

---

## Student Details

**Name:** Bhumika Meghani
**Roll Number:** IC-2K24-27
**Course:** MCA (5 years)
**Subject:** Computer Graphics
**Assignment:** Lab Assignment 1

---

## Conclusion

The program successfully demonstrates the implementation of `graphics.h` library. 
