# Uncommon HTML Bug: Disappearing Div

This repository demonstrates a common yet subtle bug in HTML where a div element disappears after a button click and does not reappear.

## Bug Description

The `bug.html` file contains a div element and a button. Clicking the button hides the div using `style.display = "none";`.  The problem is there's no mechanism to show the div again, resulting in the content becoming permanently hidden.

## Solution

The `solution.html` file provides a corrected version.  It adds a second button or an alternative method to toggle the visibility of the div, making the content accessible to the user again.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Click the button. The div will disappear.
4. Open `solution.html`. The div will be visible and can be hidden and shown.