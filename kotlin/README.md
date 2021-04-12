# Kotlin ANTLR4 grammar

Performance-oriented and runtime independent ANTLR4 grammar for Kotlin.

Refer to the [Kotlin Specification](https://github.com/Kotlin/kotlin-spec/tree/release/grammar) to get the most relevant 
Kotlin ANTLR4 grammar. The grammar here is based on the earlier versions of the language but has 
**improved parsing performance** compared to the official one.

## Testing

The main test is [Test.kt](examples/Test.kt), which is a compilation of a test data from the [JetBrains's repository](https://github.com/JetBrains/kotlin/tree/master/compiler/testData/psi).
There are additional tests for both Kotlin files and scripts in the corresponding folders.

## License
Licensed under the Apache 2.0