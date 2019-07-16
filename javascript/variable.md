---
description: var / let / const
---

# Variable

## Variable is ...

The name given to the memory space where one value can be stored or refers to the memory space itself. Simply put, a variable is a named value that is a mechanism for storing and referencing values.

```javascript
// Declaration + Definition
var a = 0;

// Declaration
var a;

// Definition
a = 0;
```

#### Purpose

Concept to effectively memorize data and manage it for reuse

## Scope

var = Function Level Scope

let, const = Block Level Scope

## Variable Declaration \(Statement\)

A statement that registers the variable name \(identifier\) ​​and notifies the JavaScript engine of the existence of the variable. When declaring a variable, use the keyword var, let, const.

* Variable declaration and assignment can express by one statement

## Assignment of values.

Use the assignment operator \(=\) when assigning variables. The assignment operator assigns the value on the right side to the variable on the left side.

## Variable Hoisting

It is a feature that acts like a declaration is pulled to the head of the code. \(Applies to Var, let, const, function, class, variable, function, class\)

## Variable Name

Declare a variable name and free memory space to store the value. undefined is implicitly initialized by assigning a value rather than an empty space.

Initialization Phase: Get memory space to store values ​​and implicitly assign undefined.

## Memories

변수에 값을 할당할 때는 이전 값 undefined가 저장되어 있던 메모리 공간을 지우고 그 메모리 공간에 할당 값 80을 새롭게 저장하는 것이 아니라 새로운 메모리 공간을 확보하고 그 메모리 공간에 할당 값 80을 저장하는 것에 주의하자.

만약 초기에 지정한 값을 새로운 값으로 변경하고, 변경 값이 저장 후 이전 값을 undefined로 교체한다. 이전 값이 더 이상 필요하지 않은 값이 된다면 가비지 컬렉터 \(Garbage Collator\)에 의해 자동으로 메모리에서 해제된다.

## **Reserved word**

await / break / case / catch / class / const / continue / debugger / default / delete / do / else / enum / export / extends / false / finally / for / function / if / implements\* / import / in / Instanceof / interface\* / let\* / new / null / package\* / private\* / protected\* / public\* / return / super / static\* / Switch / this / throw / true / try / typeof / var / void / while / with / yield\*

