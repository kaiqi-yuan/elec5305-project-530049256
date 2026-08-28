# Audio Noise Reduction Using STFT-Based Spectral Processing

## ELEC5305 Project

**Student:** Kaiqi Yuan  
**SID:** 530049256  
**University:** The University of Sydney  
**Unit:** ELEC5305 Acoustics, Speech and Signal Processing

## Project Overview

Background noise can significantly reduce the quality and intelligibility of audio recordings. This project investigates an audio noise reduction system based on Short-Time Fourier Transform (STFT) spectral processing.

The noisy audio signal is divided into short overlapping frames and transformed into the time-frequency domain using the STFT. The background noise spectrum is then estimated and unwanted spectral components are reduced. Finally, the enhanced audio signal is reconstructed using the inverse STFT.

The project will be implemented mainly in MATLAB.

## Proposed Processing Pipeline

Noisy Audio  
→ Framing and Windowing  
→ STFT  
→ Noise Spectrum Estimation  
→ Spectral Noise Reduction  
→ Inverse STFT  
→ Enhanced Audio

## Objectives

- Implement STFT-based audio analysis in MATLAB.
- Develop a spectral noise reduction algorithm.
- Reconstruct enhanced audio using the inverse STFT.
- Compare spectrograms before and after noise reduction.
- Measure improvement using signal-to-noise ratio (SNR).
- Investigate the effects of different STFT parameters.

## Proposed Methods

The initial implementation will use spectral subtraction or spectral attenuation to reduce background noise.

The main parameters investigated will include:

- Frame length
- Hop size
- FFT size
- Window function
- Noise reduction strength

If time permits, Wiener filtering will also be investigated and compared with the initial method.

## Expected Results

The final project is expected to include:

- Original, noisy and enhanced audio samples
- MATLAB implementation
- Waveform comparisons
- Spectrogram comparisons
- SNR evaluation
- Analysis of different processing parameters

## Repository Structure

The repository will be updated during the project. The planned structure is:

    elec5305-project-530049256/
    ├── README.md
    ├── proposal/
    │   └── ELEC5305_Project_Proposal.pdf
    ├── src/
    │   └── MATLAB source code
    ├── audio/
    │   └── Test audio samples
    └── results/
        └── Figures and experimental results

## Project Status

Project proposal and initial planning stage.
