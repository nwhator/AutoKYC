# AutoKYC

AutoKYC API is an AI-powered Know Your Customer (KYC) and Anti-Money Laundering (AML) verification system that automates identity verification for businesses, fintech, and compliance teams. It enables seamless ID extraction, face matching, and liveness detection to prevent fraud and ensure regulatory compliance.

## Key Features

- **OCR-based ID Extraction**: Uses Tesseract OCR / OpenCV to extract user details from official ID documents (Passports, NIN Slip, Driver’s License, etc.).
- **Face Verification**: Compares the extracted ID photo with a live selfie using DeepFace / FaceNet for high-accuracy matching.
- **Liveness Detection**: Ensures the user is physically present by detecting head movements and eye blinks using MediaPipe / dlib.
- **API Integration**: Easily integrates with financial platforms, fintech apps, and compliance systems.
- **Security & Compliance**: Follows best practices for GDPR, AML, and KYC regulations.
- **Cloud & On-Prem Deployment**: Can be deployed on AWS, Azure, GCP, or self-hosted.

## Tech Stack

- **Backend**: FastAPI / Flask (Python)
- **OCR**: Tesseract OCR / OpenCV
- **Face Recognition**: DeepFace / FaceNet / Dlib
- **Liveness Detection**: MediaPipe / OpenCV
- **Database**: PostgreSQL / MongoDB
- **Security**: JWT Authentication, Data Encryption
- **Cloud Services**: AWS Rekognition, Google Vision API (Optional)

## Getting Started

### Prerequisites

- Python 3.8+
- PostgreSQL or MongoDB
- Tesseract OCR
- OpenCV
- DeepFace / FaceNet / Dlib
- MediaPipe

### Installation

1. Clone the repository:
   ```bash
      git clone https://github.com/nwhator/AutoKYC.git
         cd AutoKYC
    ```