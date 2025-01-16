# Dart Reduce Method Error on Empty List

This example demonstrates an uncommon error that can occur when using the `reduce` method in Dart with an empty list.  The `reduce` method requires at least one element to perform its operation, and attempting to use it on an empty list will throw a `Bad state: No element` exception.

The `bug.dart` file contains code that reproduces this error, while `bugSolution.dart` provides a corrected solution that handles the case of an empty list.

This is important to consider in applications where the input list might be empty or dynamic.