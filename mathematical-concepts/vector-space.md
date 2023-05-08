# Summary of Vector Spaces
A vector space is a set of vectors that satisfies eight axioms, which define how the vectors can be added and scaled by scalars. The axioms are as follows:

- Closure under addition: If u and v are vectors in the set, then u + v is also in the set.
- Associativity of addition: For all vectors u, v, and w in the set, (u + v) + w = u + (v + w).
- Commutativity of addition: For all vectors u and v in the set, u + v = v + u.
- Existence of additive identity: There exists a vector 0 in the set such that for any vector u, u + 0 = u.
- Existence of additive inverse: For any vector u in the set, there exists a vector -u in the set such that u + (-u) = 0.
- Closure under scalar multiplication: If u is a vector in the set and c is a scalar in the field, then cu is also in the set.
- Distributivity of scalar multiplication over vector addition: For any vector u and scalars c and d, c(u + v) = cu + cv and (c + d)u = cu + du.
- Distributivity of scalar multiplication over field addition: For any vectors u and v and scalar c, (c + d)u = cu + du and c(u + v) = cu + cv.
<br>
A vector space is defined over a field, which is a set of numbers with two operations, usually addition and multiplication. The field determines the scalars that can be used to scale the vectors in the vector space. For example, the field of real numbers is often used in Euclidean spaces, but other fields can be used as well.

A basis of a vector space is a set of linearly independent vectors that can span the entire vector space. A basis is important because any vector in the space can be written as a linear combination of the basis vectors. The number of vectors in a basis is called the dimension of the vector space.

The canonical basis is a specific basis in which the vectors have a standard form. For example, in R^2, the canonical basis consists of the standard basis vectors <1,0> and <0,1>.

Changing the field can change the properties of the vector space, but it would still be a vector space as long as the eight axioms are satisfied.

In summary, a vector space is a mathematical structure that allows us to study the properties of vectors and their operations. It is defined over a field and has a basis that can span the entire space.


 # Algebra in the context of fluids:

 - In fluid mechanics, we can use vector fields to represent fluid velocities at each point in space. These vector fields are functions that map a point in space to a velocity vector at that point.
- A vector space is a collection of vectors that can be added together and multiplied by scalars (numbers) to produce new vectors that also belong to the same space. In the context of fluid mechanics, the vector space is the set of all possible velocity vector fields.
- A subspace of a vector space is a subset that is closed under vector addition and scalar multiplication. In other words, if we take any two vectors in the subspace and add them together or multiply them by a scalar, the resulting vector will still belong to the subspace. In the context of fluid mechanics, a subspace could be a collection of velocity vector fields that satisfy certain conditions (such as having constant velocity or being divergence-free).
- We can use linear algebra to study the properties of vector spaces and subspaces. For example, we can determine whether a set of vectors spans a subspace by checking whether any vector in the subspace can be written as a linear combination of the given vectors. We can also check whether a set of vectors is linearly independent (meaning that none of the vectors can be written as a linear combination of the others) by solving a system of linear equations.
- The span of a set of vectors is the set of all possible linear combinations of those vectors. In the context of fluid mechanics, we could take the span of a set of velocity vector fields to get a larger subspace that contains all the possible fluid velocities that can be obtained by combining the given fields.
- The zero vector in a vector space is the vector that when added to any other vector, leaves it unchanged. In the context of fluid mechanics, the zero vector would be the velocity field that corresponds to a stationary fluid. However, since the fluid can be moving in different directions at different points in space, we can define the zero vector differently depending on our reference frame.
- Finally, we discussed how thinking about fluids can provide an intuitive way to understand vector spaces and subspaces, since we can visualize the behavior of fluids and relate it to mathematical concepts.