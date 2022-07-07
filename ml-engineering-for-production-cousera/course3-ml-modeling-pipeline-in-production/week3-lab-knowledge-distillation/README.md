# Lab: Knowledge Distillation
Welcome, in this lab, we are going to perform a model compression technique known as knowledge distillation in which a `student` model "learns" from a more complex model known as the `teacher`. In particular we will:
1. Define a `Distiller` class with the custom logic for the distillation process.
2. Train the `teacher` model which is a CNN that implements regularization via dropout.
3. Train a `student` model (a smaller version of the teacher without regularization) by using knowledge distillation.
4. Train another `student` model from scratch without distillation called `student_scratch`.
5. Compare the three students.

## Requirements
`tensorflow==2.8.2`