DOWNLOAD THE DATASET FROM HERE:- https://drive.google.com/file/d/1Yq-mE0jgmZLF4_Fp4a-H0KlMljQjB8Ca/view?usp=sharing
EDIT THE "project_path = 'E:\project sleep analysis\sleep-edf-database-expanded-1.0.0\sleep-edf-database-expanded-1.0.0\combined'" IN THE CODE BEORE TESTING.
*RUN THE CODE IN GOOGLE COLAB ONLY.. NO GPU REQUIRED

This notebook focuses on reading, preprocessing, and analyzing EEG and related biosignals stored in EDF (European Data Format), commonly used in sleep studies. It sets the foundation for building machine learning models to classify sleep stages using raw physiological data.

📌 Core Highlights
Custom EDF Reader: Implements an efficient EDF file parser using h5py, numpy, and other utilities for structured signal extraction.

Signal Processing Pipeline: Defines constants like WINDOW_SIZE and classes like EDFEndOfData to manage signal windowing and flow control during data reading.

Logging and Annotation Handling: Integrates structured logging and recognizes EDF annotation channels (e.g., sleep events).

Model Development Framework: Includes structured placeholders for defining and training models for sleep stage classification.

Project-Specific Design: Organized for a final-year or capstone project in biomedical or data science domains.

🛠️ Libraries Used
Python standard libraries (logging, re, operator, etc.)

Scientific computing stack (numpy, h5py)

Custom class-based structure for EDF parsing
