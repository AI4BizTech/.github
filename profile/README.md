## AI4mathSci's Mission
AI4MathSci is a development group focusing on advanced mathematical problems solving with agentic workflow powered by LLM APIs and mathematical tools. At the beginning, we will only use the mathematical tools provided by Python math packages such as SciPy, NumPy, SymPy, etc. The potential use of commercial tools like Wolfram Alpha will be evaluated as the project progresses.

## LLMs Limitation on Math Problem Solving
LLMs can solve basic or at most intermediate level math directly, but struggle for math problems beyond the level of high school. The reason is that LLMs rely on pattern matching rather than true reasoning to solve math problems.

1. **How LLMs Work: Pattern Matching**
- LLMs are trained on vast amounts of text data, including mathematical problems, solutions, and explanations.
- During training, LLMs learn to recognize patterns in the data, such as common problem structures, solution steps, and mathematical notation.
- When presented with a problem, LLMs generate responses by predicting the most likely sequence of words or symbols based on these learned patterns.

2. **Why Pattern Matching Fails for Advanced Math**
- **Lack of True Understanding**: LLMs don't "understand" math in the way humans do. They don't have an internal representation of mathematical concepts or the ability to reason abstractly.
- **Complexity of Advanced Math**: Advanced math problems often require deep, step-by-step reasoning, creative problem-solving, and the ability to manipulate abstract concepts. These tasks go beyond simple pattern matching.
- **No Built-in Computation**: LLMs don't have built-in tools to perform calculations, solve equations, or evaluate integrals. They can only generate text that describes how to do these things, not actually do them.

## AI4MathSci's Approach
Despite these limitations, LLMs can still be helpful for math-related tasks in the following ways:
- **Explaining Concepts**: LLMs can provide clear explanations of mathematical concepts, formulas, and methods.
- **Generating Code**: LLMs can write code (e.g., in Python) to solve math problems using libraries like numpy, scipy, or sympy.
- **Guiding Problem-Solving**: LLMs can suggest strategies or steps for solving problems, even if we can't always execute them perfectly.

We will build an agentic workflow to solve advanced math problems, when such a problem is received:
- A prompt is formulated to inquire an LLM through its API to generate the solution steps and Python code to solve the problems. The solution steps will become comments in the generated the Python code. Here leveraging LLM's strength is leveraged.
- The generated Python code will call functions defined in math packages such as Scipy, Numpy, Sympy, etc. Note that the actual computation are delegated to the tools and therefore avoid LLM's shortcomings
- The agentic workflow will execute the generated code and re-prompt if necessary to re-generate the code (for example, when bugs are found in the code), and iterate through to achieve a final solution or exhaust the maximum number of iterations

## Applications
Automating advanced mathematical problem-solving serves as a cornerstone for streamlining complex problem-solving across various domains, including business and engineering. These fields heavily rely on sophisticated mathematical tools as their foundation. As our project evolves, we will strategically select specific sub-domains to evaluate the practical applications of our work.
Given our focus on real-world applications, our efforts will primarily concentrate on applied and computational mathematics. This includes, but is not limited to:
- Calculus
- Linear Algebra
- Probability and Statistics
- Differential Equations
- Optimization
- Numerical Analysis
Our aim is to develop automation techniques that can handle these practical mathematical challenges effectively. While theoretical mathematics, such as theorem proving, is valuable, it will not be a primary focus of our project. Instead, we will prioritize creating solutions that can be directly implemented in industry and research settings, addressing tangible problems and enhancing decision-making processes.
As the project progresses, we will refine our approach and provide more detailed insights into our methodologies and chosen sub-domains for testing.
