# Evaluating Open Source Models for Student Competence Analysis – Python Task 3

This project explores the evaluation of open-source AI models for analyzing student competence in programming and educational tasks. The focus is on identifying, testing, and reasoning about models such as CodeBERT (Hugging Face), EduNLP, and Large Language Models (LLMs), and assessing their applicability in education-related contexts. The work involves preparing a research plan, evaluating model suitability, and presenting clear reasoning for model selection. <br>

## Table of Contents
1. Reaserch Plan
2. Reasoning and Decision Making
3. Models and Tools Considered
4. Setup Instructions
5. References
6. Conclusion

## Research Plan
### Identifying and Evaluating Models
Our approach begins with exploring open-source models suitable for competence analysis in the education domain. We consider CodeBERT (Hugging Face), which is a transformer-based model trained on natural and programming languages, making it highly effective for analyzing student code submissions, detecting errors, and evaluating coding patterns. Alongside, we examine EduNLP, a specialized toolkit designed for processing and representing educational text and assessment data, enabling meaningful analysis of student learning content and exam questions. Finally, we include Large Language Models (LLMs), such as GPT-based architectures, for their ability to generalize across tasks and provide natural language-based insights into student performance. <br>
### Testing, Validation, and Decision Process
To validate these models, we would design small-scale tests simulating student data inputs such as short programming exercises, quiz responses, and written answers. CodeBERT would be tested for coding-related tasks like classification and similarity detection, while EduNLP would be validated for its ability to process and structure educational resources. LLMs would be evaluated for their adaptability in providing contextual explanations and predictions about student learning outcomes. The decision-making process prioritizes accuracy, interpretability, and domain relevance, ensuring that the chosen models are not only technically strong but also educationally meaningful for analyzing student competence. <br>

## Reasoning 
### 1. What makes a model suitable for high-level competence analysis?
A model becomes suitable for high-level competence analysis when it can go beyond surface-level correctness and capture deeper understanding. For example, it should not only check if a student’s code compiles but also whether the logic reflects real problem-solving skills. Similarly, for text-based answers, it should understand context, structure, and reasoning. Models like CodeBERT, EduNLP, and LLMs fit here because they evaluate both technical accuracy and conceptual clarity. <br>

### 2. How would you test whether a model generates meaningful prompts?
To test prompt quality, we would design sample tasks (like coding exercises, MCQs, or descriptive questions) and evaluate the generated prompts against criteria such as clarity, relevance, and alignment with learning objectives. Human evaluators (teachers) could cross-check whether prompts assess actual competence instead of rote memorization. Additionally, automated checks, such as difficulty calibration or diversity of generated prompts, would help validate usefulness. <br>

### 3. What trade-offs might exist between accuracy, interpretability, and cost?
High accuracy often comes with models that are computationally expensive (like large LLMs), making them less cost-effective. On the other hand, smaller models like EduNLP may be more efficient but less accurate in complex reasoning tasks. Interpretability also adds complexity—models that provide transparent reasoning may sacrifice speed or require additional layers of processing. Hence, balancing accuracy, interpretability, and cost is essential depending on the context of deployment. <br>

### 4. Why did you choose the model you evaluated, and what are its strengths or limitations?
We chose CodeBERT, EduNLP, and LLMs because together they cover complementary aspects of competence evaluation. CodeBERT is strong in programming-related analysis but weak in textual interpretation. EduNLP specializes in educational tasks but lacks versatility in unstructured responses. LLMs are powerful in reasoning and adaptability but costly and sometimes inconsistent. By combining them, we aim to leverage their strengths while reducing individual limitations. <br> 

## Setup Instructions 
To explore and replicate the research process, follow these steps: <br>
### 1. Clone the Repository
~~~
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
~~~
### 2. Create and Activate a Virtual Environment
~~~
python -m venv venv
source venv/bin/activate    # On macOS/Linux
venv\Scripts\activate       # On Windows
~~~
### 3. Install Dependencies
Install the required Python libraries: <br>
~~~
pip install -r requirements.txt
~~~
If you are not including a requirements.txt, you can mention the key libraries directly, e.g. transformers, torch, edunlp, etc. <br>
~~~
pip install transformers torch edunlp
~~~
### 4. Access Model References
* https://huggingface.co/microsoft/codebert-base via HuggingFace.<br>
* https://edunlp.readthedocs.io/en/latest/ documentation for educational NLP preprocessing.<br>
* LLMs can be accessed through platforms like https://huggingface.co/models or APIs. <br>
### 5. Run Experiments
Since this repository is primarily research-focused, experiments are designed conceptually. You can adapt the provided model references and reasoning to your own datasets or evaluation tasks.

## References
1. CodeBERT: A Pre-Trained Model for Programming and Natural Languages <br>
Feng, Z., Guo, D., Tang, D., Duan, N., Feng, X., Gong, M., … Zhou, M. (2020). <br>
https://arxiv.org/abs/2002.08155
2. CodeBERT Model (Hugging Face) <br>
Microsoft. CodeBERT-base.<br>
https://huggingface.co/microsoft/codebert-base
3. EduNLP Documentation<br>
USTC. EduNLP: Education-Oriented NLP Toolkit.<br>
https://edunlp.readthedocs.io/en/latest/
4. EduNLP: A Python Library for Text Processing in Educational NLP <br>
EduNLP Documentation.<br>
https://github.com/bigdata-ustc/EduNLP
5. Large Language Models (LLMs): GPT-3 and Beyond <br>
Brown, T. et al. (2020). Language Models are Few-Shot Learners. <br>
https://arxiv.org/abs/2303.18223

## Conclusion
This repository is intended as a research-focused exploration of models like CodeBERT, EduNLP, and large language models for student competence analysis.  
It is not a production-ready implementation, but rather a structured plan and reasoning framework that can be extended or adapted by others.  
Future contributors are welcome to build on this foundation to design experiments, add datasets, or integrate new evaluation methods.

*This README marks the completion of the research submission. All steps, reasoning, and references have been documented to ensure clarity and reproducibility.*

## Candidate Details
**Name:** Poorva Jawale <br>
**Program:** Second Year Engineering, Computer Engineering <br>
**Institution:** Vidyavardhini's College of Engineering and Technology, Vasai <br>
