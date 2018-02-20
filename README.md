## Sort Array

search a sorted array by repeatedly splitting the array in half using Binary Search

run the sort.js and binary-search.js togather

## HTML String Highlighter
string_highlighter.js
One way to make some HTML text appear highlighted is to wrap a segment of text with a styled `<span>` tag.

function that takes a string and a list of pairs of string indices representing segments of text that are to be highlighted. Returns an html string with each segment wrapped in `<span>` tag.

Assume: index pairs are in a valid order and within the string bounds

index = [[]]

## Map, Reduce, Filter
### Iterate Left to Right

array.map((element, index, original_array) => {
      // do something
});

array.filter((element, index, original_array) => {
      // do something
});

array.reduce((previous_val, element, index, original_array) => {
      // do something
});

// Get unique items in an array.

a.filter((element, idx, array) => array.indexOf(element) === idx)
