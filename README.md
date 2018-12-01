# scheme-compiler-in-ruby
Simple compiler and VM for a subset of Scheme, written in Ruby. Supports print statements, addition, subtraction, and multiplication. 
Bootstrap code and files provided by Thomas Austin.

Dependencies:<br>
Ruby 2.3.7+

Usage:<br>
`ruby compiler.rb  test.scm test.byco`<br>
Compiles code from the Scheme file and outputs to the bytecode file.<br>

`ruby vm.rb test.byco`<br>
VM interprets bytecode file and outputs results of calculations to console window.
