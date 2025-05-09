# Exploring-chain-of-thought-reasoning-in-LLMs

Abstract
The exploration undertaken analyzes 4 aspects of CoT reasoning - Determinism, Faithfulness, Reasoning patterns and Steering capabilities. This exploration was performed on the smaller distill models with the relatively simple GSM8K datasets involving simple reasoning. However the slew of promising trends observed even in the distill with relatively simple datasets, is exciting. This could possibly serve as a brief study which can be further built upon using larger more complex datasets. The brief key findings from each aspect analyzed 
1. Determinism- CoT reasoning is found to be reliably deterministic for simple reasoning problems with only slight variation in reasoning steps.
2. Faithfulness- CoT reasoning was found to be the medium by which even the models perform their final computation with post hoc reasoning seeming less likely. However more statistically significant studies on larger datasets may be required to establish this trend
![image](https://github.com/user-attachments/assets/9905aba9-926e-4b03-8604-16500c8a1fc1)

3. Reasoning patterns- Even within sequential reasoning, the impact of different types of problems and reasoning patterns are observed on model internals with clustering of reasoning patterns being a feasible exercise. If performed over larger datasets this may be significant to understand reasoning steps just from model computation metrics like- Model confidence(Log_softmax(logits)) and backtracking ratio
![image](https://github.com/user-attachments/assets/ef4c4eaa-adfc-46e0-8915-73ac27a0b987)

4. Steering capabilities- Steering vectors generalize fairly well, with vectors being trained on smaller simpler step wise data serving as useful interventions on larger more complex reasoning CoTs.
