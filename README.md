# EEG-Motor-Imagery-Classification-System

## Table of Contents
- [Introduction](##introduction)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
- [Usage Guide](#usage-guide)
  - [Data Input](#data-input)
- [Additional Information](#additional-information)
  - [Model Details](#model-details)
  - [Dataset](#dataset)


## Introduction

**DocumentSense** is an end-to-end **Document Intelligence System** capable of classifying raw documents (PDFs/images) into meaningful business categories using OCR, metadata extraction, text embeddings, and machine learning.

This system uses the **RVL-CDIP dataset**, one of the world's largest document-image datasets, and compresses the original **16 document classes into 5 practical enterprise level classes**.

### About Document Classification

Document classification is the process of automatically assigning labels to text based on its content. Using machine learning, the system learns patterns in language and categorizes documents quickly and accurately, making it easier to organize and manage large volumes of text.

![banner](https://i.pinimg.com/736x/89/92/f6/8992f6309f9b087144e8a6322ead2771.jpg)

### Purpose of the Project

The purpose of this project is to build an automated model that can classify documents into a few meaningful categories.

## Setup Instructions

(Ignore if you do not want to run the project locally)

### Prerequisites

Make sure you have the following installed:

- Python (>= 3.8)

- pip (Python package installer)

### Installation

Clone the repository:
  ```bash
    git clone https://github.com/aeonioo/DocumentSense.git
    cd DocumentSense
  ```

Create a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```


Install dependencies:

  ```bash
   pip install -r requirements.txt
   ```

## Usage Guide
### Data Input

1.Open the [web application](link) and navigate to the Document Classification section.

2.Upload a document file (image)

3.The system will extract text, preprocess it, and instantly display the predicted document category based on the trained model.

## Additional Information

### Model Details

- **Algorithm:** (model) (Accuracy≈xyz)
- **Purpose:** To automatically categorize documents into a reduced set of meaningful classes selected from the RVL-CDIP dataset.

### Dataset

This project uses a curated subset of the [RVL-CDIP dataset](link), a large collection of real scanned documents covering categories such as letters, forms, emails, invoices, and reports. From its original 16 classes, a smaller group of 4–5 practical categories is selected to create a focused and realistic document-classification task. Each document is processed through OCR to extract text, which is then cleaned and used to train the model. The dataset’s diversity and real-world structure make it ideal for building a robust document-intelligence system.

### Author

Shaunak Pathak
Feel free to reach out for questions or collaboration:
shaupathak41@gmail.com

