---
title: MD007 - Unordered list indentation
tags:  [bullet, ul, indentation]
alias: ul-indent
---

Parameters: indent (number; default 2)

This rule is triggered when list items are not indented by the configured
number of spaces (default: 2).

Example:

    * List item
       * Nested list item indented by 3 spaces

Corrected Example:

    * List item
      * Nested list item indented by 2 spaces

Rationale (2 space indent): indenting by 2 spaces allows the content of a
nested list to be in line with the start of the content of the parent list
when a single space is used after the list marker.

Rationale (4 space indent): Same indent as code blocks, simpler for editors to
implement. See
<http://www.cirosantilli.com/markdown-styleguide/#indented-lists> for more
information.

In addition, this is a compatibility issue with multi-markdown parsers, which
require a 4 space indents. See
<http://support.markedapp.com/discussions/problems/21-sub-lists-not-indenting>
for a description of the problem.

