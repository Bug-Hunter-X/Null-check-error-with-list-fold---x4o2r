# Dart Null Check Error with List.fold()

This repository demonstrates a common error in Dart when using the `fold` method on a list that might be null.  The code attempts to use `fold` on a nullable list without proper null checks, resulting in a runtime exception.

The `bug.dart` file showcases the erroneous code. The `bugSolution.dart` file provides a corrected version with a null check to avoid the error. 

This example highlights the importance of defensive programming when working with nullable types in Dart to prevent unexpected crashes.