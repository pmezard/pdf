# Purpose of the fork

This fork of `rsc.io/pdf` extends the package API with:
- A `Tokenize` function to help parsing PDF streams
- Two `Value.KeyId()` and `Value.IndexId()` methods helping detecting cycles
  when traversing the object graph.

