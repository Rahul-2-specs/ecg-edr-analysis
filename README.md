🫁 ECG-Derived Respiration Rate Estimation
Estimate respiration rate using ECG signals by analyzing R-R interval variability and applying frequency domain analysis.

📌 Key Features
1.Load ECG data from MIT-BIH dataset (record 100)

2.Apply bandpass filtering to remove noise

3.Detect R-peaks using HeartPy

4.Compute RR intervals and apply FFT

5.Extract dominant respiratory frequency

6.Display respiration rate in BPM

7.Visualize filtered ECG and frequency spectrum

Dependencies;
  pip install -r requirements.txt
  
  Download these files from PhysioNet:

    100.hea

    100.dat

Place them in the same directory as your script.

Run the Script

python main.py

Sample Output

Dominant Respiration Frequency: 0.23 Hz

Respiration Rate: 13.80 BPM
📈 Outputs
Filtered ECG plot

Respiration frequency spectrum

