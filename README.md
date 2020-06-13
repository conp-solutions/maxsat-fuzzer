# maxsat-fuzzer
Implements a fuzzer for maxsat solvers

### Building

Run "make" to build the formula generation tool.

### Usage

To use the fuzzer on a MaxSat solver "<maxsat-solver>", use the following call.
The tool requires a number of attempts for the tests.

 ./fuzz.py <tests> "<maxsat-solver>"
