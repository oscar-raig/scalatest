For compiling:
scalac -cp scalatest_2.11-2.2.6.jar ExampleSpec.scala

For tesging:
scala -cp scalatest_2.11-2.2.6.jar org.scalatest.run ExampleSpec

Run starting. Expected test count is: 2
ExampleSpec:
A Stack
- should pop values in last-in-first-out order
- should throw NoSuchElementException if an empty stack is popped
Run completed in 297 milliseconds.
Total number of tests run: 2
Suites: completed 1, aborted 0
Tests: succeeded 2, failed 0, canceled 0, ignored 0, pending 0
All tests passed.

