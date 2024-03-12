# Google Query Project 
---

## **Project Outline**
- [Project Overview](#Project-Overview)
- [Dataset](#Dataset)
- [Query 1](#Query-1)
- [Query 2](#Query-2)
- [Query 3](#Query-3)
- [Query 4](#Query-4)
- [Query 5](#Query-5)
- [Query 6](#Query-6)
- [Tools used](#Tools-Used)

---

## Project Overview

---
## Dataset
The dataset used can be downloaded 
[here](https://drive.google.com/file/d/1sBnniRB8LApHtMCEED0_rf3mLA0Abrtf/view?usp=drivesdk)

---

## Query 1
This section query the sales rep whose items are pen set and binder

```
=QUERY(A1:H44,"SELECT B,C WHERE C='Pen Set', OR C='Binder'", 1)
```

## Result
![](Table1.JPG)

---

## Query 2
This section query the sales of binder items and pencil in 2015

```
=QUERY(A1:H44,"SELECT C,F,H WHERE (C='Pencil', OR C='Binder') AND F=2015", 1)

```

## Result
![](Table2.JPG)

---

## Query 3
This section query the sales in Central and East region in 2014

```
=QUERY(A1:H44,"SELECT A,F,H WHERE (C='Central', OR C='East') AND F=2014", 1)
```
## Result
![](Table3.JPG)

---

## Query 4
This section query the sales in August and September 2014

```
=QUERY(A1:H44,"SELECT E,F,H WHERE (C='Aug', OR C='Sep') AND F=2014", 1)
```
## Result
![](Table4.JPG)

---

## Query 5
This section query the sales of items that start with Pen, include their region, sales rep and year

```
=QUERY(A1:H44,"SELECT A,B,C,F,H WHERE C LIKE 'Pen%'", 1)
```
## Result
![](Table5.JPG)

---

## Query 6
This section query the sales of items that end with ‘sk’, include their region, sales rep and year

```
=QUERY(A1:H44,"SELECT A,B,C,F,H WHERE C LIKE '%sk'", 1)
```
## Result
![](Table6.JPG)

---

## Tools Used

This project was done using Google Sheet

---
