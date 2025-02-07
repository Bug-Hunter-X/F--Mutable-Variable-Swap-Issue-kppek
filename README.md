# F# Mutable Variable Swap Issue

This example demonstrates an unexpected behavior when using mutable variables and functions in F#. The `swap` function attempts to swap the values of two mutable variables, but it doesn't modify the original variables outside the function scope. 

The solution shows how to correctly swap values using mutable variables, while emphasizing best practices to avoid such confusion in the future.