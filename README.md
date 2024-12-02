# Bizcardify_Doc_Scanner_App_OCR_NER_web_App

Welcome to the **Business Card Reader Web App** repository! This project focuses on creating an automated system to extract and classify information from business cards using advanced techniques in image processing and natural language processing.

---

## 🛠️ Features

- **Text Extraction**: Utilizes Pytesseract (OCR) for extracting text from business card images.  
- **Named Entity Recognition (NER)**: Identifies key entities such as names, designations, organizations, phone numbers, emails, and websites.  
- **Document Scanner**: Processes images to detect, crop, and transform business cards using OpenCV.  
- **Web App Interface**: Built using Flask, with an interactive JavaScript canvas for manual adjustments.  
- **Visualization**: Displays extracted entities and bounding boxes for better understanding.  

---

## 🧰 Technologies Used

- **Programming Language**: Python  
- **Libraries/Frameworks**: 
  - Pytesseract (OCR)
  - Spacy (NER)
  - OpenCV (Image Processing)
  - Flask (Web Application Development)
  - Pandas (Data Handling)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or above  
- Necessary libraries (install using `requirements.txt`)  

### Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/business-card-reader.git
   ```
2. Navigate to the project directory:  
   ```bash
   cd business-card-reader
   ```
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

---

## 🏃‍♂️ Usage

### Local Deployment

1. Start the Flask server:  
   ```bash
   python app.py
   ```
2. Open your browser and navigate to:  
   ```
   http://127.0.0.1:5000
   ```
3. Upload a business card image and process it to extract entities.  

### Core Functionalities

1. **Document Scanning**: Automatically detects and crops the business card region.  
2. **Text Extraction**: Extracts text from the cropped image.  
3. **Entity Recognition**: Uses the trained NER model to identify and classify entities.  
4. **Interactive Adjustments**: Adjust bounding box coordinates via a JavaScript canvas for precision.  
5. **Entity Visualization**: View extracted entities with their bounding boxes on the card.  

---

## 📊 Applications

- **Contact Management**: Streamlines the digitization of business cards.  
- **CRM Integration**: Automates the entry of business card information into CRM systems.  
- **Data Digitization**: Efficiently manages bulk business card processing.  

---

## 🤝 Contribution

Contributions are welcome! To contribute:  

1. Fork the repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:  
   ```bash
   git commit -m "Add feature"
   ```
4. Push to your forked repository and submit a pull request.  

---

## 🌟 Acknowledgments

- The creators of **Pytesseract**, **Spacy**, **OpenCV**, and **Flask** for their exceptional tools.  
- The **Data Science Anywhere** and **Visionview Team** for their vision and development efforts.  

--- 

