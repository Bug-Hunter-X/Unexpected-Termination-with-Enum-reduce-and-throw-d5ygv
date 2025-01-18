# Elixir Bug: Unexpected Termination with Enum.reduce and throw

This repository demonstrates a potential issue with using `throw` inside an `Enum.reduce` function in Elixir. The code attempts to sum a list of numbers but throws an exception when it encounters the number 3. This abrupt termination can lead to unexpected behavior, especially if the calling function does not handle the exception correctly.

The solution shows how to handle the exception using a `try...catch` block, ensuring that the code gracefully handles the interruption and provides a way to recover or report the error appropriately.