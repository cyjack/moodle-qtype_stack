# Development track for STACK

Requests for features and ideas for developing STACK are all recorded in [Future plans](Future_plans.md). The
past development history is documented on [Development history](Development_history.md).

How to report bugs and make suggestions is described on the [community](../About/Community.md) page.

## Version 4.2

Note: newer versions of Maxima require that a variable has been initialised as a list/array before you can assign values to its indices.  For this reason some older questions may stop working when you upgrade to a new version of Maxima.  Please use the bulk test script after each upgrade!  See issue #343.

To do:

* Add in a version number to STACK questions.
* Add support for matrices with floating point entries, and testing numerical accuracy.
* Refactor equiv_input and MCQ to make use of the new extra options mechanism.
* Update MCQ to accept units.
* Add a base N check to the numeric input.
* Enable individual questions to load Maxima libraries.  (See issue #305)
* Add an answer test to check if decimal separator is in the wrong place (See issue #314)
* Sort out the "addrow" problem. (See issue #333)
* Expand support for input validation options to matrices (e.g. floatnum, rationalize etc.)
* Add in full parser, to address issue #324.
