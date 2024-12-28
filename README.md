# Kotlin's map function behavior with empty and nullable lists

This example illustrates the behavior of the `map` function in Kotlin when dealing with empty and nullable lists. The `map` function transforms each element of a list into a new value using a given lambda function.

The example demonstrates three scenarios:

1. **Non-empty list:** A standard list is mapped, resulting in a new list with transformed elements.
2. **Empty list:** An empty list is mapped, resulting in an empty list – no exception or error is thrown.
3. **Nullable list:** A nullable list is mapped using the safe call operator (`?.`). If the list is null, the result is also null; otherwise, the mapping happens as expected. 

This behavior ensures that the code is safe and robust when handling potential null values and empty collections.