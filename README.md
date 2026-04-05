# audio-frequency-analyzer
Audio Frequency Analyzer & Guitar Tuner
A real-time audio analysis tool built in Python that detects fundamental pitch from live microphone input and identifies musical notes. Displays a live FFT frequency spectrum and shows tuning accuracy in cents with color-coded sharp/flat feedback.

Built with: Python, NumPy, SciPy, Matplotlib
Install dependencies:
pip install numpy scipy sounddevice matplotlib

Run:
python tuner.py

How it works:
Captures live audio at 44,100 Hz sample rate
Applies FFT to identify the dominant frequency in the 80–1200 Hz range
Maps the frequency to the nearest musical note using A4 = 440 Hz as reference
Displays tuning accuracy in cents and flags sharp/flat in real time
