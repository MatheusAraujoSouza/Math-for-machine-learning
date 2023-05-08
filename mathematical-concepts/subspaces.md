# Vector Spaces
A vector space is a set of vectors that can be added together and multiplied ("scaled") by numbers, called scalars. The scalars are usually taken to be real numbers or complex numbers. Some common examples of vector spaces include R^2 (the set of all 2-dimensional vectors with real components), R^3 (the set of all 3-dimensional vectors with real components), and the set of all polynomials with real coefficients.

# Subspaces
A subspace of a vector space is a subset of that vector space that is itself a vector space. In order to be a subspace, a set must satisfy three conditions: it must contain the zero vector, it must be closed under vector addition, and it must be closed under scalar multiplication. For example, in R^2, any line that passes through the origin is a subspace, and in R^3, any plane that passes through the origin is a subspace.

# Span
The span of a set of vectors is the set of all possible linear combinations of those vectors. For example, if v1 = (1, 0) and v2 = (0, 1), then the span of {v1, v2} is all possible linear combinations of v1 and v2, which is the entire xy-plane in R^2.

# Image and Kernel
Given a linear transformation T from one vector space V to another vector space W, the image of T (also called the range of T) is the set of all possible outputs of T. In other words, the image of T is the set of all vectors w in W that can be expressed as T(v) for some v in V. The kernel of T (also called the null space of T) is the set of all vectors v in V that map to the zero vector in W. In other words, the kernel of T is the set of all solutions to the equation T(v) = 0.

# Applications to Fluid Mechanics
In the context of fluid mechanics, vector spaces can be used to describe the velocity field of a fluid. The velocity at any point in the fluid can be represented as a vector, and the set of all such vectors forms a vector space. The subspace of constant velocity vectors is an example of a subspace in this context, and the span of a set of velocity vectors can be used to describe the flow of the fluid in a certain region. The image and kernel of a linear transformation can also be used to describe the flow of a fluid in terms of its sources and sinks.