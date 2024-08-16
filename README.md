# Multiple Invoice Detection

## Project Description

This repository is dedicated to developing and evaluating advanced object detection models for the task of detecting multiple invoices within a single image. Conducted in collaboration with Sage, the goal is to enhance their Accounts Payable Automation (APA) system by integrating models capable of handling complex invoice layouts, overlapping invoices, and varied angles.

The project evaluates several state-of-the-art models, including YOLOv3, YOLOv8, YOLOv9, RetinaNet, Cascade R-CNN, and Dynamic R-CNN. These models are trained on a custom-built dataset, designed to reflect real-world invoice detection challenges. The performance of each model is rigorously tested using metrics like precision, recall, inference time, and memory usage to determine their suitability for business applications.

## File Structure

- **Colab Notebooks**: Contains Jupyter notebooks used for training different object detection models on Google Colab.
- **Backup Reference Notebooks**: Includes reference notebooks that support the main project, such as initial experiments or supplementary code.

## Usage
- Navigate to the Colab Notebooks folder.
- Open the notebook corresponding to the model you want to train.
- Follow the instructions in the notebook to train the model or load a pre-trained model from the Model Checkpoints folder.
- Evaluate the model's performance using the provided evaluation scripts.

## Authors and Contributors
Aljaz Mohamed - Lead Developer and Researcher
