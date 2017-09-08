## Partition
Implement `Shop.getCustomersWithMoreUndeliveredOrdersThanDelivered()` using
[`partition`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/kotlin.-iterable/partition.html).

```kotlin
val numbers = listOf(1, 3, -4, 2, -11)
val (positive, negative) = numbers.partition { it > 0 }
positive == listOf(1, 3, 2)
negative == listOf(-4, -11)
```

Note that [destructuring declaration](http://kotlinlang.org/docs/reference/multi-declarations.html) syntax is used in this example.

@[Task]({"project": "kotlin-koans", "stubs": ["Collections/Partition/src/Task.kt"], "command": "\"Collections/Partition\" TestPartition"})