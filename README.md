# Learning to Steer: Optimization Framework for LLM Alignment

This repository contains the foundational research proposal for an optimization-based framework to extract steering vectors in Large Language Models. 

### Abstract
Steering vectors offer a promising way to control LLMs at inference time without modifying their weights. However, existing methods often degrade general model capabilities (e.g., reasoning, fluency) while enforcing alignment. This project treats steering vector extraction as a constrained optimization problem. By minimizing layer-wise Sliced Wasserstein Distance on benign distributions while maximizing behavioral rewards, we aim to identify orthogonal steering directions that align behavior without catastrophic forgetting.

**[Full research proposal](Learning_to_Steer_Proposal.pdf)**.
