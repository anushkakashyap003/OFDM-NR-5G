# OFDM-NR-5G
Designed and simulated a 5G NR-inspired OFDM physical layer using MATLAB.
Project Overview

This project presents a MATLAB-based simulation of a 5G NR-inspired OFDM communication system, focusing on the bit error rate (BER) performance under different wireless channel conditions.
The system is designed following the physical layer principles of 5G New Radio (NR) and evaluates performance over:

AWGN (Additive White Gaussian Noise) channel

Rayleigh fading channel

The objective is to understand how noise and multipath fading affect wireless communication reliability in modern cellular systems.

System Architecture

Transmitter

Random binary data generation

QAM modulation (QPSK / 16-QAM / 64-QAM configurable)

Serial-to-parallel conversion

IFFT to generate OFDM symbols

Cyclic Prefix (CP) insertion

Parallel-to-serial conversion

Channel Models

AWGN Channel – models thermal noise

Rayleigh Fading Channel – models multipath propagation

Receiver

Serial-to-parallel conversion

CP removal

FFT operation

Channel equalization (perfect CSI assumed)

QAM demodulation

BER calculation
