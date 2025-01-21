# Tailwind CSS Nested Flexbox Issue

This repository demonstrates a common issue encountered when working with nested flexbox elements in Tailwind CSS. The problem involves unexpected vertical rendering of flex items, where they appear stacked vertically rather than horizontally as intended.

## Problem Description

The primary issue lies in the misunderstanding of how Tailwind's `flex` utility interacts with nested elements.  When using `flex` within nested divs, proper parent and child configurations are needed to achieve the desired horizontal layout. The provided `bug.html` showcases this issue.

## Solution

The solution, outlined in `solution.html`, involves correctly setting the `flex` direction for both the parent and, in certain scenarios, the child divs.  This ensures that flex items are arranged correctly along the specified axis.