## Vectors and Graphics
- Linear Algebra lets us turn geometric ideas about dimension into things we can compute concretely.
- The most basic concept in linear algebra is that of a `vector`, which you can think of as a data point in some multi-dimensional space.
- Even though our everyday experience takes plance in three dimensions, it's useful to think of some data as higher dimensional.
- In physics, it's common to consider time as the fourth dimension. 
- While an object exists at a location in 3D space, an event occurs at a 3D location and at a specified moment.
- In data science problems, it's common for data sets to have far more dimensions.
- For instance, a user tracked on a website can have hundreds of measurable attributes, which describe usage patterns.
- Grappling with these problems in graphics, physics and data analysis requires a framework for dealing with data in higher dimensions. This framework is `vector mathematics`
- A two-dimensional vector is `a point in the plane relative to the origin`. Equivalently, you can think of a vector as a straight arrow in the plane; any arrow can be placed to start at the origin, and it indicates a particular point.
- We can describe vector in three ways
1. An ordered pair of numbers (x- and y-coordinates)
2. A point in the plane relative to the origin
3. An arrow of a specific length in a specific direction

- Rule for vector addition of arrows is sometimes called `tip-to-tail` addition. 
- Adding a vector has the effect of moving or `translating` an existing point or collection of points.
- The `length` of a vector is the length of the arrow that represents it, or equivalently, the distance from the origin to the point that represents it.
- Breaking a vector into components is handy because it always gives us a right triangle.
- If we know the lengths of the components, we can compute the length of the hypotenuse, which is the length of the vector.
- The operation of multiplying a vector by a number is called `scalar multiplication.` When working with vectors, ordinary numbers are often called `scalars`.
- It's also an appropriate term because the effect of this operation is `scaling` the target vector by the given factor.
- It doesn't matter if the scalar is a whole number; we can easily draw a vector that is 2.5 times the length of another.
- The difference for the vectors v-w = (-3,1) tells us that if we start at point w, we need to go three units left and one unit up to get to point v. This vector is sometimes called the `displacement` from w to v.
- While the displacement is vector, the distance is a scalar (a singular number). The distance on its own is not enough to specify how to get from w to v; there are plenty of points that have the same distance from w.
