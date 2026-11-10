+++
author = "Author"
title = "Code Syntax Guide"
date = "2026-11-09"
tags = ["markdown", "syntax", "code",]
showWordCount = true
+++

This article shows example fenced code blocks.

## Inline Code

`print("Hello World")`

## Code Block With No Syntax Highlighting

```
# Fibonacci sequence
def fib(n):
  if fib <= 1:
    return n

  return fib(n-1) + fib(n-2)
```

## Code Blocks With Syntax Highlighting

```py
# Fibonacci sequence (Python)
def fib(n: int) -> int:
    if n <= 1:
        return n

    return fib(n - 1) + fib(n - 2)

```

```go
// Fibonacci sequence (Go)
func fib(n int) int {
	if n <= 1 {
		return n
	}
	return fib(n-1) + fib(n-2)
}

```

Notice how the Python 'tabs' are four spaces, while the Go tabs are actual tabs!
