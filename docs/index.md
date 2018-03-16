# Home

Bonobo is a strongly-typed, intuitive language that compiles
to ANSI C. Bonobo has a very clean, concise syntax, and it's
very **easy to learn**, thanks to its powerful static analyzer.

Bonobo can be used as a general-purpose language, but is
primarily targeted at web servers, fintech, and other
systems that need **performant**, **reliable** software.

## A Quick Look

```bonobo
// No parentheses when not necessary.
f main => print 'Hello, world!'

// The type system prevents critical runtime bugs.
f square (x: Num): Num => x * x

// Return types can be inferred, so you usually
// don't need to type them.
f avg (a: Num, b: Num) => (a + b) / 2

// This code:
f five => avg 0, 10

// Is the same as this:
f alsoFive => avg(0, 10)
```

That being said, [let's dive in](installing.md)!