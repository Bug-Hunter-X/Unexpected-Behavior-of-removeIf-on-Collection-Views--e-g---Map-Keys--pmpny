# Kotlin removeIf Unexpected Behavior on Collection Views

This example demonstrates a potential pitfall when using the `removeIf` function on views of collections in Kotlin, specifically the keys of a `MutableMap`.  Directly modifying the keys view doesn't behave as intuitively expected, leading to unexpected side effects.

The `bug.kt` file shows the problematic code. The `bugSolution.kt` file provides a solution illustrating a safer approach.