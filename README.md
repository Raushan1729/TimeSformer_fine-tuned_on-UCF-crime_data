# TimeSformer_fine-tuned_on_UCF_crime_data


## Overview
This project utilizes the TimeSformer model for video analysis, specifically focused on detecting anomalies in crime-related videos. The notebook processes video data and extracts key features to identify suspicious activities efficiently.

## Features
- **Video Frame Extraction**: Extracts frames from the input video for processing.
- **TimeSformer Model Processing**: Uses a transformer-based architecture to analyze video frames.
- **Anomaly Detection**: Identifies unusual patterns within video sequences.


## Why Two Codes for One Purpose?
The code may contain multiple implementations of certain functionalities to:
1. **Optimize Performance**: Different methods allow testing variations to determine the best approach.
2. **Ensure Accuracy**: Using multiple techniques helps validate results and improve reliability.
3. **Flexibility**: Provides alternative implementations for diverse datasets or computational constraints.
4. **Model Comparison**: Enables evaluation of multiple processing pipelines to identify the most effective.

## Installation
To run this project, install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Prepare the dataset with crime-related video files.
2. Run the `Ucf_crime_TimeSformer.ipynb` notebook.
3. Review the model output for detected anomalies.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Acknowledgments
- **TimeSformer Model**: Leveraging state-of-the-art video transformer techniques.
- **Dataset**: UCF Crime dataset used for training and evaluation.
- **Kaggle data**: chmod 600 ~/.kaggle/kaggle.json
