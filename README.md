# Unexpected Behavior with Negative Input in TypeScript Function

This repository demonstrates an unexpected behavior in a simple TypeScript function when provided with negative input. The `printNumbers` function is designed to print numbers from 1 to n, but it does not handle negative input gracefully. Instead of throwing an error or providing feedback, it silently does nothing.

## Bug Report

The function `printNumbers` fails to provide an appropriate response to a negative input (n < 0).  Expected behavior is either an error message or some indication of the invalid input.

## Solution

The provided solution adds input validation to handle negative input, throwing a more informative error message.