# Chapter 8 Team Project
Jacob Losey, alex D. goat

## Chapter 8 Team Project Description


### Chapter 8 Team Project Flowchart
```mermaid
graph LR
  main --> displayMenu
  main --> inputGrades
  main --> viewGrades
  main --> saveGradesToFile
  main --> loadGradesFromFile
  main --> analyzeGrades
  main --> searchStudent
  main --> sortData
  main --> clearInputStream

  inputGrades --> calculateAverage

  analyzeGrades --> calculateAverages
  calculateAverages --> calculateAverage

  searchStudent --> quickSortByName
  searchStudent --> binarySearchByName
  quickSortByName --> partitionByName

  sortData --> quickSortByName
  sortData --> mergeSortByAverage
  mergeSortByAverage --> merge
```

#### Function Diagrams

| `main`    |               |  jacob    |
| ------------------ | ------------- | ------------ |
| accepts no arguements    | it runs the functions |   it outputs nothing           |
***
