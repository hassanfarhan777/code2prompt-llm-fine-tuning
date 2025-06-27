# Code2Prompt Dataset Curation for LLM Fine-Tuning

## Overview

**Code2Prompt** is a curated resource designed to help researchers and practitioners prepare high-quality datasets for Large Language Model (LLM) fine-tuning, especially for code-related tasks. This repository demonstrates best practices in dataset extraction, cleaning, organization, and project hygiene, with a focus on supporting downstream LLM fine-tuning efforts.

## Purpose

- **Fine-Tuning Support:** The entire workflow is designed to help others build datasets suitable for LLM fine-tuning, enabling more effective model adaptation for coding and automation tasks.
- **Reproducible Data Engineering:** All scripts, instructions, and project protocols are aimed at making dataset curation easy to replicate, adapt, or extend for similar projects.

## Key Strengths

- **Comprehensive Dataset Curation**
  - Extracts and organizes code data from open datasets (e.g., [3b1b/videos](https://github.com/3b1b/videos)), ready for use in LLM fine-tuning pipelines.
  - Modular and well-documented notebooks for scraping, cleaning, and structuring data[1][8].
- **Best Practices in Data Management**
  - **Large raw datasets are never committed to the repository**; instead, clear instructions are provided to source them externally, keeping the repo lightweight and compliant with GitHub guidelines.
  - `.gitignore` is configured to prevent accidental tracking of large or sensitive files.
- **Project Hygiene and Security**
  - Careful attention to secret management: any sensitive files (like API keys) are scrubbed from both the working directory and git history.
  - All data-related scripts are safe for open-source use and collaboration.
- **Documentation-Driven Approach**
  - Every step is clearly explained so users can reproduce the dataset creation process from scratch with minimal friction[4][8].

## Improvements Over Typical Dataset Projects

- **Reproducibility:** Anyone can reconstruct the dataset by following provided scripts and instructions—ideal for research and collaboration.
- **Security:** Demonstrates robust workflows for removing secrets and handling large files, which are common pitfalls in open-source data projects.
- **Fine-Tuning Ready:** All data preparation is tailored for downstream LLM fine-tuning tasks—even if actual model training is not included in this repo.

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/hassanfarhan777/code2prompt-llm-fine-tuning.git

2. **Install Dependencies**
  
   ```bash
   pip install -r requirements.txt


Obtain the 3b1b Dataset

This project relies on code data from 3b1b/videos.
Please clone the dataset repository separately: 

   ```bash
   git clone https://github.com/3b1b/videos.git 
