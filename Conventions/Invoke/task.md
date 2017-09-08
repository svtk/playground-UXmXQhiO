## Invoke

Objects with `invoke()` method can be invoked as a function.

You can add `invoke` extension for any class, but it's better not to overuse it:

```kotlin
fun Int.invoke() { println(this) }

1() //huh?..
```

Implement the function `Invokable.invoke()` so it would count a number of invocations.

@[Task]({"project": "kotlin-koans", "stubs": ["Conventions/Invoke/src/Task.kt"], "command": "\"Conventions/Invoke\" TestInvoke"})