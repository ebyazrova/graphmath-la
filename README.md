# GraphMath — Linear Algebra

This repository contains visual and geometric interpretations of key concepts in linear algebra, including projections, subspaces, pseudoinverse and least squares.

Some of these diagrams and ideas are also linked from public educational platforms including Wikipedia, Wikimedia Commons and Zenodo.

---

## Concepts

- **Least Squares as Projection in R³ (3 Observations, 2 Parameters)**  
  https://www.graphmath.com/la/concepts/least-squares-projection-r3.html

- **Change of Basis — Coordinate Mapping View**  
  https://www.graphmath.com/la/concepts/change-of-basis-coordinate-mapping.html

---

## Least Squares (OLS)

- Geometric interpretation as projection onto the column space
- Decomposition of y into y∥ in col(X) and y⊥ orthogonal to col(X)
- Representation of col(X) as a plane in R³ for three observations

📄 PDF: [best-solution-ols.pdf](ls/best-solution-ols.pdf)  
🖼 Diagram: [Least squares projection in R3.png](ls/Least%20squares%20projection%20in%20R3.png)  
🌐 Web: https://www.graphmath.com/la/ls/best-solution-ols.html

---

## Four Fundamental Subspaces

- Decomposition of domain: Rⁿ = row(A) ⊕ null(A)
- Decomposition of codomain: Rᵐ = col(A) ⊕ null(Aᵀ)
- Orthogonality of row space vs null space, and column space vs left null space

📄 PDF: [subspaces.pdf](subspaces/subspaces.pdf)  
🖼 Diagram: [Matrix four fundamental subspaces decomposition](subspaces/Matrix_four_fundamental_subspaces_decomposition.png)  
🌐 Web: https://www.graphmath.com/la/subspaces/subspaces.html

---

## Pseudoinverse

- Mapping between column space and row space  
- A⁺A acts as identity on the row space  
- AA⁺ acts as projection onto the column space  

📄 PDF: [pseudoinverse.pdf](pseudoinverse/pseudoinverse.pdf)  
🌐 Web: https://www.graphmath.com/la/pseudoinverse/pseudoinverse.html

---

## External references

- Wikipedia:
  - [Projection (linear algebra) — Orthogonal projections](https://en.wikipedia.org/wiki/Projection_(linear_algebra)#Orthogonal_projections)
  - [Projection (linear algebra) — Finding projection with an inner product](https://en.wikipedia.org/wiki/Projection_(linear_algebra)#Finding_projection_with_an_inner_product)
  - [Ordinary least squares — Projection](https://en.wikipedia.org/wiki/Ordinary_least_squares#Projection)
  - [Row and column spaces — Relation to the left null space](https://en.wikipedia.org/wiki/Row_and_column_spaces#Relation_to_the_left_null_space)
  - [Change of basis](https://en.wikipedia.org/wiki/Change_of_basis)
  - [QR decomposition — Square matrix](https://en.wikipedia.org/wiki/QR_decomposition#Square_matrix)
  - [QR decomposition — Example](https://en.wikipedia.org/wiki/QR_decomposition#Example)
  - [Gaussian elimination — Definitions and example of algorithm](https://en.wikipedia.org/wiki/Gaussian_elimination#Definitions_and_example_of_algorithm)

- Wikimedia Commons:
  - [Least squares projection geometry](https://commons.wikimedia.org/wiki/File:Least_squares_projection_geometry.png)
  - [Orthogonal projection using an orthonormal basis](https://commons.wikimedia.org/wiki/File:Orthogonal_projection_using_an_orthonormal_basis.png)
  - [Geometric interpretation of least squares (three observations)](https://commons.wikimedia.org/wiki/File:Geometric_interpretation_of_least_squares_(three_observations).png)
  - [Four fundamental subspaces of a matrix (diagram)](https://commons.wikimedia.org/wiki/File:Four_fundamental_subspaces_of_a_matrix_(diagram).png)
  - [Change-of-basis coordinate mapping (matrix representation)](https://commons.wikimedia.org/wiki/File:Change-of-basis_coordinate_mapping_(matrix_representation).png)
  - [Change-of-basis coordinate transformation between bases](https://commons.wikimedia.org/wiki/File:Change-of-basis_coordinate_transformation_between_bases.png)
  - [QR decomposition geometric interpretation (2D)](https://commons.wikimedia.org/wiki/File:QR_decomposition_geometric_interpretation_(2D).png)
  - [QR decomposition geometric interpretation (3D)](https://commons.wikimedia.org/wiki/File:QR_decomposition_geometric_interpretation_(3D).png)
  - [Gaussian elimination as multiplication by elementary matrices](https://commons.wikimedia.org/wiki/File:Gaussian_elimination_as_multiplication_by_elementary_matrices.png)

- Open educational repositories:
  - [OER Commons — Geometric Interpretation of Least Squares (OLS)](https://oercommons.org/courses/geometric-interpretation-of-least-squares-ols)
  - [MERLOT — GraphMath materials](https://www.merlot.org/merlot/materials.htm?contributorUserId=1497058&fromAdvancedSearch=true&sort.property=dateCreated)

- Zenodo:
  - [GraphMath record](https://zenodo.org/records/19272886)

---

## Authors

- Eteri Byazrova
- Yuri Morozov

---

## Project

GraphMath — https://www.graphmath.com

---

## Related external project

- [Learn Linear Algebra](https://github.com/prashantkul/learn-linear-algebra) — free project by Prashant Kulkarni using GitHub notes, NotebookLM, SageMath/Python, examples and exercises
