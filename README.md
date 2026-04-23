# NEC3202-Laboratory-Report-5
Lab Report 1
_________________________________________________________________________________________________________________________________________________________________________________________________________________________
<details>
<summary>Lab Report 5 - EXPERIMENT #1 - Full Demodulation of a QPSK Signal </summary>
  
INTRODUCTION:
  
Quadrature Phase Shift Keying (QPSK) is a bandwidth-efficient digital modulation
scheme that transmits two bits per symbol. By utilizing two orthogonal carriers (Sine
and Cosine) of the same frequency, QPSK halves the required radio-frequency
spectrum compared to Binary Phase Shift Keying (BPSK) for the same bit rate. This
experiment explores the generation, channel modeling, and coherent demodulation
of QPSK signals using the Emona Telecoms-Trainer 101.
_________________________________________________________________________________________________________________________________________________________________________________________________________________________

OBJECTIVES:

- To demonstrate serial-to-parallel and parallel-to-serial data conversion.
- To implement a mathematical model of a QPSK modulator.
- To model channel effects including noise and phase shifts.
- To perform full demodulation of a QPSK signal using synchronous detection.
- To analyze the effects of varying signal-to-noise ratios (SNR) on data recovery.
_________________________________________________________________________________________________________________________________________________________________________________________________________________________
<details>
<summary>Part A - Verifying Parallel-to-Serial & Serial-to-Parallel Conversion </summary>
This phase involves converting a serial digital stream into two parallel streams and then recombining them. This is the foundation of QPSK, where data is
split to be modulated onto orthogonal carriers. 
