# CSS Specificity and !important Unexpected Behavior

This repository demonstrates a subtle but important issue related to CSS specificity and the `!important` declaration.  The example showcases how `!important` doesn't always override styles when specificity comes into play. Even with `!important`, a more specific selector takes precedence.  The solution demonstrates a more appropriate way to handle style conflicts by using more specific selectors or adjusting the CSS order to achieve the desired outcome.

## Setup

1. Clone the repository
2. Open `bug.html` in your browser

## Usage

Observe the color of the paragraph within the `container` div in `bug.html`.  The unexpected behavior is demonstrated in `bug.css`.  The `bugSolution.css` file shows a way to resolve the issue.
