before we dive into the linear algebra we need to learn vectors

### vector 
	-> magnitude and direction

magnitude - value
direction - in which direction the value points

It can be also described as 

#### example

 5kmph in east

here 5Kmph is the magnitude ( also called as scalar )
and also in east represent the direction

in more practical way we can say

(5,0)

here the direction is positive X axis and value is 5

### co-ordinate system 

Coordinates systems are often used to specify the position of a point, but they may also be used to specify the position of more complex figures such as lines, planes, circles or spheres.

Few co-ordinate systems are 

* number line
* cartesian coordinate system ( used in geomentry - xy coordinate system)
* polar coordinate system ( theta - sin,cos )

The use of a coordinate system allows problems in geometry to be translated into problems about numbers and vice versa

 In x,y co-ordinate has two special vectors i^ (along x-axis) and j^ (along y-axis)

 i^ and j^ -> basis vectors of xy co-ordinate system

 data representation is 

 [5]  
 [3]

 here i^ is 5 ( 5 direction toward the positive x axis)
      j^ is 3 ( 3 direction toward the positive y axis)

 choosing two vector also we can do the same except when two vector lies in same line or two scalar lies in origin.

 when two vector lies in same line we call that as linear dependent

 if not we call that as linear independent

 anytime scaling two vector and adding them is called *linear combination*

### Transformation

Because there are often many different possible coordinate systems for describing geometrical figures, it is important to understand how they are related. Such relations are described by coordinate transformations

example:

to convert cartesian coordinate(x,y) => Polar coordinate(r,0) we use

0 - theta

x = r * cos0

y = r * sin0

### linear transformation

linear means it follows two things

* line must remain line.
* The origin must remain in fixed place.

simply linear transformation as keeping grid lines parallel and evenly spaced.

these transformations can be described using only a handful of numbers.

The coordinates of where each basis vector lands.

Matrices give us a language to describe these transformations

where the columns represent those coordinates and matrix-vector multiplication is just a
way to compute what that transformation does to a given vector.

every time you see a matrix,

you can interpret it as a certain *transformation*
of space.

### Matrix multiplication

Inorder to perform matrix multiplication we need to two essential things. They are

* unit vectors after transformation.

unit vectors -> i^ and j^ ( normally i^ is (1,0) and j^ is (0,1) )

matrix multiplication can be represented as 

[ trans\_i^ trans\_j^ ] 

1. For 2-Dimension

eg:

  i^ j^
[ 1  0 ]  
[ 1  1 ]   

above example can be represented generally as

  i^ j^
[ a  b ]  
[ c  d ]

if we want to find the value (x,y) after any operations such as rotation or scaling.

[ x ] * [ a b ] => x * [ a ] + y * [ b ] => [ ax ] + [ by ] => [ ax + by ]  
[ y ]   [ c d ]        [ c ]       [ d ]    [ cx ]   [ dy ]    [ cx + dy ]  

2. 3-Dimension

In 3-D we have basis vector as i^ , j^ and k^ location then we can do the same as above

### Determinant

how much it stretchs or squish things

the factor by which a linear transformation changes any area we call that as **determinant of the transformation**

important thing to notice in the determinant which is it can have negative value.

negative value represents transformation which fliped i^ and j^ ( literally sheet of paper instead using front page we use back page )

normally the j^ present in left side of i^ if the J^ present in right side of i^ then we get negative determinant.

### composition

composition is the combination of two or more tranformation 

eg: rotation and sheering

### Linear system of equation

in progress

### What is the linear algebra? 

* Systems of linear equations form a fundamental part of linear algebra

first systematic method to solving linear equation is using determinants

Linear equation can be represented as Matrix


### References

* 3 blue 1 brown youtube channel playlist => https://www.youtube.com/watch?v=fNk_zzaMoSs&index=1&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab

* khan Academy => https://www.khanacademy.org/math/linear-algebra

* For coordinate system reference => https://en.wikipedia.org/wiki/Coordinate_system
