# Unexpected Element Wrapping with CSS Floats

This repository demonstrates an uncommon rendering issue related to the use of `float: left` in CSS.  The problem occurs when floated elements do not completely fill a line, leading to unexpected wrapping and overlapping of subsequent elements.

## Bug Description

The `bug.css` file contains a simple CSS rule that sets `width: 50%` and `float: left` on a `div` element.  When multiple `div` elements are used without a clearing mechanism, they will not always wrap correctly in all browsers.  This can lead to layout inconsistencies and unpredictable rendering.

## Solution

The `solution.css` file demonstrates how to fix this issue by using a clearing method.  This will ensure that subsequent elements render correctly after a row of floated elements.