# DSC180A Methodology 4

Name: Zeyu Qi
Email: zeqi@ucsd.edu
Section: Evaluation Strategies for Next-Generation AI Systems
Mentor: Rajeev Chhajer, Ryan Lingo

1. **What is the most interesting topic covered in your domain this quarter?**
The most intersting topic covered in my domain this quarter is Chain of Density approach to text summarization. Unlike conventional summarization methods that try to compress content in a single step, Chain-of-Density builds summaries iteratively—starting with a brief outline and then progressively adding key facts and entities at each stage to increase information density without losing coherence.

2. **Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
Building on my Quarter 1 project on LLM-based summarization evaluation, I would like to extend my investigation to explore how summary density can be automatically optimized during generation, not just measured afterward. Specifically, I plan to design a multi-agent system where one model generates summaries and another provides real-time density feedback, guiding the generator to iteratively refine its output in the spirit of Chain of Density. 

3. **What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
In my Quarter 1 project, I focused primarily on implementing a baseline pipeline without much optimization. If I could redo it, I would introduce more systematic evaluation and ablation analysis — for example, quantifying how much each preprocessing or modeling step contributes to the final accuracy.

4. **What other techniques would you be interested in using in your project?**
Other techiques I am interested in using are vector-based semantic similarity and reinforcement learning. Vector-based semantic similarity, such as embeddings and cosine similarity, can be used to compare generated and reference summaries. I am also interested in exploring reinforcement learning, where feedback signals from human or model-based evaluators could be used to fine-tune a summarization model’s behavior.