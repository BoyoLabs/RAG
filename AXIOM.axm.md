# Axiom (AXM)
*The Command Prompt for LLMs*

## 1. Philosophy
Axiom is a **Declarative Structured Prompting Language** designed to shift the interaction with Large Language Models from *conversational prose* to *deterministic specification*. 

Traditional prompting relies on "natural language," which is prone to ambiguity, instruction drift, and noise. Axiom treats the prompt as a technical specification. It establishes "ground truths" (axioms) and a logical execution flow, ensuring that the model's reasoning process is structured, predictable, and efficient.

**Core Concept:** If a conversation is a sketch, Axiom is the architectural blueprint.

## 2. Why Axiom? (The Advantage)

1.  **Zero Drift**: By using headers, the model is less likely to "forget" instructions in the middle of a prompt.
2.  **High Signal-to-Noise**: Eliminates conversational fluff, reducing token waste and increasing precision.
3.  **Modular Iteration**: Users can update a specific `# Logic` or `# Variable` block without needing to rewrite the entire prompt.
4.  **Deterministic Reasoning**: By specifying the flow (`->`), the user dictates *how* the model thinks, not just what it produces.

---

## 3. Basic Syntax (The Atomic Units)

### Headers (Operators)
Axiom uses `# Label :` to define the role and intent of a block. This separates the **Operator** (the instruction) from the **Operand** (the data).

| Header | Purpose |
| :--- | :--- |
| `# Persona :` | Defines the identity, expertise, and behavioral constraints of the agent. |
| `# Context :` | Provides the environment, background knowledge, or existing state. |
| `# Query :` | The specific question or request. |
| `# Goal :` | The desired final outcome or end-state. |
| `# Constraints :` | Hard boundaries, "NOT" rules, and critical restrictions. |
| `# Variable :` | Defines a reusable piece of information. |
| `# Output Format :` | Specifies the structure of the response (e.g., JSON, Table, Markdown). |
| `# Return :` | Used for the final answer or to signal a completed process. |

### Variables
Axiom allows for state management via variable declaration:
**Syntax:** `# Variable : name [variableName] | value [Variable value]`

---

## 4. Logic & Control Flow

Axiom introduces programmatic structures to control the model's "thought process."

### The Sequence Operator (`->`)
Defines a linear, step-by-step cognitive pipeline.
`Step 1 -> Step 2 -> Step 3`
*The model is instructed to complete each step before proceeding to the next.*

### Conditionals (`IF / ELSE`)
Introduces branching logic based on the state of the context.
**Syntax:** `IF condition : [action]`
**Syntax:** `IF condition : [action] ELSE : [alternative]`

*   **Skipping:** If an `IF` condition does not resolve as true, the statement is ignored or skipped, and the flow continues.

### Boolean Logic (`OR`)
The `OR` operator can be used in two primary ways:
1.  **Conditional Trigger:** `[IF (A OR B) : [action]]` (Action triggers if either A or B is true).
2.  **Path Alternative:** `[Task A] OR [Task B]` (The model chooses the most appropriate path based on the context).

### Nesting
Logic can be nested to create complex decision trees.
`Step 1 -> [IF condition : [Step 2 -> Step 3] ELSE : [Step 4]] -> Step 5`

---

## 5. Implementation Examples

### Case 1: The Simple Query (Symmetry)
`# Persona : Technical Writer`
`# Context : Product documentation for a new API`
`# Query : Summarize the authentication flow`
`# Output Format : Bulleted List`

### Case 2: Complex Logic Flow (The "CMD" Style)
`# Persona : Agentic Engineer`
`# Variable : name [API_URL] \| value [https://api.example.com/v1]`
`# Logic : Fetch Data from API_URL -> [IF CORS issue : [Check Headers -> Verify Origin]] ELSE [Parse JSON] -> Format Result`
`# Output Format : JSON`
`# Query : Execute the logic flow and return the final data.`
