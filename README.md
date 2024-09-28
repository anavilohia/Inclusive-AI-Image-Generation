# AI-Image-Generation-Bias
COMS 6156 Spring 2024 Final Project
## Team Members
Jacqueline Gibson, Chia-Mei Liu, Anavi Lohia, Harpreet Multani, Nicole Neil

## Overview
As Artificial Intelligence (AI) becomes increasingly central to modern innovation, it brings remarkable opportunities and notable challenges, especially in creative domains like image generation. This research project focuses on identifying and understanding biases in AI-generated images, with an emphasis on inclusivity and fairness. We specifically analyze two popular models: OpenAI's DALL-E and Microsoft's Designer Image Creator. Our study targets biases related to Gender, Race, Disability, and Age, aiming to develop best practices for mitigating these biases in image generation technologies. 
Through this research, we aim to offer insights on gender, age, race, and disability biases in AI, aiding the creation of ethical AI. We believe it would benefit AI professionals and educators, guides creators on bias-minimized content, and increase awareness and inclusivity in digital media.

## Research Methodology
Our methodology involved a detailed analysis of two state-of-the-art image generation models: OpenAI’s DALL-E and Microsoft’s Designer Image Creator. The study was structured to investigate biases within four major categories: Gender, Race, Disability, and Age, with each category divided into various subtopics such as profession, family roles, and abilities.

### Data Collection Process
Initially, we crafted prompts for each subsection tailored to exploration of the image generation models’ default representations and inherent biases. These prompts were then refined through three iteration cycles, reaching a fourth and final prompt that aimed at specifically generating diverse and inclusive images. Every iteration of the prompts was run 10 times on each of the models to generate a
total of 640 images.

## Repository Structure
```
├── Data
| |__ Age Representation
| |__ Disability Representation
| |__ Gender Representation
| |__ Racial Representation
|── Bias_in_AI_Image_Generation.pdf
|── PromptList.md
|── BestPractice.md
└── README.md
```
* `Data`: Contains the generated images categorized by bias subtopics, includes age, diability, gender, and race.
* `PromptList.md`: A markdown file that lists all the prompts used throughout the study, including initial prompts and their iterative refinements.
* `BestPractices.md`: A markdown file documenting the recommended best practices for prompt design and image generation, derived from our research findings.
* `README.md`: Provides an overview of the project, its value, methodology, and instructions for navigating and utilizing the repository.
