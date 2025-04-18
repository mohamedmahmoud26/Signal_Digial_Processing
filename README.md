# MIT-BIH Arrhythmia ECG Data Analysis 🫀📊

This project presents an exploratory data analysis (EDA) of the MIT-BIH Arrhythmia ECG dataset. The analysis aims to better understand the nature of ECG signals, visualize their patterns in both time and frequency domains, and uncover meaningful relationships between signal leads.

## 📁 Dataset

- **Source**: [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/)
- **Format**: CSV
- **Fields**:
  - `time_ms`: Time in milliseconds
  - `MLII`, `V5`: ECG signal leads

## 📌 Objectives

- Perform signal inspection using statistical and visual techniques.
- Explore the signals in both time and frequency domains.
- Understand correlations between different ECG leads.
- Lay groundwork for future classification and anomaly detection models.

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- FFT (Fast Fourier Transform)

## 📈 Key Steps

1. **Data Loading & Cleaning**  
   Loaded CSV, checked for null values, and ensured consistent types.

2. **Time-Domain Visualization**  
   Visualized ECG signals from MLII and V5 leads over time.

3. **Statistical Description**  
   Described each lead with summary statistics (mean, std, etc.).

4. **Distribution Analysis**  
   Used histograms and KDE plots to analyze the value distributions.

5. **Correlation & Relationship Analysis**  
   Used heatmaps and pairplots to understand relationships between leads.

6. **Frequency-Domain Analysis (FFT)**  
   Applied FFT to explore the dominant frequency components in the signals.

## 🖼️ Sample Visualizations

<img src="path/to/time_domain_plot.png" alt="Time Domain" width="500"/>
<img src="path/to/frequency_domain_plot.png" alt="Frequency Domain" width="500"/>

> Replace the image paths above with your actual file names or hosted links.

## 🚀 Run It Yourself

```bash
git clone https://github.com/your-username/mitbih-ecg-analysis.git
cd mitbih-ecg-analysis
pip install -r requirements.txt
python analysis.py


