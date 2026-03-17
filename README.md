# Digital Communications AWGN Simulation Platform

Course – Practical Assignment  
University of Pretoria  
Completed: September 2021

---

## Project Overview

This project involves the development of a simulation platform for digital communication systems transmitting information over an additive white Gaussian noise (AWGN) channel.

The simulation platform includes the implementation of a uniform random number generator using the Wichmann-Hill algorithm and a Gaussian random number generator using the Marsaglia-Bray algorithm. These generators are used to simulate random bit generation and noise within the communication system.

The system supports multiple modulation schemes, namely BPSK, 4QAM, 8PSK, and 16QAM. Bits are generated, mapped to symbols, transmitted through a noisy channel, and then detected at the receiver. The performance of the system is evaluated by calculating the symbol error rate (SER) and bit error rate (BER) across a range of signal-to-noise ratio (SNR) values.

The results are visualised by plotting SER and BER as functions of SNR for each modulation scheme.

👉 [View Full Project Report (PDF)](docs/EDC310_Practical_Assignment_1.pdf)

---

## Objectives

- Develop a uniform random number generator using the Wichmann-Hill algorithm to generate numbers between 0 and 1  
- Evaluate the uniform random number generator by comparing its statistics (μ, σ, σ²) to theoretical values  
- Develop a Gaussian random number generator using the Marsaglia-Bray algorithm with μ = 0 and σ = 1  
- Evaluate the Gaussian random number generator by comparing its statistics to an ideal Gaussian distribution  
- Implement a simulation platform for digital communication systems using the developed random number generators  
- Generate random bits and map them to symbols using BPSK, 4QAM, 8PSK, and 16QAM constellations  
- Add Gaussian noise to transmitted symbols over an AWGN channel  
- Perform symbol detection using Euclidean distance  
- Determine symbol error rate (SER) and bit error rate (BER)  
- Evaluate system performance over an SNR range of [-4, 12] dB  
- Plot SER and BER as functions of SNR  

---

## Tools & Technologies

- Python  
- numpy  
- random (Python package)  
- math  
- matplotlib (pyplot)  
- pandas  
- scipy.stats  

---

## Notes

This repository contains the academic report for the project.  

The implementation code is included in the appendix of the report.
