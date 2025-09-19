# 🖼️ Image Compression with K-Means (From Scratch)

This project demonstrates **image compression using K-Means clustering**, fully implemented **from scratch in Python** (without using scikit-learn's KMeans).  
By reducing the number of unique colors in an image, we achieve compression while preserving visual quality.  

---

## 🚀 Features
- Implemented **K-Means clustering algorithm from scratch**  
- Compress images by reducing thousands of colors to **K representative colors**  
- Works with **JPG and PNG images**  
- Simple preprocessing pipeline for handling different image formats  

---

## 📂 Project Workflow
1. Load and preprocess the image  
2. Treat each pixel as a point in 3D RGB space  
3. Run **K-Means clustering** to find `K` centroids (colors)  
4. Replace each pixel with its nearest centroid color  
5. Reconstruct and display the compressed image  

---

## 🖼️ Example
Original Image → Compressed Image (K = 16)

---

## 🛠️ Tech Stack
- Python 🐍  
- NumPy  
- Matplotlib  

---

## 🏷️ Topics
`machine-learning` `k-means` `image-compression` `clustering` `python`  

---

cd image-compression-kmeans
python main.py
