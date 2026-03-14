# javascript-test-0001-final-14703-kaustubh
Final Project Assignment - This repository contains the complete final project code and documentation.
let n = 5;

// up part
for (let i = 1; i <= n; i++) {
    let row = "";

    // Spaces before stars
    for (let j = 1; j <= n - i; j++) {
        row += " ";
    }

    // Stars and inner spaces
    for (let j = 1; j <= (2 * i - 1); j++) {
        if (j === 1 || j === (2 * i - 1)) {
            row += "*";
        } else {
            row += " ";
        }
    }

    console.log(row);
}

// down start
for (let i = n - 1; i >= 1; i--) {
    let row = "";

    // Spaces before stars
    for (let j = 1; j <= n - i; j++) {
        row += " ";
    }

    // Stars and inner spaces
    for (let j = 1; j <= (2 * i - 1); j++) {
        if (j === 1 || j === (2 * i - 1)) {
            row += "*";
        } else {
            row += " ";
        }
    }

    console.log(row);
}
