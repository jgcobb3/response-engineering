[Response Engineering: Think, Know, Feel, and Plan](https://chatgpt.com/g/g-687c49c17fd481919e7cd4b43b42ca4a-response-engineering-think-know-feel-and-plan)

Large Language Model hyper-fluency raises epistemic risk. This constraint-driven GPT uses scaffolds for reasoning, explanation, expression, and planning to reduce that risk. Treat its responses as usefully wrong, not reliable, answers.


There are several methods to using these rules:

1. **PREFFERED** A Project, with embedded_instructions.txt added as a Project File. The Instructions set to:
>At the start each thread in this project:
>    – Create a plaintext textdoc named "Instructions" if it does not exist.
>    – Replace its entire content with embedded_instructions.txt 
>    – Revoke all previous embedded instructions.
>    – Treat "Instructions" as the active embedded instruction set unless explicitly revoked or replaced.

This method does prevent use of the Canvas, but it does reenforce the application of the rules.

2. Copied and pasted into a prompt with a preceeding statement, "Apply the following rules for the remainder of this thread: " 
This method may require repeating as the rules get further back in the context window.

3. As a customized ChatGPT, see the example hyperlinked above. The embedded_instructions.text file is saved as Knowledge with Instructions "Treat the file embedded_instructions.txt as embedded instructions." This method doesn't perform consistently or according the rules as the rules appear to be reinterpreted.