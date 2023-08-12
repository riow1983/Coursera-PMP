# 1 Narrative Charter Statement
https://www.coursera.org/learn/project-management-capstone/supplement/7vheD/1-narrative-charter-statement

## Project: Development of an App for Automatic Sorting of Nursery Schools by Preference
| Project Owner | Effective Date | Version | Date |
| ---- | ---- | ---- | ---- |
| Ryosuke Horiuchi | August 19, 2023 | First issue | August 11, 2023 |

## a. Project purpose or justification
The purpose of this project is to develop an app that sorts nursery schools by user's preference. In Japan, when parents want their child to go to a nursery school, they have to report their own prefered nursery schools ranking within the region. Nursery schools on this report must be sorted by parents' preference. A municipal office accepts their submit and decide which nursey school can actually acept their child. One of the main factors for this decision is based on the degree of preference, which means more prefered nursery school is more likely to be adopted as their nursey school. This ranking system annoys parents a lot.
<br><br>
Actually, parents sort nursery schools by their preference mannually. There are a lot of factors to be considered: nursery school reputation/popularity, nursery school capacity, geographical conditions, parents' commuting direction, etc. They have to tweek their own weights and biases and culculate a score for every nursery school in their heads. It is really a time-consuming and labor intensive task.
<br><br>
Upon completion of this project, parents will be freed from manual sorting getting a recommended sort result which is customized for them by reflecting their weights and biases from the app.



## b. Measurable project objectives and related success criteria

| Objective | Success Criteria |
| ---- | ---- |
| Eliminattion of manual sorting process for parents. | Over 90% of manual process of each parent must be eliminated by app.|
| Reduce time consumed for manual research on nursery schools. | Over 90% of information gathered by manual research on the internet must be obtained from app. |
| Syncronization of updates on nursery school information | Syncronization between app and a nursery school information website that a municipality runs must be guaranteed. Longer than 15 minutes delay from the last update of municipality website is not accepted. |

## c. High-level requirements
- Completion of the work within the budget approved.
- Completion of the work according to the planning detailed in next sections of this document.
- App must be available in iOS.
- App must be designed to be used in every municipality in Japan. However, in this project the usage of app is limited in a specific area.
- Must comply with personal information protection regulations in Japan
## d. Assumptions and constraints
[Assumptions]
- App to be developed for iOS version 17.
- App to be developed by Swift version 5.8.1 and Xcode version 14.3.1.
- All app data will be stored in Azure cloud server located in Japan east.

[Constrains]
- App just displays a recommended nursery school ranking for a user and does not have any responsibilities or guarantees for receiving approval.

## e. High-level risks
- Chage in application requirements. (Online application, sort ranking not required any more)
- Inadequate knowledge/skills to develop app.
- Running cost of app.
- Lack of added values.
- High variance between municipalities in terms of collectable information from the internet.
- Legality and/or difficulty of web scraping.

## f. Summary milestone schedule
```mermaid
graph LR
  A[Define Requirements]
  B[Define range of \nweb scraping]
  C[Completion of \napp prototype]
  D[Feedbacks from \ntest users and refurbishment]
  E[Initial deployment of app]
  F[Feedbacks from \nusers and refurbishment]
  G[User servey]
  A-->B
  B-->C
  C-->D
  D-->E
  E-->F
  F-->G
```
## g. Summary budget
[!image](spreadsheetA')

***
# 2 Work Breakdown Structure
https://www.coursera.org/learn/project-management-capstone/supplement/RGRp2/2-work-breakdown-structure

```mermaid
graph TB
  H[Completion of Nurse School Sorting App]

  AM[1.0 Define requirements]
  A1[1.1 Marcket survey]
  A2[1.2 Select region]
  A3[1.3 Interview w/ parents \nin the region]
  A4[1.4 List up factors \nparents consider]
  A5[1.5 Fix requirements]
  A6[1.6 List up technical factors]
  
  BM[2.0 Define range of \nweb scraping]
  B1[2.1 List up web pages]
  B2[2.2 Select web pages]
  B3[2.3 Confirm web API availability]
  
  CM[3.0 Completion of \napp prototype]
  C1[3.1 Hiring a frontend engineer]
  C2[3.2 Hiring a web scraping engineer]
  C3[3.3 Hiring a backend engineer]
  C4[3.4 Team building]
  C5[3.5 Frontend development and unit test]
  C6[3.6 Web scraping /\ndata retrieve via web API]
  C7[3.7 Backend development and unit test]
  C8[3.8 Join test]
  
  DM[4.0 Feedbacks from \ntest users and refurbishment]
  D1[4.1 Recruiting test users]
  D2[4.2 Test by test users \nand feedbacks gathering]
  D3[4.3 Refurbishment based on feedbacks]
  D4[4.4 Join test]

  EM[5.0 Initial deployment of app]
  E1[5.1 Submit app to App Store]
  E2[5.2 Monitoring the usage of app \nand feedbacks gathering]
  
  FM[6.0 Feedbacks from \nusers and refurbishment]
  F1[6.1 Refurbishment based on feedbacks]
  F2[6.2 Join test]
  F3[6.3 Update the version of app \non App Store]

  GM[7.0 User survey]
  G1[7.1 Hiring a digital marketer]
  G2[7.2 Develop user survey web site]
  G3[7.3 Deploy user survey campaign]
  G4[7.4 Analyze and report user survey result]

  H --> AM & BM & CM & DM & EM & FM & GM
  AM --> A1
  A1 --> A2
  A2 --> A3
  A3 --> A4
  A4 --> A5
  A5 --> A6
  BM --> B1
  B1 --> B2
  B2 --> B3
  CM --> C1
  C1 --> C2
  C2 --> C3
  C3 --> C4
  C4 --> C5
  C5 --> C6
  C6 --> C7
  C7 --> C8
  DM --> D1
  D1 --> D2
  D2 --> D3
  D3 --> D4
  EM --> E1
  E1 --> E2
  FM --> F1
  F1 --> F2
  F2 --> F3
  GM --> G1
  G1 --> G2
  G2 --> G3
  G3 --> G4
```

***
# 3 Sequence Project Activities
https://www.coursera.org/learn/project-management-capstone/supplement/SbODQ/3-sequence-project-activities

![image](https://github.com/riow1983/Coursera-PMP/blob/main/png/sequence.png)

***
# 4 Build a Project Schedule
https://www.coursera.org/learn/project-management-capstone/supplement/Dycq0/4-build-a-project-schedule

![image](https://github.com/riow1983/Coursera-PMP/blob/main/png/schedule.png)


```mermaid
gantt
  dateFormat  YYYY-MM-DD
  title       Completion of Nurse School Sorting App

  section 1.0 Define requirements
  1.1 Market survey        :2023-08-19, 3d
  1.2 Selection region :3d
  1.3 Interview w/ parents in the region  :10d
  1.4 List up factors parents consider: 1d
  1.5 Fix requirements: 1d
  1.6 List up technical factors: 0.5d
  1.0 Define requirements     :milestone, 0d

  section 2.0 Define range of web scraping
  2.1 List up web pages      :2023-09-06, 2d
  2.2 Select web pages      :1d
  2.3 Confirm web API availability     :1d
  2.0 Define range of web scraping: milestone, 0d

  section 3.0 Completion of app prototype
  3.1 Hiring a frontend engineer: 2023-09-06, 5d
  3.5 Frontend development and unit test: 20d
  3.2 Hiring a web scraping engineer: 2023-09-06, 5d
  3.6 Web scraping / data retrieve via web API: 10d
  3.3 Hiring a backend engineer: a, 2023-09-06, 5d
  3.7 Backend development and unit test: 20d
  3.8 Join test: 5d
  3.0 Completion of app prototype: milestone, 0d
  3.4 Team building: after a, 2d
  
  section 4.0 Feedbacks from test users and refurbishment
  4.1 Recruiting test users: 2023-10-06, 4d
  4.2 Test by test users and feedbacks gathering: 10d
  4.3 Refurbishment based on feedbacks: 5d
  4.4 Join test: 5d
  4.0 Feedbacks from test users and refurbishment: milestone, 0d
  
  section 5.0 Initial deployment of app
  5.1 Submit app to App Store: 2023-10-30, 0.5d
  5.2 Monitoring the usage of app and feedbacks gathering: 10d
  5.0 Initial deployment of app: milestone, 0d

  section 6.0 Feedbacks from users and refurbishment
  6.1 Refurbishment based on feedbacks: 2023-11-10, 5d
  6.2 Join test: 5d
  6.3 Update the version of app on App Store: 0.5d
  6.0 Feedbacks from users and refurbishment: milestone, 0d

  section 7.0 User survey
  7.1 Hiring a digital marketer: 2023-10-31, 5d
  7.2 Develop user survey web site: 2d
  7.3 Deploy user survey campaign: 2d
  7.4 Analyze and report user survey result: 2d
  7.0 User survey: milestone, 0d
```


***
# 5 Create a Project Budget
https://www.coursera.org/learn/project-management-capstone/supplement/xu0Pj/5-create-a-project-budget

![image](https://github.com/riow1983/Coursera-PMP/blob/main/png/budget.png)

***
# 6 Create a RAM
https://www.coursera.org/learn/project-management-capstone/supplement/IO2AX/6-create-a-ram

![image](https://github.com/riow1983/Coursera-PMP/blob/main/png/ram.png)

**R** (Responsible): Person who is completing the task<br>
**A** (Accountable): Person who is making decisions and taking actions on the task(s)<br>
**C** (Consulted): Person who will be communicated with regarding the decision-making process and specific tasks<br>
**I** (Informed): Person who will be updated on decisions and actions during the project

***
# 7 Identify Project Risks
https://www.coursera.org/learn/project-management-capstone/supplement/rKo79/7-identify-project-risks

![image](https://github.com/riow1983/Coursera-PMP/blob/main/png/risks.png)



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



## Example
https://www.coursera.org/learn/project-management-capstone/peer/8TpaT/feedback-peer-review/review/bJ86fHZIEeyglw7n74i5Tw



## FAQ
### What type of files does the Peer Review submission and evaluation take?
During the peer review submission and evaluation phases, learners  will be able to upload (in the submission phase) and download  (in the evaluation phase)  .txt, .csv, .html, .htm, .css, .pdf, .jpeg,  .jpg, .png, and .gif files.

https://www.coursera.org/learn/project-management-capstone/supplement/DTE3c/faqs


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