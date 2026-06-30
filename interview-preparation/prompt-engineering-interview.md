# Prompt Engineering Interview Questions

## Q1. What is Prompt Engineering?

### Answer

Prompt Engineering is the process of designing, structuring, testing, and refining prompts to obtain accurate, relevant, and high-quality responses from Large Language Models (LLMs) such as ChatGPT, Gemini, Claude, and Microsoft Copilot.

A well-designed prompt provides clear instructions, business context, constraints, and expected output, enabling the AI model to generate more consistent and useful results.

### Example

Instead of asking:

> Generate Login Test Cases.

A better prompt would be:

> You are a Senior QA Automation Architect. Generate Functional, Security, API, Accessibility, and Performance test cases for the Login feature and return the output in a Markdown table.

### Interview Tip

Prompt Engineering is similar to writing clear software requirements. The more precise the instructions, the better the AI response.

---

## Q2. What is Zero-shot Prompting?

### Answer

Zero-shot Prompting is a prompting technique where the AI model is asked to perform a task without providing any examples.

The model relies entirely on its pre-trained knowledge to generate the response.

### Example

Generate Login Test Cases.

### When to Use

- Quick tasks
- Brainstorming
- Initial drafts
- General questions

### Advantages

- Fast
- Easy to create
- Requires minimal effort

### Limitations

- Output quality may vary
- May miss business-specific requirements

### QA Example

Generate API test cases for a Login API.

---

## Q3. What is Few-shot Prompting?

### Answer

Few-shot Prompting is a technique where one or more examples are provided before asking the AI to perform a similar task.

These examples help the model understand the expected format, style, and quality of the output.

### Example

Example:

Input:

Registration Page

Output:

- Verify mandatory fields
- Verify email validation
- Verify password strength

Now generate test cases for the Login page.

### Advantages

- More accurate responses
- Better consistency
- Better formatting

### Limitations

- Longer prompts
- Uses more tokens

### QA Example

Provide one sample Selenium test before asking AI to generate automation scripts for another feature.

---

## Q4. What is Chain of Thought (CoT) Prompting?

### Answer

Chain of Thought Prompting encourages the AI model to reason through a problem step by step before producing the final answer.

Instead of immediately generating the response, the AI explains its reasoning process, which often improves the quality and accuracy of complex tasks.

### Example

Analyze the Login feature step by step before generating test cases.

### When to Use

- Root Cause Analysis
- Bug Investigation
- Complex Business Rules
- Test Strategy Preparation

### Advantages

- Better reasoning
- More detailed explanations
- Higher-quality output

### Limitations

- Longer responses
- Higher token usage

### QA Example

Analyze why the login feature is failing before suggesting possible fixes.

---

## Q5. What is Hallucination?

### Answer

Hallucination occurs when an AI model generates incorrect, misleading, or completely fabricated information while presenting it as if it were factual.

Hallucinations happen because LLMs predict the most likely sequence of words rather than verifying facts.

### Example

An AI invents an API endpoint that does not exist in the application.

### How to Reduce Hallucinations

- Provide clear business context.
- Supply reference documents.
- Use structured prompts.
- Ask the AI to mention assumptions.
- Verify AI-generated outputs before implementation.

### QA Example

Always validate AI-generated test cases against the actual business requirements.

---

## Q6. What is Context Window?

### Answer

The Context Window is the amount of information (measured in tokens) that an AI model can remember and use during a single conversation or request.

If the prompt exceeds the model's context window, older information may be forgotten or truncated.

### Example

If an AI model supports a 128K token context window, it can process approximately hundreds of pages of text in one conversation, depending on the content.

### Why It Matters

A larger context window allows the AI to:

- Understand long documents
- Analyze large codebases
- Maintain conversation history
- Generate better responses using more context

### QA Example

A large context window enables AI to analyze an entire Software Requirement Specification (SRS) and generate comprehensive test cases.

---

# Quick Interview Summary

| Question | One-Line Answer |
|----------|-----------------|
| What is Prompt Engineering? | Designing effective prompts to obtain accurate AI responses. |
| Zero-shot Prompting | Asking AI without providing examples. |
| Few-shot Prompting | Providing examples before asking AI to perform a task. |
| Chain of Thought | Asking AI to reason step by step. |
| Hallucination | AI generating incorrect or fabricated information. |
| Context Window | The amount of information an AI model can process in one interaction. |

---

# Interview Tips

- Explain concepts using real-world QA examples.
- Mention practical use cases from your GitHub repository.
- Differentiate similar concepts (e.g., Zero-shot vs. Few-shot Prompting).
- Emphasize that AI-generated outputs should always be reviewed and validated.
- Relate prompt engineering to software requirements: clear inputs produce better outputs.
