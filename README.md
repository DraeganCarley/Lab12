# Number Theory: Addition


In this lab, you’ve learned about One Hot and Binary state machines and how to build them.


## Rubric


| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |


## Name
Group #7 - Aaron Ray and Draegan Carley
## Summary
In this lab, we learned how to create finite state machines using One Hot and Binary encoding in Verilog. We used state tables and K-maps to determine the logic needed to move between five different states. We also learned how to use D flip-flops to store the current state and how the input determines which state comes next. After building both versions, we were able to see how they perform the same function while using different numbers of flip-flops.

## Lab Questions

### Compare and contrast One Hot and Binary encodings
One Hot and Binary encoding are both methods used to represent states in a state machine. The main difference is that One Hot uses one flip-flop for each state, while Binary uses combinations of bits to represent the states. In our lab, One Hot required five flip-flops while Binary only required three. One Hot makes it easier to determine which state is active because only one bit is high at a time. Binary uses fewer flip-flops but requires more logic to determine the current and next states.
### Which method did your team find easier, and why?
Our team found One Hot encoding easier because each state had its own flip-flop, making it easier to understand how the machine moves between states. It was also easier to follow the logic when using the state table and K-maps because we could look at each state individually. Binary encoding was a little more complicated because we had to keep track of combinations of bits to determine which state was active.
### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.
Choosing between One Hot and Binary encoding depends on the number of states and the resources available on the FPGA. One Hot would be useful when we have fewer states or want simpler logic, but it requires more flip-flops. Binary would be better when we have more states and want to save resources because it uses fewer flip-flops. However, Binary can require more combinational logic to determine the next state. If we were working with limited flip-flops, Binary would probably be the better option, while One Hot might be easier to implement and troubleshoot.
