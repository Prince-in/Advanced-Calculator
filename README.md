# Advanced-Calculator
- We want to design a calculator application that allows the user to type in an expression such as (2+6)/4 + 6 and returns the result of evaluating the expression.
- The user will type an expression in a window and click the enter button, following which the expression is to be evaluated, and the result is to be displayed.
- If the input expression is typed incorrectly, then the output should indicate that there was an error and that the user should enter it again.
- The calculator’s GUI (Graphical User Interface) is created using TKinter, Python’s standard GUI framework. It is defined as a class GUI, and is already provided to you. See the **coding**

- First, we start off by building a simple calculator which evaluates simple arithmetic expressions to get the application up and running.
- For this part, the arithmetic expression contains 1 operator and 2 operands. The operator can be among “+” (add), “-” (subtract), “*” (multiply), or “/” (divide). The operands are integers. There can be any amount of spaces present in the expression.
- Some valid expressions are: “2 + 3”, “1-2”, “4  *1 ”. Some invalid expressions are: “2 + 3 - 4”, “2-”.

- Now that the simple calculator is up and running, we want to extend its functionality to support advanced expressions. Stacks are a good data structure for managing the computation required for evaluating expressions.
- Please implement a Stack class and its core methods. Complete the Stack class defined in the starter code.

- - With a stack data structure, we are now ready to support advanced expressions containing multiple operators and parenthesis, such as “2 + {3 - (4 * 2 + 1)}”
- As before, the operators can be “+” (add), “-” (subtract), “*” (multiply), or “/” (divide), and the operands are integers, and there are variable whitespaces. There can be multiple operators and brackets.
- We would like to support both ‘{ }’ and ‘()’ types of brackets. We assume the following semantics: Open brackets must be closed by the same type of brackets and open brackets must be closed in the same order. Further, assume that ‘()’ brackets can only contain ‘()’ brackets. But ‘{}’ brackets can contain both ‘{}’ and ‘()’ brackets.
