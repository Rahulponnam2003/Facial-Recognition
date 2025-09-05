# Face Recognition using PCA (Eigenfaces)

## 📌 Project Overview  
This project implements a **face recognition pipeline using Principal Component Analysis (PCA)**, also known as the **Eigenfaces method**. The goal is to reduce the dimensionality of facial image data while retaining important identity features, enabling efficient **face reconstruction and recognition**.  

---

## 🔑 Key Features  
- Processed a dataset of **~2,400 facial images**.  
- Reduced dimensionality by **95%** using PCA while preserving identity information.  
- Achieved **high-quality face reconstruction** with as few as **100 eigenfaces**.  
- Demonstrated **clear separation of individuals** in low-dimensional PCA feature space (PC5 vs. PC6).  
- Built a structured pipeline from **data preprocessing** to **recognition**.  

---

## 🛠️ Tech Stack  
- **Python**: NumPy, Matplotlib, SciPy  
- **Machine Learning**: Principal Component Analysis (PCA), Singular Value Decomposition (SVD)  
- **Data**: Pre-collected facial dataset (`allFaces.mat`)  

---

## 🔄 Project Pipeline  
The workflow followed in this project:  

1. **Dataset (~2400 Faces)** → Load and structure the dataset  
2. **Preprocessing & Visualization** → Normalize and visualize sample faces  
3. **Mean Face Computation** → Compute the average face for alignment  
4. **PCA / Eigenfaces Extraction** → Apply PCA (via SVD) to extract eigenfaces  
5. **Reconstruction** → Rebuild test images with varying numbers of eigenfaces (25, 50, 100, …)  
6. **Recognition & Classification** → Project test individuals into PCA space for recognition  


