# ECG Signal Viewer

**A Tkinter-based ECG signal viewer designed to display, filter, and annotate ECG signals from multiple leads.**

---

## 📋 Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Dataset](#dataset)
- [Troubleshooting](#troubleshooting)
- [Future Improvements](#future-improvements)

---

## 🌟 Features

- **Multi-Lead ECG Display**: Visualizes ECG signals from 12 leads, with labeled axes and gridlines for enhanced readability.
- **Filtering Options**: Includes low-pass and notch filters to remove noise and improve signal quality.
- **Interactive Annotation**: Allows users to label rhythms and morphologies for each ECG signal.
- **Data Saving**: Save annotated rhythms and morphologies with timestamps to a CSV file.
- **Signal Navigation**: Easily browse through ECG files in a folder.
- **Custom File Extension Support**: Option to specify file extensions (e.g., `.D20`, `.bin`) before loading files.

---

## 🛠 Requirements

- **Python** 3.7 or higher
- **Required Python Packages**:
  - `numpy`
  - `matplotlib`
  - `scipy`
  - `pywavelets`
  - `tkinter` (included with standard Python installations)

Install dependencies with:

```bash
pip install numpy matplotlib scipy pywavelets
