# 1 Narrative Charter Statement
https://www.coursera.org/learn/project-management-capstone/supplement/7vheD/1-narrative-charter-statement
## a. Project purpose or justification
## b. Measurable project objectives and related success criteria
## c. High-level requirements
## d. Assumptions and constraints
## e. High-level risks
## f. Summary milestone schedule
```mermaid
```
## g. Summary budget
[!image](spreadsheetA')

# 2 Work Breakdown Structure
https://www.coursera.org/learn/project-management-capstone/supplement/RGRp2/2-work-breakdown-structure

```mermaid
```

# 3 Sequence Project Activities
https://www.coursera.org/learn/project-management-capstone/supplement/SbODQ/3-sequence-project-activities

[!image](spreadsheetA-1)

# 4 Build a Project Schedule
https://www.coursera.org/learn/project-management-capstone/supplement/Dycq0/4-build-a-project-schedule

[!image](spreadsheetA-2)

# 5 Create a Project Budget
https://www.coursera.org/learn/project-management-capstone/supplement/xu0Pj/5-create-a-project-budget

[!image](spreadsheetA-3)

# 6 Create a RAM
https://www.coursera.org/learn/project-management-capstone/supplement/IO2AX/6-create-a-ram

[!image](spreadsheetA-4)

Responsible: Person who is completing the task
Accountable: Person who is making decisions and taking actions on the task(s)
Consulted: Person who will be communicated with regarding the decision-making process and specific tasks
Informed: Person who will be updated on decisions and actions during the project

# 7 Identify Project Risks
https://www.coursera.org/learn/project-management-capstone/supplement/rKo79/7-identify-project-risks

[!image](spreadsheetB)



***
# Appendix
## Tools
- README.md:
    - 1 Narrative Charter Statement
- Mermaid: 
    - 1 > f. Summary milestone schedule
    - 2 Work Breakdown Structure
- Spreadsheet
    - A: 3 - 6
    - A': 1 > g. Summary budget
    - B: 7



## Minimum requirements
```python
minscores1 = {"a":1,"b":1,"c":1,"d":1,"e":1,"f":1,"g":1}
minscores2 = {2:4, 3:3, 4:3, 5:3, 6:1, 7:3}
total = sum(minscores1.values()) + sum(minscores2.values())
print(total)
# 24
```
> The entire project is worth 48 points. A passing score is 34 points and above.

https://www.coursera.org/learn/project-management-capstone/supplement/RtyTu/grading-logistics



## Links to Relevant Course Content
https://www.coursera.org/learn/project-management-capstone/supplement/epvxT/links-to-relevant-course-content



## Mermaid example
[e3nn](https://www.connectedpapers.com/main/c7215ab4589ce3590910c597e86b1aba8e460d49/e3nn%3A-Euclidean-Neural-Networks/graph)
```mermaid
flowchart TD;
    A[Freeman,1991\nThe design and use of steerabe filters]-- steerable filters -->B[Worrall,2017\nHarmonic networks: deep translation and rotation equivariance]
    A-- steerable filters -->C[Cohen,2016\nSteerable cnns]
    subgraph ide0[Equivariant NN]
    subgraph ide1[Equivariant 3D CNN]
        subgraph ide2[Equivariant 2D CNN]
        C-- steerable cnns -->B
        end
        B-- harmonic networks -->D[Thomas,2018\nTensor field networks:\nrotation- and translation- equivariant neural networks for 3d point clouds]
        B-- harmonic networks -->G[Weiler,2018\n3d steerable cnns:\nlearning rotationally equivariant features in volumetric data]
        C -. block structure for the equivariant filter bank .-> G
    end
        D-- TFN / Clebsch-Gordan coefficients -->F[Geiger,2021\ne3nn: euclidean neural networks]
        G-..->F
        K[Finzi,2021\nA practical method for constructing equivariant multilayer perceptrons\nfor arbitrary matrix groups]-. equivariant MLP .-> F
    end
    E[Schutt,2017\nQuantum-chemical insights from deep tensor neural networks]-. continuous-filter convolution .->D
    H[Li,2020\nPredicting charges in protein thermodynamic stability\nupon point mutation with deep 3d convolutional neural networks]-- ThermoNet library -->I>6th solution, Novozymes, Kaggle competition, 2023]:::kagglecolor
    classDef kagglecolor fill:#33FFFF
    F-- e3nn library -->I
    J[Cohen,2014\nLearning the irreducible representations of commutative lie groups]-- irreps of rotation group --> C
```