# Fourier Transform Exercises

This repository contains a series of exercises exploring the Fourier Transform and signal processing concepts, using Python and libraries like NumPy, SciPy, and Matplotlib. Each exercise focuses on a different type of signal, transformation, or filtering technique.

---

## Table of Contents
1. [Exercise 1: Introduction to Fourier Transform](#exercise-1-introduction-to-fourier-transform)
2. [Exercise 2: Phase Shift](#exercise-2-phase-shift)
3. [Exercise 3: Square Wave](#exercise-3-square-wave)
4. [Exercise 4: Noise](#exercise-4-noise)
5. [Exercise 5: Uniform Noise](#exercise-5-uniform-noise)
6. [Exercise 6: Triangular Wave](#exercise-6-triangular-wave)
7. [Exercise 7: Sawtooth Wave](#exercise-7-sawtooth-wave)
8. [Exercise 8: Square Wave with Noise](#exercise-8-square-wave-with-noise)
9. [Exercise 9: Triangular Wave with Noise](#exercise-9-triangular-wave-with-noise)
10. [Exercise 10: Low-pass Filter](#exercise-10-low-pass-filter)
11. [Exercise 11: High-pass Filter](#exercise-11-high-pass-filter)
12. [Exercise 12: Band-pass Filter](#exercise-12-band-pass-filter)

---

## Exercise Descriptions

### Exercise 1: Introduction to Fourier Transform
We explore the Fourier Transform starting from the sum of two sine waves. Using FFT, we analyze the amplitude and phase spectrum of the signal.

### Exercise 2: Phase Shift
This exercise shows the effect of a phase shift in a signal. Time-domain plots shift horizontally, while the amplitude spectrum remains unchanged.

### Exercise 3: Square Wave
Introduction to square waves, their definition, duty cycle, and Fourier spectrum properties (odd harmonics).

### Exercise 4: Noise
We add noise to a composed sine wave signal and observe its effect on the amplitude spectrum.

### Exercise 5: Uniform Noise
A signal composed of three sine waves is combined with uniform noise. The amplitude spectrum shows the effect of the stronger second sine wave.

### Exercise 6: Triangular Wave
Triangular wave properties and its Fourier series representation. Amplitude of peaks decreases faster than for a square wave (1/n²).

### Exercise 7: Sawtooth Wave
Description of the sawtooth wave and its Fourier spectrum (all harmonics present, amplitudes decreasing with 1/n).

### Exercise 8: Square Wave with Noise
Adding uniform noise to a square wave and observing changes in the frequency spectrum.

### Exercise 9: Triangular Wave with Noise
Triangular wave with Gaussian noise. Higher harmonics are more affected, making them harder to distinguish.

### Exercise 10: Low-pass Filter
Filtering a multi-frequency sine wave to preserve low frequencies and eliminate higher ones. Demonstrates noise reduction and selective frequency preservation.

### Exercise 11: High-pass Filter
Filtering a 10 Hz square wave with a 60 Hz high-pass filter. Harmonics below 60 Hz are removed, higher remain.

### Exercise 12: Band-pass Filter
Band-pass filtering a 10 Hz square wave (20-80 Hz range). Only harmonics inside the band remain. Useful for focusing on a specific frequency range.

---

## How to Run
1.	Clone this repository to your local machine.
Example: git clone https://github.com/yourusername/yourrepo.git
2. Open the file Fourier_transform_exercises.py in your Python editor or IDE.
3. Make sure you have the required libraries installed:
  
⦁	numpy

⦁	matplotlib

⦁	scipy

You can install them using: pip install numpy matplotlib scipy

4. Run the script:

⦁	On Windows: open Command Prompt, navigate to the folder, and type:
python Fourier_transform_exercises.py

⦁	On Linux/Mac: open Terminal, navigate to the folder, and type:
python3 Fourier_transform_exercises.py

The plots and FFT results will appear in separate windows as the script runs.
