 COOL Stack Implementation

This project implements a stack data structure using a linked list in COOL (Classroom Object Oriented Language).

 Project Structure

- `stack.cl`: The main COOL source file containing the stack implementation and test code.

How to Run

1. Ensure you have the COOL compiler and simulator installed.
2. Compile the code:
coolc stack.cl

3. Run the generated assembly code with the SPIM simulator:
spim stack.s

 Implementation Details

- The stack is implemented using a linked list of `ListNode` objects.
- The `Stack` class provides `push`, `pop`, `peek`, and `isEmpty` operations.
 Example Output

When you run the program, it will push three integers (10, 20, 30) onto the stack and then pop them, printing the popped values in reverse order (30, 20, 10).
注意：由于无法实际运行COOL代码，以上输出结果为预期结果。实际运行时，请确保COOL环境配置正确。
