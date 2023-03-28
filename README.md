# rectangleObjects

## Challenge Description: 
Create a class called "Rectangle" that represents a rectangle with a given width and height. The class should have methods to calculate the area and perimeter of the rectangle. Additionally, create a function called "find_largest_rectangle" that takes in a list of Rectangle objects and returns the Rectangle with the largest area.

### Class: 
Rectangle

#### Attributes:
- width (float)
- height (float)

#### Methods:
- __init__(self, width, height): Initializes a new Rectangle object with the given width and height.
- area(self): Calculates and returns the area of the rectangle.
- perimeter(self): Calculates and returns the perimeter of the rectangle.

### Function: 
find_largest_rectangle(rectangles)

#### Parameters:
- rectangles (list of Rectangle objects): A list of Rectangle objects.

#### Returns:
- The Rectangle object with the largest area.

## Tests:

```python
# Test 1: Creating a Rectangle object
rect = Rectangle(4, 5)
assert rect.width == 4
assert rect.height == 5

# Test 2: Calculating the area of a Rectangle
rect = Rectangle(4, 5)
assert rect.area() == 20

# Test 3: Calculating the perimeter of a Rectangle
rect = Rectangle(4, 5)
assert rect.perimeter() == 18

# Test 4: Finding the largest rectangle in a list
rect1 = Rectangle(4, 5)
rect2 = Rectangle(3, 6)
rect3 = Rectangle(2, 8)
rectangles = [rect1, rect2, rect3]
assert find_largest_rectangle(rectangles) == rect3
```
