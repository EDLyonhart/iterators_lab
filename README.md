# Iterators Lab

### Description

In the iterators lab we will be continuing our exploration of
iterators. We have a series of challenges that require you to use the
iterators we discussed in class. We will try to use various testing
methods to verify that your code is working.

### Phase-1

Research the following term and summarize your findings on it two to
three sentences:

* `higher-order function`


Update this README with a description of each of the following and an
example you've created:

* `forEach`: closest iterator to a traditional ‘for loop’. applies the condition to each part of an array.

* `map`: takes an array and transforms it in some way (.downcase, .toUpperCase, .sort, etc…)

* `filter`: creates subsets of an array based on certain parameters. (strings beginning with the letter ‘a’, or with an even/odd length string, etc. . .). it ‘filters’ the array. Creates a new array.

* `reduce`: combines an entire array into a single value.

* `some`: is like the ‘||’ of the array world. returns true if any of the elements return true.

* `every`: is like the ‘&&’ of the array world. returns true if all of the elements return true.

Use the notes provided to help guide you explanation.

### Phase-2

* Run `npm install` from the `iterators_lab` directory.
* Looks at the tests we've written in the `test` folder. Run the tests
  with `npm test` (also from the `iterators_lab` directory). They
  should all fail.
* Get all of the tests to pass by writing the necessary code in
  `src/iterators.js`.

### Phase-3

Refactor the following code using `map` to make only one call to the `map` function versus the two below.


```
var myNumbers = [ -1, 2, -3, 4, -5, 6];

var square = function(num) {
	return num * num;
};

var sqrRoot = function(num) {
	return Math.sqrt(num);
};


var sqrNumbers = map(myNumbers, square);
var absNumbers = map(sqrNumbers, sqrRoot);
```




