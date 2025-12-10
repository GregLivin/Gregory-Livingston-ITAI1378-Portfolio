VisionTalk: Image Captioning Program
1. Problem Statement

Image captioning is the task of generating natural-language descriptions for images.
This project demonstrates how modern AI models can connect vision (images) with language (text) using a Vision-Language Model (VLM).

2. Approach

I built a captioning system using the BLIP Vision-Language Model from Hugging Face.
The notebook loads the model, processes an input image, and generates a caption in natural language.

This project connects topics learned across modules, including:

Image processing

Neural networks

Convolutional networks

Transformers

Vision-language systems

3. Technologies Used

Python

PyTorch

Hugging Face Transformers

BLIP Model

PIL / OpenCV

Google Colab

Jupyter Notebook

4. Results

The model successfully generated captions such as:

"a dog sitting on a couch"

"a car parked on the street"

Output examples and screenshots are stored in the results/ folder.

5. What I Learned

Through this project, I gained skills in:

Preprocessing images for AI models

Loading and running transformer-based models

Understanding how multimodal AI works

Connecting vision and language tasks

Organizing an AI project into reusable code and documentation

6. How to Run the Notebook
Option A — Run in Google Colab

Open the notebook: VisionTalk_Image_Captioning.ipynb

Upload an image

Run all cells

The model generates a caption

Option B — Run Locally

Install dependencies:

pip install torch torchvision transformers pillow


Open the notebook in Jupyter

Run all cells

7. Folder Structure
VisionTalk-Image-Captioning/
│── VisionTalk_Image_Captioning.ipynb
│── README.md
└── results/
    └── .gitkeep

8. Dataset

No dataset required.
The model captions any image provided by the user.
