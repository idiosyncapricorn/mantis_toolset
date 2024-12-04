M4NTIS: Audio Processing Application (Python/Flask/Docker)

Overview

M4NTIS is a comprehensive audio processing application currently in development. It combines Python, Flask, and Docker to deliver tools for sampling rate customization, multi-channel audio processing, audio spectrum learning, anomaly detection, and graphic analysis. A built-in honeypot feature enhances security by detecting unauthorized access.

Features

	•	Audio Processing: Multi-channel handling, customizable sampling rates, and block-by-block processing.
	•	Audio Spectrum Learning: Tools to analyze and learn patterns in audio data.
	•	Anomaly Detection: Real-time detection of irregularities in audio signals.
	•	Graphic Analysis: Visual representations of audio data and spectrum plots.
	•	Security Honeypot: Logs unauthorized access attempts to enhance security.

Installation

Clone the Repository

git clone https://github.com/yourusername/m4ntis.git
cd m4ntis

Build and Run with Docker

	1.	Build the Docker image:

docker build -t m4ntis-app .


	2.	Run the container:

docker run -p 8000:8000 m4ntis-app


	3.	Access the app at http://localhost:8000.

Notes

	•	In Development: All features are experimental and subject to change.
	•	Dependencies: All Python dependencies are listed in requirements.
