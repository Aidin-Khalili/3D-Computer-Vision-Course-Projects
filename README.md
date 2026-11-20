# 3D Computer Vision — Course Projects

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white) ![Open3D](https://img.shields.io/badge/Open3D-1A1A1A) ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

My solutions to the assignments of the **3D Computer Vision** course at Amirkabir University of Technology (Tehran Polytechnic), M.Sc. in Artificial Intelligence and Robotics (Fall 2025).

Each folder contains the code (Jupyter notebooks / Python scripts) and the full written report with results and analysis.

## Assignments

| Assignment | Topics | Main tools | Files |
|---|---|---|---|
| [Camera Calibration](HW0-Camera-Calibration) | Intrinsic calibration from checkerboard images, reprojection error, lens distortion | OpenCV | [code](HW0-Camera-Calibration/code) · [report](HW0-Camera-Calibration/report.pdf) |
| [Single-View AR Cube](HW1-Single-View-AR-Cube) | Vanishing points (least squares and RANSAC), horizon line, homography, camera pose, rendering a virtual 3D cube | OpenCV, NumPy | [code](HW1-Single-View-AR-Cube/code) · [report](HW1-Single-View-AR-Cube/report.pdf) |
| [Two-View & Epipolar Geometry](HW2-Two-View-Epipolar-Geometry) | Feature matching, fundamental/essential matrix, epipolar lines, rectification, stereo disparity | OpenCV, NumPy | [code](HW2-Two-View-Epipolar-Geometry/code) · [report](HW2-Two-View-Epipolar-Geometry/report.pdf) |
| [Point Cloud Registration & SLAM Basics](HW3-Point-Cloud-Registration-and-SLAM) | ICP registration, building a unified map from LiDAR scans, trajectory evaluation on KITTI | Open3D, Plotly | [code](HW3-Point-Cloud-Registration-and-SLAM/code) · [report](HW3-Point-Cloud-Registration-and-SLAM/report.pdf) |

## How to run

```bash
git clone https://github.com/Aidin-Khalili/3D-Computer-Vision-Course-Projects.git
cd 3D-Computer-Vision-Course-Projects
pip install numpy opencv-python matplotlib open3d plotly ipywidgets
jupyter notebook
```

Most notebooks were run on Google Colab or locally; paths to data files may need to be changed to your own.

> The KITTI sample and the Middlebury stereo images are not included; download them from their official websites.

## Notes

- Reports are written in Persian.
- Large datasets, model weights and course-provided input files are not included. Some figures in the notebooks were compressed or removed to keep the repository small; the full set is in each `report.pdf`.

## License

Released under the [MIT License](LICENSE): you are free to use, modify and share this code with attribution.

## Author

**Aidin Khalili** — [GitHub](https://github.com/Aidin-Khalili)
