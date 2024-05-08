# lab-report3
**Failure Inducing Input**
```

@Test
    public void testReversedNonFailure() {
      int[] inputArray = {5, 4, 3, 2, 1}; // Already reversed array
      int[] expected = {0, 0, 0, 0, 0}; // Expected output
      int[] result = ArrayExamples.reversed(inputArray); // Calling the buggy method
      assertArrayEquals(expected, result); // Assertion
  }
}
```


**Non failure inducing input**
```
@Test
    public void testReversedNonFailure() {
      int[] inputArray = {5, 4, 3, 2, 1}; // Already reversed array
      int[] expected = {0, 0, 0, 0, 0}; // Expected output
      int[] result = ArrayExamples.reversed(inputArray); // Calling the buggy method
      assertArrayEquals(expected, result); // Assertion
  }
}
```

**Tests output**

