# ECG-Signal-Viewer-and-Annotation-Tool
ECG Signal Viewer
A Tkinter-based ECG signal viewer designed to display and analyze ECG signals from multiple leads. The tool provides interactive features to filter signals, select specific rhythms and morphologies, and save the analyzed data to a CSV file.

Features
Multi-lead ECG Display: Visualizes signals from 12 leads, with labels and gridlines for clarity.
Filtering Options: Low-pass and notch filters to improve signal quality.
Interactive Rhythm & Morphology Selection: Allows users to label signals with specific rhythms and morphologies.
Data Saving: Save the selected rhythms and morphologies along with a timestamp to a CSV file.
Navigation: Move between different ECG signals in a folder.
Custom File Extension Support: Choose the file extension of the signals before loading files.
Requirements
Python 3.7 or higher
Required Python packages:
numpy
matplotlib
scipy
pywt
tkinter (standard with Python installations)
You can install the required packages using pip:

pip install numpy matplotlib scipy pywavelets



 code
python ECG.ipynb
Load ECG Files:

Select the file extension from the dropdown menu (e.g., .D20, .bin, .ecg).
Click "Open Folder" and select the folder containing the ECG files.
Navigate and Annotate:

Use the "Next" and "Previous" buttons to navigate through ECG signals in the selected folder.
Choose the rhythm and morphology for each signal from the dropdown menus.
Click "Save" to save the annotations to a results.csv file in the same directory as the ECG files.
Code Structure
Main Application (ecg_viewer.py): Contains the main code for loading, displaying, filtering, and annotating ECG signals.
Filters: Low-pass and notch filters are applied to remove noise and enhance signal clarity.
UI Components: Built with Tkinter, with dropdown menus, buttons, and a canvas for displaying the ECG plot.
Example Files
The program reads files from the specified folder with the following supported extensions:

.D20, .D21, .D22, .bin, .ecg
Troubleshooting
Ensure that your ECG files are in a supported format.
The application is best suited for files with a sampling rate of 500 Hz and 12-lead data format.
Verify that all required Python packages are installed.
