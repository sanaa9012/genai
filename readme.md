# GenAI Bootcamp

Traditional AI (old)    
Generative AI (new)

- Without data there is no AI

## Q:- How to build an AI system? 
###        -> Three ingredients:
    1. Data
    2. Identify the task 
        (ex. Regression, Classification)
    3. Choose an Algorithm 
        (ex. Linear Regression, Logistic Classification, KNN Regression/ Classification)

## Q:- Build an AI system which predicts/tells if the loan can be approved or rejected? 
(Pro tip: Breakdown the problem as follows)

-> used by(banks)

        ?(I/P) --> AI SYSTEM --> ?(O/P)

        Loan app --> AI SYSTEM --> Approved/Rejected 

- Needed in order to perform/solve the problem:
    1. Get data
    2. Identify the task (Tip: Look at the output. Numerical or categorical?)
        - here its categorical(discrete).
        - Output = numerical continuous value, Task= Regression. Output = categorical, Task = Classification)


    Loan App --> AI SYSTEM 1 (CLASSIFIER) --> Approved --> AI SYSTEM 2 (REGRESSION)
                                            --> or Rejected. 

Recipe:

    1. Training
    2. Testing/Evaluation (purpose: To check if the model is good or bad)
        -> Is the model good or bad? 
            - Good model is the model which best fits the data. 
            - Bad model is the model which overfit/underfit the data. (multiple strategies to fix)
    3. Inference


## Q:- Build an AI system which takes english text input and return kannada text output. (ex. Google Translator) 
    --> 
        I/P (English text) --> AI SYSTEM --> O/P (Kannada text) 

    Ingredients: 
        1. Data
            - English sentences -> Kannada Translations (a LOT)
        2. Output here is text, now classifying the task:
            - Language Modeling 
            - Auto Regressive LM task
        3. Algorithm? 
            - RNN (Recurrent Neural Network) is one of the most important algos to solve Auto Regressive LM tasks.
            - Transformer


### --> RAG is the solution of the limited knowledge.

### I/P (Prompt) --> GPT/Gemini (LLM --> generate text) --> O/P (text output)

#### Properties of any LLM: 
    
    1. LLMs are non-deterministic. 
        - can be controlled by:
            a. Temperature
            b. Top-p
    2. Limited Context Window
    3. They only generate text

## Prompt Design: 
1. Prompting Persona (give a personality)
2. Emulate user profile
3. Provide Specific instructions
4. Limiting response length
5. Output Structuring