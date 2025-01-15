# Go Nil Map Access Panic

This repository demonstrates a common error in Go: panicking due to accessing a nil map.  The `bug.go` file contains the erroneous code, while `bugSolution.go` shows how to correctly handle this situation.

## The Problem

In Go, attempting to access a map that hasn't been initialized (i.e., it's `nil`) results in a runtime panic. This can be difficult to debug, especially in larger programs.

## The Solution

The best practice is to always check for `nil` before accessing a map.  This can be done using an `if` statement or a more concise approach using the comma ok idiom.
