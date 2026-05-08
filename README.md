# SmartFit Garment Analysis System

AI-powered garment fit analysis system using 3D mesh processing, body measurement sanitization, and intelligent garment recommendation algorithms for fashion technology and virtual fitting applications.

---
# Question 1: Waist Circumference Visualization

## Overview

- Extracts waist circumference from a 3D human body mesh using mesh slicing and contour analysis techniques  
- Visualizes the waist contour on the 3D body mesh  
- Computes accurate geometric body measurements from `.obj` mesh models  

## Working

- Upload the `.obj` body mesh file  
- Load mesh using the `trimesh` library  
- Apply rotation transformation for proper body alignment  
- Create a horizontal slicing plane at waist level  
- Intersect slicing plane with the mesh  
- Extract contour curves from the sliced section  
- Detect the largest contour as the waist boundary  
- Calculate circumference using contour distances  
- Visualize the waist contour on the 3D mesh  

## Technologies Used

- Python  
- Trimesh  
- NumPy  
- Matplotlib  
- Google Colab / Jupyter Notebook  

## Output

- Waist circumference value generated  
- Waist contour highlighted on the 3D mesh  
- Waist slicing height identified  
- 3D waist visualization created  
- Output image saved as `waist_slice.png`  
---
# Question 2: Measurement Normalization & Outlier Detection Engine

## Overview

- Validates, sanitizes, and normalizes body measurements before garment fit analysis  
- Detects abnormal body proportions and inconsistent values  
- Generates clean and standardized body measurement data  

## Working

- Accept body measurements such as height, chest, waist, and hip  
- Convert all measurements into standard units (centimeters)  
- Validate measurement inputs and remove invalid values  
- Detect abnormal body proportions using ratio-based checks  
- Generate derived measurements such as arm length  
- Produce clean and normalized measurement data  

## Technologies Used

- Python  
- NumPy  
- Object-Oriented Programming (OOP)  
- Exception Handling  

## Output

- Normalized body measurements generated  
- Invalid or inconsistent values detected  
- Outlier measurements identified  
- Derived measurements calculated  
- Clean and standardized dataset produced  

---
# Question 3: Best-Fit Multi-Constraint Search Algorithm

## Overview

- Recommends best-fit garments using weighted scoring and fit confidence analysis  
- Identifies top suitable garments based on user body measurements  
- Uses intelligent ranking logic for garment recommendation  

## Working

- Collect and normalize user body measurements  
- Compare measurements with garment database values  
- Assign weights to chest, waist, and hip measurements  
- Apply penalties for tight or loose garment fitting  
- Compute fit confidence scores for garments  
- Rank garments using weighted scoring logic  
- Display Top 3 garment recommendations  

## Technologies Used

- Python  
- NumPy  
- Heapq  
- Weighted Scoring Algorithms  
- Lists & Dictionaries  

## Output

- Top 3 garment recommendations generated  
- Garment IDs displayed  
- Fit confidence scores calculated  
- Garments ranked based on fitting accuracy  
- Best-fit clothing suggestions identified  
---
# How to Run

- Open each `.ipynb` notebook in Google Colab or Jupyter Notebook  
- Install the required Python libraries  
- Run the notebook cells sequentially  
- View outputs such as waist visualization, normalized measurements, and garment recommendations

---

# Applications

- Virtual fitting rooms  
- Smart fashion recommendation systems  
- AI-powered apparel platforms  
- Digital tailoring solutions  
- Personalized shopping systems  
