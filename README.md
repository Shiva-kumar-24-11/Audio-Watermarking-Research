# Time-Domain Spread Spectrum Approach for Low-Latency Audio Watermarking

## Overview

This project presents a Time-Domain Spread Spectrum (TDSS) based audio watermarking technique designed for secure and low-latency embedding of digital information into audio signals. The research focuses on maintaining audio quality while ensuring robustness against common signal processing operations.

The work was presented at the **8th International Conference on Smart Computing and Informatics (SCI-2026)** and published in Springer Conference Proceedings.

---

## Objectives

* Develop a secure audio watermarking system.
* Achieve low-latency watermark embedding and extraction.
* Preserve audio quality and imperceptibility.
* Evaluate robustness against signal distortions and attacks.

---

## Problem Statement

Digital audio content is vulnerable to unauthorized copying, tampering, and redistribution. Traditional watermarking techniques often introduce noticeable distortion or require significant processing time.

This project addresses these challenges by implementing a Time-Domain Spread Spectrum approach that provides secure watermark embedding with minimal impact on audio quality and latency.

---

## Technologies Used

* Digital Signal Processing (DSP)
* Audio Signal Analysis
* Spread Spectrum Techniques
* MATLAB / Python (if used)
* Audio Processing Tools

---

## Methodology

### Watermark Embedding Process

1. Input audio signal acquisition.
2. Generation of pseudo-random spreading sequence.
3. Watermark signal encoding.
4. Embedding watermark into audio samples.
5. Generation of watermarked audio output.

### Watermark Extraction Process

1. Receive watermarked audio.
2. Apply correlation-based detection.
3. Recover embedded watermark.
4. Verify watermark integrity.

---

## System Architecture

```text
Original Audio
      │
      ▼
Watermark Encoder
      │
      ▼
Spread Spectrum Embedding
      │
      ▼
Watermarked Audio
      │
      ▼
Transmission / Storage
      │
      ▼
Watermark Extraction
      │
      ▼
Recovered Watermark
```

---

## Features

* Low-latency watermark embedding
* High audio quality preservation
* Robust watermark detection
* Spread spectrum security
* Suitable for real-time applications
* Protection against unauthorized content distribution

---

## Experimental Results

The proposed approach was evaluated using multiple audio samples.

Performance Metrics:

* Signal-to-Noise Ratio (SNR)
* Bit Error Rate (BER)
* Imperceptibility Analysis
* Robustness Evaluation
* Processing Latency

Results demonstrated effective watermark recovery while maintaining acceptable audio quality.

---

## Applications

* Digital Rights Management (DRM)
* Audio Copyright Protection
* Multimedia Security
* Broadcast Monitoring
* Secure Audio Communication

---

## Research Publication

**A Time-Domain Spread Spectrum Approach for Low-Latency Audio Watermarking**

Published at:

8th International Conference on Smart Computing and Informatics (SCI-2026)

Organized by Swinburne University of Technology, Hanoi, Vietnam

Published in Springer Conference Proceedings.

---

## Future Enhancements

* Real-time implementation
* FPGA-based acceleration
* Machine Learning assisted watermark detection
* Enhanced resistance to audio compression attacks
* Multi-layer watermark embedding

---

## Repository Structure

```text
Audio-Watermarking-Research/
│
├── Research_Paper.pdf
├── Presentation.pptx
├── Project_Report.pdf
├── Demo_Videos/
├── Results/
├── Images/
├── References/
└── README.md
```

---

## Author

**Shiva Kumar**

B.Tech Information and Communication Technology

Marwadi University, Rajkot, Gujarat, India

GitHub: https://github.com/Shiva-kumar-24-11

LinkedIn: https://linkedin.com/in/shiva-kumar-519a3a30a
