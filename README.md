# Julia Function Bug: Unexpected Result for Negative Input

This repository demonstrates a bug in a simple Julia function that returns an unexpected result when given negative input. The function is designed to square positive inputs and return 0 for non-positive inputs.

## Bug Description

The `myfunction` function incorrectly handles negative inputs, resulting in unexpected output. This is due to a missing `else` condition that handles non-positive inputs appropriately.

## Bug Reproduction

1. Clone this repository.
2. Open the `bug.jl` file.
3. Run the file. Observe the unexpected output for the negative input.

## Solution

The solution involves adding an `else` condition to explicitly handle the cases where the input is less than or equal to 0.