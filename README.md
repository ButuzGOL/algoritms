# Algoritms

## New year tree
[Source](https://github.com/ButuzGOL/algoritms/blob/master/new-year-tree.js)

**Output**
```
t(4)

//    *
//   ***
//  *****
// *******
```

## Bucket fill tool
[Source](https://github.com/ButuzGOL/algoritms/blob/master/bucket-fill-tool.js)
[Source recursion](https://github.com/ButuzGOL/algoritms/blob/master/bucket-fill-tool-recursion.js)

**Input**
```
// [ [ 'O', 'X', 'X', 'X', 'X' ],
//   [ 'X', 'O', 'O', 'O', 'X' ],
//   [ 'X', 'O', '#', 'O', 'X' ],
//   [ 'X', '*', '*', '*', 'X' ],
//   [ 'X', 'X', 'O', 'X', 'X' ],
//   [ 'X', 'X', 'X', '#', '#' ],
//   [ 'X', 'O', 'X', 'X', 'X' ] ]
```

**Output**
```
fill(field, 0, 0, '*');

// [ [ '*', 'X', 'X', 'X', 'X' ],
//   [ 'X', '*', '*', '*', 'X' ],
//   [ 'X', '*', '#', '*', 'X' ],
//   [ 'X', '*', '*', '*', 'X' ],
//   [ 'X', 'X', '*', 'X', 'X' ],
//   [ 'X', '*', 'X', '#', '#' ],
//   [ 'X', '*', 'X', 'X', 'X' ] ]

```

## Facebook events calendar
[Source](https://github.com/ButuzGOL/algoritms/blob/master/fb-calendar.js)

**Input**
```
//  { start: 0, end: 30 },
//  { start: 30, end: 100 },
//  { start: 80, end: 160 },
//  { start: 110, end: 240 },
//  { start: 110, end: 180 },
//  { start: 170, end: 230 },
//  { start: 170, end: 240 },
//  { start: 170, end: 220 },
//  { start: 190, end: 260 },
//  { start: 230, end: 300 },
//  { start: 240, end: 280 },
//  { start: 250, end: 290 },
//  { start: 300, end: 330 }
```

**Output**
```
draw(build(events));

// 10  ||                                                                              |
// 20  ||                                                                              |
// 30  ||______________________________________________________________________________|
// 40  ||              |
// 50  ||              |
// 60  ||              |
// 70  ||              |
// 80  ||              |
// 90  ||              ||              |
// 100 ||______________||              |
// 110 |                |              |
// 120 ||              ||              ||              |
// 130 ||              ||              ||              |
// 140 ||              ||              ||              |
// 150 ||              ||              ||              |
// 160 ||              ||______________||              |
// 170 ||              |                |              |
// 180 ||______________||              ||              ||              ||              |
// 190 |                |              ||              ||              ||              |
// 200 ||              ||              ||              ||              ||              |
// 210 ||              ||              ||              ||              ||              |
// 220 ||              ||______________||              ||              ||              |
// 230 ||              |                |              ||______________||              |
// 240 ||              |                |______________||              ||______________|
// 250 ||              |                                |              ||              |
// 260 ||______________|                |              ||              ||              |
// 270 |                                |              ||              ||              |
// 280 |                                |              ||              ||______________|
// 290 |                                |______________||              |
// 300 |                                                |______________|
// 310 ||                                                                              |
// 320 ||                                                                              |
// 330 ||______________________________________________________________________________|

```

## Bubble sort
[Source](https://github.com/ButuzGOL/algoritms/blob/master/bubble-sort.js)

**Input**
```
// [ 5, 4, 1, 6, 8, 10, 25 ]
```

**Output**
```
console.log(sort(array));

// [ 1, 4, 5, 6, 8, 10, 25 ]
```
