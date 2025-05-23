# AI Directory Manager

An intelligent file organization system that uses AI to automatically categorize and organize files based on their content.

## Features

- Real-time file monitoring
- AI-powered file categorization using TF-IDF and K-means clustering
- Modern, responsive UI built with Tailwind CSS
- Interactive file visualization

## Setup

1. Install Python dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
python app.py
```

3. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Enter the path to the directory you want to analyze in the input field
2. Click "Analyze" to start the categorization process
3. View the categorized files in the grid layout below

## How it Works

The system uses the following AI techniques to organize files:

1. **Text Analysis**: Uses TF-IDF (Term Frequency-Inverse Document Frequency) to extract meaningful features from file contents
2. **Clustering**: Implements K-means clustering to group similar files together
3. **Real-time Monitoring**: Watches for new files and automatically categorizes them

## Technologies Used

- Python with Flask
- scikit-learn for AI/ML
- Tailwind CSS for styling
- Vue.js for frontend interactivity
- Watchdog for file system monitoring 