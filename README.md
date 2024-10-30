 Testing Report for the StringProcessor Class

Overview  
In this report, I summarize my testing process for the StringProcessor class, which includes methods for checking password strength, counting digits, counting words, and evaluating mathematical expressions.

Test Cases

Password Strength Check  
- Test Case 1:  
  - Input: "Strong1@"  
  - Expected Result: true  
  - Actual Result: true  
  - Outcome: Passed  

- Test Case 2:  
  - Input: "weakpass"  
  - Expected Result: false  
  - Actual Result: false  
  - Outcome: Passed  

Counting Digits  
- Test Case 1:  
  - Input: "Hello 123!"  
  - Expected Result: 3  
  - Actual Result: 3  
  - Outcome: Passed  

- Test Case 2:  
  - Input: "No digits here."  
  - Expected Result: 0  
  - Actual Result: 0  
  - Outcome: Passed  

Counting Words  
- Test Case:  
  - Input: "This is a sample input."  
  - Expected Result: 5  
  - Actual Result: 5  
  - Outcome: Passed  

Evaluating Mathematical Expressions  
- Test Case 1:  
  - Input: "2 + 3"  
  - Expected Result: 5.0  
  - Actual Result: 5.0  
  - Outcome: Passed  

- Test Case 2:  
  - Input: "(1 + 2) * 3 - 1"  
  - Expected Result: 8.0  
  - Actual Result: 8.0  
  - Outcome: Passed  

Issues Encountered  
During my testing process, I encountered an issue with evaluating expressions using the JavaScript engine. Some expressions threw exceptions due to incorrect formatting. I addressed these issues by ensuring that the input expressions were valid and well-formed before evaluation.

Conclusion  
I successfully tested the StringProcessor class, and all test cases passed without any significant issues. I learned how to create unit tests using JUnit and improved my understanding of handling exceptions in code.
