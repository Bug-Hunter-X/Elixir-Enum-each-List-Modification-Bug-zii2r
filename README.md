This example demonstrates a common misconception in Elixir regarding list immutability.  Attempting to modify a list in place within an `Enum.each` loop will fail to produce the expected result because lists are immutable. The solution shows how to use `Enum.filter` to achieve the intended outcome.