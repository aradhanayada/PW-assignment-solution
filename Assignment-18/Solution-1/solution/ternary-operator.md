### Ternary Operator in Programming

In programming, the ternary operator is a concise way to write a simple conditional expression. It is often used as a shorthand for the `if-else` statement. The syntax of the ternary operator is as follows:

result = condition ? expression_if_true : expression_if_false;

condition: The boolean expression that determines which of the two expressions is evaluated.

expression_if_true: The value assigned to result if the condition is true.

expression_if_false: The value assigned to result if the condition is false.

**Example in JavaScript:**
        
        let age = 20;
        let eligibility = (age >= 18) ? "Eligible to vote" : "Not eligible to vote";
        console.log(eligibility);
In this example, if the age is greater than or equal to 18, the eligibility will be set to "Eligible to vote"; otherwise, it will be set to "Not eligible to vote."
