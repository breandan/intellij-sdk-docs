---
title: 7. Folding Test
---

In this test we will check if the folding builder, implemented in the
[Folding Builder](/tutorials/custom_language_support/folding_builder.md)
section of the
[Custom Language Support Tutorial](/tutorials/custom_language_support_tutorial.md),
works as we expect.

### 7.1. Define test data

Create a file *FoldingTestData.java*.

```java
public class Test {
    public static void main(String[] args) <fold text='{...}'>{
        System.out.println("<fold text='http://en.wikipedia.org/'>simple:website</fold>");
    }</fold>
}
```

### 7.2. Define a test

```java
public void testFolding() {
    myFixture.configureByFiles("DefaultTestData.simple");
    myFixture.testFolding(getTestDataPath() + "/FoldingTestData.java");
}
```

### 7.3. Run the test

Run the test and make sure it's green.

-----

[Previous](rename_test.html)
[Top](../writing_tests_for_plugins.html)
[Next](find_usages_test.html)
