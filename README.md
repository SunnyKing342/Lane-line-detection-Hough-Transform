# Lane Line Detection Using Otsu Thresholding & Fast Hough Transform

This repository contains the implementation of a lane detection approach for autonomous vehicles, based on the method proposed in the paper:
**Lane line detection and object scene segmentation using Otsu thresholding and the fast Hough transform for intelligent vehicles in complex road conditions**.

---

## 📌 Project Overview
This work proposes a fast and accurate lane detection pipeline using:
- **Otsu thresholding** for adaptive binarization
- **Improved Canny edge detection** with Sobel gradients and Gaussian blur
- **Fast Hough Transform (FHT)** for line detection
- **Least-squares fitting** for lane tracking

The system is designed to meet both accuracy and real-time processing requirements for lightweight automatic driving systems, making it suitable for deployment in intelligent vehicles under complex road conditions.

---

## 🔄 Pipeline Workflow
The algorithm follows this sequence of operations:
<img width="3764" height="2580" alt="image" src="https://github.com/user-attachments/assets/a0409156-63d3-4c4e-8f77-58b1acc71172" />


---

## ✨ Key Features
✅ Gaussian blur to reduce image noise and improve edge detection  
✅ Sobel operator for gradient-based edge enhancement  
✅ Otsu thresholding for adaptive segmentation  
✅ Region of Interest (ROI) extraction to focus on road lanes  
✅ Fast Hough Transform to detect lane lines in polar coordinates  
✅ Least-squares fitting for stable lane tracking  
✅ High accuracy and reasoning speed for real-time applications  

---

## 📄 Citation
If you use this implementation in your research, please cite the original paper:

```bibtex
@article{javeed2023lane,
  title={Lane line detection and object scene segmentation using Otsu thresholding and the fast Hough transform for intelligent vehicles in complex road conditions},
  author={Javeed, Muhammad Awais and Ghaffar, Muhammad Arslan and Ashraf, Muhammad Awais and Zubair, Nimra and Metwally, Ahmed Sayed M and Tag-Eldin, Elsayed M and Bocchetta, Patrizia and Javed, Muhammad Sufyan and Jiang, Xingfang},
  journal={Electronics},
  volume={12},
  number={5},
  pages={1079},
  year={2023},
  publisher={MDPI}
}
```

---

## 🚀 Usage (Placeholder)

1. Install dependencies:
```bash
pip install -r requirements.txt
```
2. Run the lane detection pipeline:
```bash
python lane_detection.py --input data/road_video.mp4
```

---

## 📝 License
This project is based on the research published in Electronics (MDPI). Please refer to the original paper’s license for usage rights.
```
