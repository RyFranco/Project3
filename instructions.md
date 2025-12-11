
## Objective

In this assignment, you will apply your knowledge of the **Document Object Model (DOM)** and **Browser Object Model (BOM)**. You are provided with starter HTML and CSS files. Your goal is to write the JavaScript necessary to make the page interactive, manipulating DOM elements, handling user events, and implementing timing functions.

---

## Instructions

Complete the following 10 mini-tasks. Each task builds upon the previous one.






### Part 4: Advanced DOM and Timing (30 Points)




**Task 10: The Flashing Timer**

- **Goal:** Implement asynchronous timing functions.
- **Action:**
  1.  Create a function `startFlashing()` that uses **`setInterval`** to toggle the `.hidden` class on the `control-panel` every **500ms**. Store the ID returned by `setInterval` in a global variable.
  2.  Create a function `stopFlashing()` that uses **`clearInterval()`** to stop the animation.
  3.  Bind `startFlashing` to the `timer-button` **click** event.
  4.  Bind `stopFlashing` to the `timer-button` **dblclick** (double click) event.
- _Reference:_ `setInterval` returns an "interval ID" [12]; `clearInterval` stops the execution [13].

---

## Grading Rubric

| Task      | Requirement                                                        | Points  |
| :-------- | :----------------------------------------------------------------- | :------ |
| **1-2**   | Console log appears; `.hidden` class exists in CSS.                | 20      |
| **3**     | Title text changes to "DOM Project: Ready!" on load.               | 10      |
| **4**     | Toggle button has `data-action="status-toggle"` attribute.         | 10      |
| **5**     | Clicking button toggles visibility of the status div.              | 10      |
| **6**     | Page does not jump/reload on click (`preventDefault`).             | 10      |
| **7**     | Title background turns yellow when status is visible.              | 10      |
| **8**     | A new timestamp is appended to the status div on every show event. | 10      |
| **9**     | All list items are blue on page load.                              | 10      |
| **10**    | "Start Timer" flashes the panel; Double-click stops it.            | 10      |
| **Total** |                                                                    | **100** |
