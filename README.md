# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity. A more specific selector unintentionally overrides a more general selector, leading to unexpected styling results.

## Bug Description

The issue arises due to the specificity of CSS selectors. More specific selectors take precedence over less specific ones, sometimes leading to undesired outcomes. The bug showcases this conflict, where a specific selector overrides the styles defined by a more general selector.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to observe the conflicting styles.
3. Open `index.html` (or equivalent file containing the HTML structure) in a browser.
4. Note the unexpected styling applied to the elements due to the specificity issue.

## Solution

The `bugSolution.css` file demonstrates several ways to resolve this specificity issue:

* **Increasing the Specificity of the Overridden Selector:** By increasing the specificity of the more general selector.
* **Using the !important Flag (Use with caution):** This is a last resort to override specific styles.
* **Re-structuring the CSS:**  Reorganizing the CSS rules to improve order of precedence and fix specificity issues.

Choose the appropriate solution based on the overall CSS structure and best practices.