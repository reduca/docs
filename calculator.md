# Calculator assignment
The goal of this task is to build a simple mathematical calculator. The calculator
should be able to parse a string statement and then execute it, returning an integer
value. The number of operands (numeric values) is arbitrary but they can all be
assumed to be integers, eg. no floating point support is required. The calculator
only has to support the plus (+) and minus (-) operators, parentheses can be disregarded.

A pseudo-interface for the calculator could look something like this:
```
interface Calculator {
  calculate(value: string): int
}
```

Example code:
```
calc = new Calculator()
calc.calculate("1 + 2") // 3
calc.calculate("1 + 2 + 3") // 6
calc.calculate("1 - 2 + 3") // 2
calc.calculate("-1 + 5 + 6 + 0") // 10
calc.calculate("10 + 10") // 20
```

You may complete the task in any programming language of choice using the standard
library of that language. You may not import external libraries whose whole purpose
is to parse numerical statements. The code should be uploaded to a git repository.

You should not spend more than 2 hours on the task and at that point it is totally
OK if the code is incomplete, buggy or ugly. We are interested in your thought
process, not your homework skills 😎.
