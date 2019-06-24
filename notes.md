_Hallmarks of imperative languages:_
- Assignment and side-effects
- Iteration
- Order of execution is critical
Example of C (imperative)
    int fact(int n) {
        int sofar = 1;
        while (n>0) sofar *= n--;
        return sofar;
    }

_Hallmarks of functional languages:_
- Single-valued variables
- Heavy use of recursion
- Functions are first-class citizens, can be used as     parameters, function results, etc.
- Minimal use of assignments and side-effects

_Hallmarks fo object-oriented languages:_
- (Usually) Imperative
- Constructs to help programmers use "objects" - little bundles of data that know how to do things to themselves

_Functional languages:_ a style using many small
side-effect-free functions

_Why F#?_
- high level, powerful
- functional - everything returns a result
- interactive
- minimal side effects
- object oriented
- pattern matching style
- C# and F# classes can be freely mixed

_Hallmarks of functional languages:_
- Single-valued variables
- Heavy use of recursion
- Functions are first-class citizens, can be used as parameters,function results, etc.
- Minimal use of assignments and side-effects
