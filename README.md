# gemma2_2b_finetune
This repository is part of my project for building an AI Legal Assistant for legal practitioners, faculties and students.
There are many blogs with code to inference and finetune models, from where i have taken the code to finetune my model but a specific issue I was facing was with "torch._dynamo()" package. It was preventing my code from because it does not support 4bit quantization inference. The inference and finetune code in this repository contains the correct code with no torch._dynamo() package issue.
