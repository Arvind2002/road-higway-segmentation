# Road Safety from Satellite Images

## Overview
This project focuses on analyzing the safety standards of highways using raw satellite imagery and computer vision techniques. By leveraging advanced satellite datasets and deep learning models, this research aims to provide a cost-effective and accurate method for assessing and predicting road safety standards globally.

---

## Key Features
- **Satellite Image Collection**: Uses Google Earth Engine to acquire RGB satellite imagery from Landsat, Sentinel-2, and NAIP datasets.
- **Elevation Analysis**: Extracts elevation data to analyze road terrain and slope using the SRTM dataset.
- **Road Segmentation**: Implements a U-Net architecture to segment roadways from satellite images.
- **Road Width Calculation**: Detects road edges and calculates the width using OpenCV techniques and scaling factors derived from image metadata.
- **Future Scope**: Expands the framework for additional attributes like bridges, flyovers, and accident reports to develop comprehensive safety analysis models.

---

## Methodology
1. **Data Collection**:
   - Satellite images from Landsat, Sentinel-2, and NAIP datasets.
   - Elevation data from the Shuttle Radar Topography Mission (SRTM).
2. **Image Processing**:
   - Preprocessing raw satellite images.
   - Segmenting roadways using a fine-tuned U-Net model.
3. **Analysis**:
   - Calculating road widths using OpenCV’s edge detection.
   - Generating masks for visual representation of roads.
4. **Validation**:
   - Tested models using annotated datasets and validated results with real-world road data.

---

## Technologies Used
- **Programming Languages**: Python
- **Libraries/Frameworks**: 
  - OpenCV
  - TensorFlow/Keras (for U-Net)
  - Google Earth Engine API
- **Datasets**:
  - NAIP
  - Landsat
  - Sentinel-2
  - Massachusetts Road Dataset

---

## Results
- Achieved accurate road segmentation and width calculation for stretches of the I-90 interstate highway.
- Demonstrated the utility of satellite images for road safety analysis.
- Proposed a scalable framework to extend analysis to global road networks.
  
  <img width="296" alt="Screenshot 2024-12-22 at 12 24 53 PM" src="https://github.com/user-attachments/assets/b3fb913c-d407-4ba6-8013-7fbf4cd18f74" />
  <img width="296" alt="Screenshot 2024-12-22 at 12 25 04 PM" src="https://github.com/user-attachments/assets/69f31685-b6aa-40ea-838a-07f9880ca703" />
  <img width="296" alt="Screenshot 2024-12-22 at 12 25 17 PM" src="https://github.com/user-attachments/assets/5e0f7424-a2e1-4570-8dac-db38726e7d30" />


---

