**Chain of Function**\
Prompting methods such as Chain of
Thoughts (CoT) improve the performance
of Large Language Models (LLMs) by
decomposing tasks into steps. To solve
each step accurately, approaches like
Program Aided Language (PAL) models
prompt LLMs to generate Python code and
execute the code with an external
interpreter. Here LLMs attempt to map
problem description into low level
instructions, which may be challenging for
complicated domain-specific applications.
In this paper we present Chain of Function
(CoF), which prompts LLMs with domain-
specific function libraries. LLMs generate
function calls in each step, and receive
intermediate feedback from each function
execution. This allows LLMs to simplify
problem solving by reasoning at abstract
function level instead of atomic
operations. We demonstrate the
effectiveness of CoF across mathematical,
symbolical, and algorithmic reasoning
tasks from popular benchmarks.
Experiments show satisfactory results by
reasoning at function level using domain
specific libraries. Various extensions of
CoF including solving problems with
multi-libraries and blended libraries, as
well as automatic generation of domain
specific libraries, are also studied in this
research.
