# CSS `calc()` with Percentages Unexpected Results

This repository demonstrates an uncommon issue with the CSS `calc()` function when used with percentages.  The expected calculation does not produce the correct result, leading to unexpected layout issues.

## Bug Description

The `calc()` function, when used with percentages in certain scenarios, doesn't perform the calculation as anticipated. This often occurs when combining percentages with other units like pixels or `em`s.

## Reproduction Steps

1. Open `bug.css`
2. Observe the behavior of the element with the incorrectly calculated width.
3. Compare with the corrected `bugSolution.css` file.

## Solution

The solution may involve adjusting the calculation to ensure the percentages are handled correctly in relation to the other units used within the `calc()` function. This often necessitates careful consideration of the context and parent element dimensions.