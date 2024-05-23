Absolutely! Here are 10 tricky objective questions on loops in Java, designed to test your understanding:

**1. Infinite Loop:**

```java
for (int i = 10; i >= 0; i++) {
    System.out.println(i);
}
```
What is the output of the above code?

(a) Numbers 10 to 0 printed once
(b) Infinite loop, prints numbers 10 to 0 repeatedly
(c) Compile-time error
(d) No output

**2. Nested Loop Counting:**

How many times does the `println` statement execute in this nested loop?
```java
for (int i = 0; i < 3; i++) {
    for (int j = 0; j < 4; j++) {
        System.out.println("Inner loop");
    }
}
```

(a) 3
(b) 4
(c) 7
(d) 12

**3. Loop Condition Trickery:**

```java
int x = 5;
while (x > 0) {
    x = x - 2;
    System.out.println(x);
}
```

What values are printed by this loop?

(a) 5, 3, 1
(b) 3, 1, -1
(c) 5, 3, 1, -1
(d) Infinite loop

**4. Loop Variable Scope:**

```java
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}
System.out.println(i); // Line X
```
What happens at `Line X`?

(a) Prints 5
(b) Prints 4
(c) Compile-time error: `i` is not accessible
(d) Runtime error

**5. While Loop Initialization:**

```java
int num = 1;
while (num <= 10) {
    // Code here
}
```
Is it necessary to initialize `num` before the `while` loop?

    (a) Yes, always
    (b) No, it can be initialized inside the loop
    (c) Only if `num` is not declared outside the loop
    (d) It depends on the compiler

**6. Loop Termination with `break`:**

```java
for (int i = 0; i < 10; i++) {
    if (i == 5) {
        break;
    }
    System.out.println(i);
}
```

What is the output of this code?

(a) 0 1 2 3 4 5
(b) 0 1 2 3 4
(c) 0 1 2 3 4 6 7 8 9
(d) 5

**7. Nested Loop Behavior:**

In nested loops, which loop runs faster?

(a) The outer loop
(b) The inner loop
(c) Both run at the same speed
(d) It depends on the loop conditions

**8. Loop Counter Modification:**

```java
for (int i = 0; i < 5; i++) {
    i++;
    System.out.println(i);
}
```
What is the output of this code?

(a) 0 1 2 3 4
(b) 1 3 5
(c) 2 4
(d) None of the above

**9. While vs. For:**

Which loop is best suited for iterating over a collection of known size?

(a) `while` loop
(b) `for` loop
(c) `do-while` loop
(d) Any loop can be used

**10. Loop Exit Condition:**

When does a `do-while` loop guarantee execution of its code block at least once?

(a) Always
(b) Never
(c) Only if the condition is true
(d) Only if the condition is false

**Answers:**

1. **(b)**
2. **(d)**
3. **(b)**
4. **(c)**
5. **(a)**
6. **(b)**
7. **(b)**
8. **(c)**
9. **(b)**
10. **(a)**
