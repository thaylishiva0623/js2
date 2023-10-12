# js2
const numbers = [4, 2, 9, 1, 5, 8, 3];

// Sort the array in descending order
numbers.sort(function(a, b) {
    return b - a;
});

console.log(numbers); // Output: [9, 8, 5, 4, 3, 2, 1]
