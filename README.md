# JavaScript exercises

Nine standalone examples of JavaScript loops, arrays, functions, and strings. Each file prints its example result to the terminal; there are no dependencies or build tools.

## Run

Install Node.js, then run an individual example from this directory:

```sh
node J2.js
```

Expected output: `10`.

## Exercise map

| File | Concept | Example result |
| --- | --- | --- |
| `J1.js` | `for` loop | Numbers 1 through 10, one per line |
| `J2.js` | Sum an array | `10` |
| `J3.js` | Find the largest array member | `9` |
| `J4.js` | Even/odd classification | `Even`, then `Odd` |
| `J5.js` | Reverse a string | `olleh` |
| `J6.js` | Merge arrays using spread | `[1, 2, 3, 4]` |
| `J7.js` | Filter even numbers | `[2, 4, 6]` |
| `J8.js` | Template literal | `Hello Alice, welcome!` |
| `J9.js` | Arrow function | `Hello, Alice` |

Console spacing for arrays depends on Node.js. Change the inputs at the bottom of each file to experiment. `findLargest` assumes a nonempty array; `reverseString` reverses UTF-16 code units rather than user-perceived Unicode characters. No automated test suite is included.

## More documentation

- [Source, command, and configuration reference](docs/REFERENCE.md)
- [Contributing](CONTRIBUTING.md)
