
# goit-js-hw-04  

This repository contains three JavaScript functions solving different tasks.  

## `task-1.js` - `isEnoughCapacity(products, containerSize)`  

Checks if the total quantity of products fits within the given container size.  

**Params:**  
- `products` (object) – an object where keys are product names and values are their quantities  
- `containerSize` (number) – the maximum allowed capacity  

**Example:**  
```
isEnoughCapacity({ apples: 2, grapes: 3, carrots: 1 }, 8); // true
```
---

## `task-2.js` - `calcAverageCalories(days)`


Calculates the average daily calorie intake based on an array of daily records.

**Params:**  
- `days` (array) – an array of objects, each containing day (string) and calories (number)

**Example:**  
```
calcAverageCalories([
  { day: "monday", calories: 3010 },
  { day: "tuesday", calories: 3200 },
  { day: "wednesday", calories: 3120 }
]); // 3110
```
---

## `task-3.js` - `profile object`
An object that manages a user's profile, allowing username changes, playtime updates, and retrieving profile info.

**Properties:**
- `username` (string) – the user's name
- `playTime` (number) – the total playtime in hours

**Methods:**
- `changeUsername(newName)` – updates the username
- `updatePlayTime(hours)` – adds playtime hours
- `getInfo()` – returns a string with username and playtime

**Example:**
```
console.log(profile.getInfo()); // "Jacob has 300 active hours!"
profile.changeUsername('Marco');
console.log(profile.getInfo()); // "Marco has 300 active hours!"
profile.updatePlayTime(20);
console.log(profile.getInfo()); // "Marco has 320 active hours!"
```