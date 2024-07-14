# Intel-unnati
Running GenAI on Intel AI Laptops This repository contains documentation and code for running Generative AI models on Intel AI laptops for the Intel Unnati Industrial Training program. It focuses on LLM inference on CPU and fine-tuning with Intel OpenVINO, using the Intel Edge Developer Cloud due to local system constraints.
Running GenAI on Intel AI Laptops
This repository contains the documentation and code for running Generative AI (GenAI) models on Intel AI laptops as part of the Intel Unnati Industrial Training program. The focus of this project is to perform language model (LLM) inference on CPU and fine-tuning LLM models using Intel OpenVINO. The experiments were conducted on the Intel Edge Developer Cloud due to compatibility and hardware constraints on local systems.

Project Overview
The project aims to demonstrate the performance and efficiency improvements in running GenAI models on Intel AI laptops using OpenVINO optimizations. The experiments involve:

Environment Setup: Configuring the necessary tools and platforms.
Model Selection and Configuration: Choosing appropriate models for inference and fine-tuning.
Model Optimization with OpenVINO: Converting models to FP16, INT8, and INT4 formats for enhanced performance.
Inference Process: Executing model inference tasks and measuring performance.
Fine-Tuning Process: Training models on specific datasets and exporting optimized versions for deployment.

Contents
Documentation

report.tex: The LaTeX source file documenting the technical approach, issues faced, results, and future directions of the project.
report.pdf: The compiled PDF document of the report.
Code
inference.py: Script for running inference using the neural-chat-7b-v3-1 model.
fine_tuning.py: Script for fine-tuning the Meta-LLama-2-7b-hf model using Hugging Face's Trainer API.
openvino_optimization.py: Script for converting and optimizing models with OpenVINO.

Figures
Screenshot 2024-07-14 at 6.36.13 PM.png: Image illustrating the inference process.
Screenshot 2024-07-14 at 8.11.40 PM.png: Image illustrating the fine-tuning process.

Results
Inference Performance (neural-chat-7b-v3-1)
High accuracy with efficient response times.
Fine-Tuning Performance (Meta-LLama-2-7b-hf)
Inference time: 0.8281 seconds
Throughput: 1.21 sequences per second

Benefits of OpenVINO Integration
Performance Enhancement: Improved speed and efficiency with optimized execution.
Resource Efficiency: Better CPU utilization and scalability across Intel hardware.
Cost-Effectiveness: Leveraging existing hardware resources for broad deployment.

Future Directions
Further optimization and fine-tuning techniques.
Application development for real-world use cases.
Comprehensive benchmarking across different models and hardware configurations.

Video Link
Demonstration Video (Placeholder for actual link)

Contribution
This project was completed as part of the Intel Unnati Industrial Training program. Contributions and feedback are welcome to further enhance the performance and applicability of GenAI models on Intel hardware.

