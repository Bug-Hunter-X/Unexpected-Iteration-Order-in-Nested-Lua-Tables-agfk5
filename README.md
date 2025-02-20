# Lua Nested Table Iteration Bug

This repository demonstrates a potential issue with Lua's `pairs` iterator when dealing with nested tables.  The `pairs` iterator does not guarantee a specific iteration order, which can lead to unexpected behavior, particularly when modifying tables within the iteration process.

The `bug.lua` file contains code that showcases this issue. The `bugSolution.lua` file demonstrates a workaround using a different iteration method that offers more predictable results.