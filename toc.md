### Navigation

  * [index](../genindex.html)
  * [modules](../py-modindex.html) |
  * [next](appetite.html) |
  * [previous](../whatsnew/changelog.html) |
  * ![](../_static/py.png)
  * [Python](http://www.python.org/) »
  * 3.3.3 [Documentation](../index.html) »

# The Python Tutorial¶

Python is an easy to learn, powerful programming language. It has efficient
high-level data structures and a simple but effective approach to object-
oriented programming. Python's elegant syntax and dynamic typing, together
with its interpreted nature, make it an ideal language for scripting and rapid
application development in many areas on most platforms.

The Python interpreter and the extensive standard library are freely available
in source or binary form for all major platforms from the Python Web site,
[http://www.python.org/](http://www.python.org/), and may be freely
distributed. The same site also contains distributions of and pointers to many
free third party Python modules, programs and tools, and additional
documentation.

The Python interpreter is easily extended with new functions and data types
implemented in C or C++ (or other languages callable from C). Python is also
suitable as an extension language for customizable applications.

This tutorial introduces the reader informally to the basic concepts and
features of the Python language and system. It helps to have a Python
interpreter handy for hands-on experience, but all examples are self-
contained, so the tutorial can be read off-line as well.

For a description of standard objects and modules, see [_The Python Standard
Library_](../library/index.html#library-index). [_The Python Language
Reference_](../reference/index.html#reference-index) gives a more formal
definition of the language. To write extensions in C or C++, read [_Extending
and Embedding the Python Interpreter_](../extending/index.html#extending-
index) and [_Python/C API Reference Manual_](../c-api/index.html#c-api-index).
There are also several books covering Python in depth.

This tutorial does not attempt to be comprehensive and cover every single
feature, or even every commonly used feature. Instead, it introduces many of
Python's most noteworthy features, and will give you a good idea of the
language's flavor and style. After reading it, you will be able to read and
write Python modules and programs, and you will be ready to learn more about
the various Python library modules described in [_The Python Standard
Library_](../library/index.html#library-index).

The [_Glossary_](../glossary.html#glossary) is also worth going through.

  * [1. Whetting Your Appetite](appetite.html)
  * [2. Using the Python Interpreter](interpreter.html)
    * [2.1. Invoking the Interpreter](interpreter.html#invoking-the-interpreter)
      * [2.1.1. Argument Passing](interpreter.html#argument-passing)
      * [2.1.2. Interactive Mode](interpreter.html#interactive-mode)
    * [2.2. The Interpreter and Its Environment](interpreter.html#the-interpreter-and-its-environment)
      * [2.2.1. Error Handling](interpreter.html#error-handling)
      * [2.2.2. Executable Python Scripts](interpreter.html#executable-python-scripts)
      * [2.2.3. Source Code Encoding](interpreter.html#source-code-encoding)
      * [2.2.4. The Interactive Startup File](interpreter.html#the-interactive-startup-file)
      * [2.2.5. The Customization Modules](interpreter.html#the-customization-modules)
  * [3. An Informal Introduction to Python](introduction.html)
    * [3.1. Using Python as a Calculator](introduction.html#using-python-as-a-calculator)
      * [3.1.1. Numbers](introduction.html#numbers)
      * [3.1.2. Strings](introduction.html#strings)
      * [3.1.3. Lists](introduction.html#lists)
    * [3.2. First Steps Towards Programming](introduction.html#first-steps-towards-programming)
  * [4. More Control Flow Tools](controlflow.html)
    * [4.1. `if` Statements](controlflow.html#if-statements)
    * [4.2. `for` Statements](controlflow.html#for-statements)
    * [4.3. The `range()` Function](controlflow.html#the-range-function)
    * [4.4. `break` and `continue` Statements, and `else` Clauses on Loops](controlflow.html#break-and-continue-statements-and-else-clauses-on-loops)
    * [4.5. `pass` Statements](controlflow.html#pass-statements)
    * [4.6. Defining Functions](controlflow.html#defining-functions)
    * [4.7. More on Defining Functions](controlflow.html#more-on-defining-functions)
      * [4.7.1. Default Argument Values](controlflow.html#default-argument-values)
      * [4.7.2. Keyword Arguments](controlflow.html#keyword-arguments)
      * [4.7.3. Arbitrary Argument Lists](controlflow.html#arbitrary-argument-lists)
      * [4.7.4. Unpacking Argument Lists](controlflow.html#unpacking-argument-lists)
      * [4.7.5. Lambda Expressions](controlflow.html#lambda-expressions)
      * [4.7.6. Documentation Strings](controlflow.html#documentation-strings)
      * [4.7.7. Function Annotations](controlflow.html#function-annotations)
    * [4.8. Intermezzo: Coding Style](controlflow.html#intermezzo-coding-style)
  * [5. Data Structures](datastructures.html)
    * [5.1. More on Lists](datastructures.html#more-on-lists)
      * [5.1.1. Using Lists as Stacks](datastructures.html#using-lists-as-stacks)
      * [5.1.2. Using Lists as Queues](datastructures.html#using-lists-as-queues)
      * [5.1.3. List Comprehensions](datastructures.html#list-comprehensions)
      * [5.1.4. Nested List Comprehensions](datastructures.html#nested-list-comprehensions)
    * [5.2. The `del` statement](datastructures.html#the-del-statement)
    * [5.3. Tuples and Sequences](datastructures.html#tuples-and-sequences)
    * [5.4. Sets](datastructures.html#sets)
    * [5.5. Dictionaries](datastructures.html#dictionaries)
    * [5.6. Looping Techniques](datastructures.html#looping-techniques)
    * [5.7. More on Conditions](datastructures.html#more-on-conditions)
    * [5.8. Comparing Sequences and Other Types](datastructures.html#comparing-sequences-and-other-types)
  * [6. Modules](modules.html)
    * [6.1. More on Modules](modules.html#more-on-modules)
      * [6.1.1. Executing modules as scripts](modules.html#executing-modules-as-scripts)
      * [6.1.2. The Module Search Path](modules.html#the-module-search-path)
      * [6.1.3. "Compiled" Python files](modules.html#compiled-python-files)
    * [6.2. Standard Modules](modules.html#standard-modules)
    * [6.3. The `dir()` Function](modules.html#the-dir-function)
    * [6.4. Packages](modules.html#packages)
      * [6.4.1. Importing * From a Package](modules.html#importing-from-a-package)
      * [6.4.2. Intra-package References](modules.html#intra-package-references)
      * [6.4.3. Packages in Multiple Directories](modules.html#packages-in-multiple-directories)
  * [7. Input and Output](inputoutput.html)
    * [7.1. Fancier Output Formatting](inputoutput.html#fancier-output-formatting)
      * [7.1.1. Old string formatting](inputoutput.html#old-string-formatting)
    * [7.2. Reading and Writing Files](inputoutput.html#reading-and-writing-files)
      * [7.2.1. Methods of File Objects](inputoutput.html#methods-of-file-objects)
      * [7.2.2. Saving structured data with `json`](inputoutput.html#saving-structured-data-with-json)
  * [8. Errors and Exceptions](errors.html)
    * [8.1. Syntax Errors](errors.html#syntax-errors)
    * [8.2. Exceptions](errors.html#exceptions)
    * [8.3. Handling Exceptions](errors.html#handling-exceptions)
    * [8.4. Raising Exceptions](errors.html#raising-exceptions)
    * [8.5. User-defined Exceptions](errors.html#user-defined-exceptions)
    * [8.6. Defining Clean-up Actions](errors.html#defining-clean-up-actions)
    * [8.7. Predefined Clean-up Actions](errors.html#predefined-clean-up-actions)
  * [9. Classes](classes.html)
    * [9.1. A Word About Names and Objects](classes.html#a-word-about-names-and-objects)
    * [9.2. Python Scopes and Namespaces](classes.html#python-scopes-and-namespaces)
      * [9.2.1. Scopes and Namespaces Example](classes.html#scopes-and-namespaces-example)
    * [9.3. A First Look at Classes](classes.html#a-first-look-at-classes)
      * [9.3.1. Class Definition Syntax](classes.html#class-definition-syntax)
      * [9.3.2. Class Objects](classes.html#class-objects)
      * [9.3.3. Instance Objects](classes.html#instance-objects)
      * [9.3.4. Method Objects](classes.html#method-objects)
    * [9.4. Random Remarks](classes.html#random-remarks)
    * [9.5. Inheritance](classes.html#inheritance)
      * [9.5.1. Multiple Inheritance](classes.html#multiple-inheritance)
    * [9.6. Private Variables](classes.html#private-variables)
    * [9.7. Odds and Ends](classes.html#odds-and-ends)
    * [9.8. Exceptions Are Classes Too](classes.html#exceptions-are-classes-too)
    * [9.9. Iterators](classes.html#iterators)
    * [9.10. Generators](classes.html#generators)
    * [9.11. Generator Expressions](classes.html#generator-expressions)
  * [10. Brief Tour of the Standard Library](stdlib.html)
    * [10.1. Operating System Interface](stdlib.html#operating-system-interface)
    * [10.2. File Wildcards](stdlib.html#file-wildcards)
    * [10.3. Command Line Arguments](stdlib.html#command-line-arguments)
    * [10.4. Error Output Redirection and Program Termination](stdlib.html#error-output-redirection-and-program-termination)
    * [10.5. String Pattern Matching](stdlib.html#string-pattern-matching)
    * [10.6. Mathematics](stdlib.html#mathematics)
    * [10.7. Internet Access](stdlib.html#internet-access)
    * [10.8. Dates and Times](stdlib.html#dates-and-times)
    * [10.9. Data Compression](stdlib.html#data-compression)
    * [10.10. Performance Measurement](stdlib.html#performance-measurement)
    * [10.11. Quality Control](stdlib.html#quality-control)
    * [10.12. Batteries Included](stdlib.html#batteries-included)
  * [11. Brief Tour of the Standard Library - Part II](stdlib2.html)
    * [11.1. Output Formatting](stdlib2.html#output-formatting)
    * [11.2. Templating](stdlib2.html#templating)
    * [11.3. Working with Binary Data Record Layouts](stdlib2.html#working-with-binary-data-record-layouts)
    * [11.4. Multi-threading](stdlib2.html#multi-threading)
    * [11.5. Logging](stdlib2.html#logging)
    * [11.6. Weak References](stdlib2.html#weak-references)
    * [11.7. Tools for Working with Lists](stdlib2.html#tools-for-working-with-lists)
    * [11.8. Decimal Floating Point Arithmetic](stdlib2.html#decimal-floating-point-arithmetic)
  * [12. What Now?](whatnow.html)
  * [13. Interactive Input Editing and History Substitution](interactive.html)
    * [13.1. Line Editing](interactive.html#line-editing)
    * [13.2. History Substitution](interactive.html#history-substitution)
    * [13.3. Key Bindings](interactive.html#key-bindings)
    * [13.4. Alternatives to the Interactive Interpreter](interactive.html#alternatives-to-the-interactive-interpreter)
  * [14. Floating Point Arithmetic: Issues and Limitations](floatingpoint.html)
    * [14.1. Representation Error](floatingpoint.html#representation-error)

#### Previous topic

[Changelog](../whatsnew/changelog.html)

#### Next topic

[1. Whetting Your Appetite](appetite.html)

### This Page

  * [Report a Bug](../bugs.html)
  * [Show Source](../_sources/tutorial/index.txt)

### Quick search

Enter search terms or a module, class or function name.

### Navigation

  * [index](../genindex.html)
  * [modules](../py-modindex.html) |
  * [next](appetite.html) |
  * [previous](../whatsnew/changelog.html) |
  * ![](../_static/py.png)
  * [Python](http://www.python.org/) »
  * 3.3.3 [Documentation](../index.html) »

(C) [Copyright](../copyright.html) 1990-2014, Python Software Foundation.

The Python Software Foundation is a non-profit corporation. [Please
donate.](http://www.python.org/psf/donations/)

Last updated on Feb 01, 2014. [Found a bug](../bugs.html)?

Created using [Sphinx](http://sphinx.pocoo.org/) 1.2.

