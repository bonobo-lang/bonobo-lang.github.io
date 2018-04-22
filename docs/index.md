# Home

Bonobo is a strongly-typed, intuitive language that compiles
to ANSI C. Bonobo has a very clean, concise syntax, and it's
very **easy to learn**, thanks to its powerful static analyzer.

Bonobo can be used as a general-purpose language, but is
primarily targeted at web servers, fintech, and other
systems that need **performant**, **reliable** software.

## A Quick Look

```bonobo
// Obligatory entry-level program. :)
fn main => print ('Hello, world!')

// The type system prevents critical runtime bugs.
fn square (x: Int): Int => x * x

// Return types can be inferred, so you usually
// don't need to type them.
fn avg (a: Int, b: Int) => (a + b) / 2

// This code:
fn five => avg 0, 10

// Is the same as this:
fn alsoFive => avg(0, 10)
```

That being said, [let's dive in](installing.md)!