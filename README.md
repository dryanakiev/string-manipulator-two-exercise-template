# string-manipulator-two-exercise-template

Write a StringManipulator class that contains two methods: Reverse and Truncate. The Reverse method takes a string as input and returns the string with its characters reversed. The Truncate method takes a string and an integer length as input, and returns the first length characters of the string. If the length of the input string is less than or equal to length, the original string is returned unchanged.

Then, write unit tests to ensure that all methods of the StringManipulator class are working correctly. Your tests should cover a range of scenarios, including:

1. Testing for correct reversal of a simple string.
2. Testing for correct reversal of a longer string.
3. Testing for correct truncation of a simple string.
4. Testing for correct truncation of a longer string.
5. Testing for correct handling of null input values.
6. Testing for correct handling of empty input values.
7. Testing for correct handling of zero length in the Truncate method.

Here's a sample code structure to get you started:

```
public class StringManipulator {
  public string Reverse(string str) {
    // TODO: Implement string reversal
  }

  public string Truncate(string str, int length) {
    // TODO: Implement string truncation
  }
}

[TestFixture]
public class StringManipulatorTests {
  [Test]
  public void TestReverse() {
    // TODO: Write test for reversal method
  }

  [Test]
  public void TestTruncate() {
    // TODO: Write test for truncation method
  }
}
```

Your task is to complete the TODO comments with the appropriate code to implement the StringManipulator class and its methods, and write the unit tests to verify their correctness. Good luck!
