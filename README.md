# Apache Spark Exercise with Python

This repository includes 2 exercises, that I did in my Fundamentals of Big 
Data Class in my post-graduate program at the university, to perform 
real-world analysis on two data sets.

The data sets:

- WhiteHouse Visitor Logs
- Wikipedia Links

# Contents

```bash
.
├── 100000 Data.tar.xz
├── Q1
│   ├── A2_Q1.ipynb
│   ├── Q1A-answer.txt
│   ├── Q1B-answer.txt
│   ├── Q1C-answer.txt
│   ├── Q1D-answer.txt
│   └── Q1E-answer.txt
├── Q2
│   ├── A2_Q2.ipynb
│   ├── Q2A-answer.txt
│   ├── Q2B-answer.txt
│   └── Q2C-answer.txt
└── README.md
```

# Exercices

## Question 1

This part involves some fun Spark processing using the White House Visitor  
Log from 2015. You are required to write efficient Spark programs to find the 
following information:

A) The 5 most frequent visitors (NAMELAST, NAMEFIRST, NAMEMID) to the 
WhiteHouse.

B) Of the top-5 most frequent visitors (above), who did they each most 
frequently visit?

C) The 5 most frequently visited people (visitee_namelast, visitee_namefirst) 
in the White House.

D) Of the top-5 most frequently visited people (above), who were they most 
frequently visited by?

E) The 10 most frequent visitor-visitee combinations.

## Question 2

In this part, you will write Spark programs to process wikipedia datasets 
titles-sorted and links-simple-sorted. Please see the included Using the 
Haselgrove Wikipedia Dataset document for details on how to use these 
datasets. Also be aware that you may use the first 100000 rows from the 
links-simple-sorted dataset but must use the entire titles-sorted file.

A) Write a Spark program that will output all pages with no outlinks.

B) Write a Spark program that will output all pages with no inlinks.

C) Write a Spark program that sorts the pages by popularity. In addition to 
the Spark program, you will also need to provide a justification for your 
algorithm.

# How to run the scripts

```
Question 1 Instruction

- Extract the "100000_White_House_Visitor_Records_Requests.csv.gz" file the from "100000 Data.tar.xz" file and copy it in the main folder.
- Run the jupyter notebook.
```

```
Question 2 Instruction

- Extract the "1titles-sorted.txt" file and the "100000_links-simple-sorted.txt.gz" the from "100000 Data.tar.xz" file and in the main folder.
- Run the jupyter notebook.
```
