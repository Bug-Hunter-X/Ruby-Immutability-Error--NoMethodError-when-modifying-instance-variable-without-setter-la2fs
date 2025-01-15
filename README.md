# Ruby Immutability Error

This repository demonstrates a common error in Ruby related to the implicit immutability of instance variables when no setter method is defined.

The `bug.rb` file contains code that attempts to modify an instance variable without a corresponding setter method, resulting in a `NoMethodError`.

The `bugSolution.rb` file provides a corrected version of the code, demonstrating how to either define an explicit setter method or use a mutable data structure (like an array or hash) to achieve the desired behavior.

This example highlights the importance of understanding how instance variables are handled in Ruby and the need to explicitly define setters for mutable properties.