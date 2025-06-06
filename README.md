````markdown
# 🧮 Bubble Sort Visualizer

A simple web-based visualization tool that demonstrates each step of the **Bubble Sort** algorithm. Built using HTML, CSS, and JavaScript.

---

## 🚀 Features

- Visualizes the sorting process for an array of **5 random integers**
- Step-by-step bubble sort comparisons and swaps
- Highlights compared elements during sorting
- Fully dynamic array generation
- Clean and responsive UI

---

## 📂 Project Structure

```text
├── index.html        # Markup for UI structure
├── styles.css        # Styling for layout and visualization
├── script.js         # JavaScript logic and DOM manipulation
└── README.md         # Project documentation
```

---

## 🎯 User Stories Implemented

1. `generateElement` returns a random integer between **1 and 100**.
2. `generateArray` returns an array of **five random integers**.
3. `generateContainer` creates and returns an **empty div** element.
4. `fillArrContainer` takes a container and array, and fills the container with **5 span elements** representing the array.
5. `isOrdered` checks if two integers are in **ascending order**.
6. `swapElements` swaps two elements in the array **if not ordered**.
7. `highlightCurrentEls` visually highlights the two elements being **compared**.
8. `#generate-btn` generates and displays a **new random array** in `#starting-array`.
9. `#sort-btn` initiates the **Bubble Sort**, appending each sorting step to `#array-container`.
10. Sorting steps show updated arrays and **highlight active comparisons**.

---

## 📸 Screenshots

> Not included here, but feel free to capture and add UI images after running the app locally.

---

## 🛠 How to Use

1. Open `index.html` in any modern web browser.
2. Click **"Generate Array"** to create a new unsorted array.
3. Click **"Sort Array"** to visualize the Bubble Sort steps.

---

## 🔍 Technologies Used

* **HTML5** – Structure of the visualizer
* **CSS3** – Styling and layout
* **Vanilla JavaScript** – Sorting logic and DOM manipulation

---

## 📌 Notes

* The visualizer uses a simplified version of Bubble Sort.
* Each comparison and swap creates a new visual step in the container.
* Initial and final arrays are also shown in the step-by-step output.

---

## 📈 Bubble Sort Logic Summary

```js
do {
  swapped = false;
  for (let i = 0; i < array.length - 1; i++) {
    if (array[i] > array[i + 1]) {
      swap them;
      swapped = true;
    }
  }
} while (swapped);
```

---

## 📃 License

This project is open-source and free to use. Customize or expand upon it as you see fit!

---

```
