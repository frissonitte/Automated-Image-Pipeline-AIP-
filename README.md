Automated Image Pipeline (AIP)

AIP is a prototype system that automates a series of image‑processing tasks within a single, centrally managed pipeline.
It combines software‑automation logic with computer‑vision workflows, allowing different preprocessing scripts to be executed, logged, and optimized in one environment.

Project Overview

Modern data‑driven projects often involve scattered preprocessing scripts and manual task execution.
This project aims to design a unified automation manager for these image‑based data flows.
The current implementation focuses on medical microscopy images using the RBC Raabin‑WBC Dataset.

Core Features (so far):

    Preprocessing pipeline for color microscope images
    Operations: noise removal (Gaussian Blur), grayscale conversion, and edge detection (Canny)
    Automatic iteration through entire image folders
    Saving intermediate steps (gray, edges) for analysis
    Modular structure ready for task management integration

Tech Stack
Category	Tools
Language	Python (3.10 +)
Core Libraries	OpenCV, NumPy, Matplotlib
Environment	Jupyter Notebook / VS Code
Version Control	Git + GitHub

Roadmap (next steps)

    [ ] Integrate contrast enhancement (CLAHE) and morphological filters.
    [ ] Add simple logging of task results and parameters.
    [ ] Design a basic task manager to define and run pipelines automatically.
    [ ] Optional: Flask / Streamlit UI for execution and monitoring.

Why it matters

This project bridges data engineering and computer vision, showing how process automation principles can streamline experimental workflows in research environments—especially those dealing with image‐based datasets.

Project Status — Learning Stage

    This is a learning‑oriented project to explore image processing and automation pipeline design.
    The system structure is kept modular for future extensions and AI integration.
