---
title: MD041 - First line in file should be a top level header
tags:  [headers]
alias: first-line-h1
---

This rule is triggered when the first line in the file isn't a top level (h1)
header:

    ```
    This is a file without a header
    ```

To fix this, add a header to the top of your file:

    ```
    # File with header

    This is a file with a top level header
    ```
