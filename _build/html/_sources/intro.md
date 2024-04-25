# Facial Recognition System

🔸️ A company wants to implement an access control system based on facial recognition.

🔸️ Every time someone tries to enter the company, the system must process his or her image and determine two questions:
   
   1. Is the person an employee of the company (does he/she belong to the staff)?

   2. If yes: Which employee is he/she?

🔸️ If the answer to 1. is affirmative and the worker (2) is coming on his/her scheduled shift --> he/she is allowed to enter. Otherwise, he/she is prevented.

This face recognition system has three versions, all of them using the KNN algorithm as classifier. 

The first version uses the data extracted from the raw image processing, the second uses its PCA transformation, and the third uses its PCA + FisherLDA transformation.


```{tableofcontents}
```
