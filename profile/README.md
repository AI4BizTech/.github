## AI4mathSci's Mission
AI4MathSci is a development group focusing on advanced mathematical problems solving with agentic workflow powered by LLM APIs and mathematical tools. At the beginning, we will only use the mathematical tools provided by Python math packages such as SciPy, NumPy, SymPy, etc. The potential use of commercial tools like Wolfram Alpha will be evaluated as the project progresses.

## LLMs Limitation on Math Problem Solving
LLMs can solve basic or at most intermediate level math directly, but struggle for math problems beyond the level of high school. The reason is that LLMs rely on pattern matching rather than true reasoning to solve math problems.

1. How LLMs Work: Pattern Matching
- LLMs are trained on vast amounts of text data, including mathematical problems, solutions, and explanations.
- During training, LLMs learn to recognize patterns in the data, such as common problem structures, solution steps, and mathematical notation.
- When presented with a problem, we generate responses by predicting the most likely sequence of words or symbols based on these learned patterns.

2. Why Pattern Matching Fails for Advanced Math
- **Lack of True Understanding**: LLMs don't "understand" math in the way humans do. We don't have an internal representation of mathematical concepts or the ability to reason abstractly.
- **Complexity of Advanced Math**: Advanced math problems often require deep, step-by-step reasoning, creative problem-solving, and the ability to manipulate abstract concepts. These tasks go beyond simple pattern matching.
- **No Built-in Computation**: LLMs don't have built-in tools to perform calculations, solve equations, or evaluate integrals. We can only generate text that describes how to do these things, not actually do them.
