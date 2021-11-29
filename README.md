# Boilerplate-code-generation

[Research paper](https://drive.google.com/file/d/1LCp-N7qHynYUlUcw6D3CwYL6zVxXaZEC/view?usp=sharing)

Programmers are required to write a
significant amount of repetitive code to accomplish minor
functionalities while writing a computer program. 

The purpose of this study is to
investigate a way to generate directly usable Python code to
address variable declarations and input statements from
given input constraints provided in problem statements.


## Installation and Setup Instructions

### Install Dependencies:

```pip3 install -r requirements.txt```

### Setup:
- Clone this repository

```git clone https://github.com/compspandan/Boilerplate-code-generation.git```  

Best Model: finalModel.ipynb

## Reflection

- This study investigates
the possibility of using a simple Seq2Seq encoder decoder
model, involving Long Short Term Memory (LSTM)
networks, to convert input parameters in a human language
i.e. English to Python code.
-  This work successfully generates
Python code for input statements based on the input
parameters specified in the Beginner/ Easy level competitive
programming problems.
-  This study can be further used as a
stepping stone for future work aimed at auto-generation of
code for logical parts of a computer program.

This was a 6 month long research project built as a part of UE19CS208E(Mini-project) course.