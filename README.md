# Bench: A command line benchmark tool.

'Bench' is a command line tool for benchmarking command line tools that
operate on files and output performance data to stdout.  Specifically 'bench'
helps the user by:

  1) Ingesting template files and doing simple string replacement to generate
test cases
  2) Invoking the process with custom flags and the instantiated template
  3) Processing the stdout in an **extremely basic manner**, recording words
at particular indexes
  4) Periodically polling the memory use
  5) Recording information including the test case, specified values from
stdout, and memory use, in a CSV file
