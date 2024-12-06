# Ruby Bug: Unexpected Behavior with Direct Instance Variable Access

This repository demonstrates a common Ruby bug related to directly manipulating instance variables using `instance_variable_set` and `instance_variable_get`.  Directly accessing and modifying instance variables bypasses accessor methods (getters and setters), potentially leading to inconsistencies and making code difficult to maintain and debug.

The `bug.rb` file shows the problematic code, while `bugSolution.rb` provides a corrected version that uses accessor methods for better encapsulation and maintainability.  This improved approach allows for controlled access to the instance variables and makes the code easier to understand and modify.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository directory.
3. Run `ruby bug.rb`. This will show the unexpected behavior.
4. Run `ruby bugSolution.rb` to see the correct behavior.
