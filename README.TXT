Project: network-v2
Authors: Michael Kölling and David J. Barnes

This project is part of the material for chapter 8 of the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It implements a second (partly improved) version of a news feed 
for a social network.

2: Because the show() method reads into each object inside its ArrayLists, any
change done to the objects also uptades the result they give when the show()
method is called. This is the same behavior as the time since it was first created.
4: MessagePost no longer works because it stopped inheriting from Post.
5: Inherited methods directly comes from an inherited class.
7: When the super method is used, it uses the same constructor method as its superclass.
9: From top to bottom:
Food item,
Cereal, Fruit, Dessert,
Bread, Baguette, Orange, Apple, Ice cream, Chocolate mousse.
10: The touch pad and the mouse are both imput devices for the cursor.
11: The square because they also count as rectangles, but rectangles do not count as squares.
12: a: Person p1 = new Student();, Person p2 = new PhDStudent();, Student s1 = new PhDStudent();.
b: p1=s1; and s1=phd1; because the supertype variable already holds a subtype object.
14: Nothing, because it looks into Post, not EventPost.
