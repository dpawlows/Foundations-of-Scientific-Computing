Good coding practices- Documentation
====================================

One of the main purposes of writing software is to take
a task that would be repetitive for a human and make the computer
do it. Running the same piece of software over and over again
is a fundamental part of computing. Not only will you use
specific files over and over again, you will find yourself using
code blocks that you've created before multiple times.

For this reason, it should be obvious that documenting your
code is an important best practice. While you might
perfectly understand what your software is doing when you write
it and use it a bunch, if you put it aside for a week or two and
then come back to it, things may not be so clear.

Documentation can take a few forms. At the most basic level, adding
comments to the code itself can serve to explain the basic purpose
of that piece of software, how it should be used, and a description
of the code itself (including sources where appropriate). At a
higher level, it might be necessary to include separate documents
with the files that make up a complex program or module, such
as a README, to explain how your program works and how to use it.

In this course, we will often be dealing with programs that
are executed with a single file, so higher level documentation
isn't usually necessary. But, commenting your code is a practice
that you should adopt and use consistently.

In python, there are a couple ways that you can include
comments in your file:

* A ``#`` symbol tells python to ignore all text from that point until the
  end of the line. If the `#` is at the beginning of a line, the
  entire line is ignored
* Triple quotes ``'''`` are used to comment out multiple lines. For example:
  ::

    '''
    This is a comment block.
    All of these lines would be ignored by the python
    interpreter when the file is executed.
    '''
* If the ``'''`` comment block
  is used right after a function definition, the comment becomes
  part of that function's `doc string <https://www.geeksforgeeks.org/python-docstrings/>`_, which is a special
  attribute of every function that serves to provide usage information
  for that function.

Here are some
guidelines for commenting your code:

* At the top of your program, briefly describe the purpose of the
  program.
* If you define any functions, briefly describe their purpose and usage.
  Usage should include a description of the arguments that the function
  needs to work as well as what the function will return to the program
  that called it.
* Include comments for individual lines of code that depend on
  external parameters. For example, in physics we may use the
  software to solve a particular equation. Describe the equation and
  provide a source if appropriate. Good use of variable names
  should help when including fundamental constants in your
  code, but sometimes a comment may be necessary to avoid ambiguity.
* Include comment blocks if complex logic is used. It's difficult to
  define "complex" as it will be different for everyone. If it takes
  you more than a few seconds to understand what the part of the
  code is doing, consider adding a comment as a reminder.


There aren't any specific requirements for commenting your software,
but keep in mind that the goal is to make it so it is easy for you, or
someone that might use your code, to understand how it works without
turning your file into a novel. Single line comments are usually
sufficient except maybe when describing an entire file (or module)
when some extra description may be warranted. Either way,
get in the habit of adding comments to your code right away. Your
future self will thank you for it.
