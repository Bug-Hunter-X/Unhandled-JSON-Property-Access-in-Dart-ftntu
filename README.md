# Unhandled JSON Property Access in Dart

This repository demonstrates a common error in Dart when dealing with JSON responses: accessing a property that might not exist in all objects within a list.  The code attempts to access the 'name' property from each item, but if an item is missing this property, it will throw an exception.

The `bug.dart` file shows the erroneous code. The `bugSolution.dart` file provides a solution that addresses this issue using null-aware operators and error handling.
