# sorting-helpers

A Simple Sorting Library to help you sorting, i have 3 Sorting now, and the sorting with Array data.
* * *

## How To Install
```bash
npm install --save sorting-helpers
```
* * *

## How To Use

```Javascript
const sort = require('sorting-helpers')

let data = [10,5,2,5,70,99,88,100,40,16]
//This For Bubble Sort
console.log(sort.bubbleSort(data))
//This For Merge Sort
console.log(sort.mergeSort(data))
//This For Selection Sort
console.log(sort.selectionSort(data))
```