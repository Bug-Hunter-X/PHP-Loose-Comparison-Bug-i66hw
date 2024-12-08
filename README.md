# PHP Loose Comparison Bug
This repository demonstrates a common error in PHP related to loose comparison (==) of different data types.

The `bug.php` file contains code that uses loose comparison to check for equality.  This comparison can lead to unexpected behavior.  The `bugSolution.php` file shows how to correctly use strict comparison (===) to resolve the issue.

This can be especially problematic when comparing numeric and string values, as the loose comparison may cast the values to a common type for the comparison, leading to unexpected 'true' results.

## How to run

1. Clone this repository.
2. Run `bug.php` and `bugSolution.php` using a PHP interpreter.
3. Compare the outputs to see the different behavior between loose and strict comparison.
